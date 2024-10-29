<template>
  <div class="bg-black" style="min-height: 100vh">
    <div
      class="absolute bottom-0 left-0 right-0 top-0 bg-[linear-gradient(to_right,#4f4f4f2e_1px,transparent_1px),linear-gradient(to_bottom,#4f4f4f2e_1px,transparent_1px)] bg-[size:14px_24px] [mask-image:radial-gradient(ellipse_80%_50%_at_50%_0%,#000_70%,transparent_110%)]"
    ></div>
    <div
      class="gradient-effect absolute"
      style="width: 100%"
      ref="gradient"
    ></div>
    <div class="relative z-10">
      <header class="text-white">
        <nav class="container mx-auto p-4 flex justify-between">
          <NuxtLink to="/"
            ><p class="font-bold">Mormah <br />Studios.</p></NuxtLink
          >
          <ul class="flex gap-4">
            <li>
              <NuxtLink to="/contact" class="button">Lets Talk →</NuxtLink>
            </li>
            <li>
              <NuxtLink to="/services">
                <div class="space-y-2">
                  <span class="block w-8 h-0.5 bg-white"></span>
                  <span class="block w-8 h-0.5 bg-white"></span>
                  <span class="block w-5 h-0.5 bg-white"></span>
                </div>
              </NuxtLink>
            </li>
          </ul>
        </nav>
      </header>
      <main>
        <slot />
      </main>
      <div class="bg-red text-center py-24">
        <div>
          <ul class="flex gap-4 justify-center">
            <NuxtLink to="about" class="text-xs underline text-black"
              >ABOUT ME</NuxtLink
            >
            <NuxtLink to="portfolio" class="text-xs underline text-black"
              >WORKS</NuxtLink
            >
            <NuxtLink to="contact" class="text-xs underline text-black"
              >INSIGHTS</NuxtLink
            >
          </ul>
        </div>
        <p class="text-3xl font-bold">
          Want to create something <br />
          <span class="text-black">awesome?</span>
        </p>
        <br />
        <NuxtLink to="contact" class="button bg-black" style="border: none"
          >Lets Talk →</NuxtLink
        >
      </div>
      <footer class="flex p-8">
        <div class="w-1/2">
          <p>Stay connected with me</p>
          <h1 class="text-3xl font-bold">
            Mormah <br />
            Studios.
          </h1>
          <p class="text-sm">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Modi, eos!
          </p>
        </div>

        <div class="w-1/2">
          <p>Join Newsletter</p>
          <input type="text" class="w-full" />
        </div>
      </footer>
    </div>
  </div>
</template>

<script>
export default {
  mounted() {
    const gradient = this.$refs.gradient;
    let mouseX = 0;
    let mouseY = 0;

    const handleMouseMove = (e) => {
      mouseX = e.pageX;
      mouseY = e.pageY;

      // Set the gradient position based on mouse coordinates
      gradient.style.background = `radial-gradient(circle 300px at ${mouseX}px ${
        mouseY - window.scrollY
      }px, #FE0000, transparent)`;
      gradient.style.opacity = 1;
    };

    const handleScroll = () => {
      // Fade out the gradient when scrolling
      gradient.style.opacity = 0;

      // Optionally update the gradient position while scrolling
      gradient.style.background = `radial-gradient(circle 300px at ${mouseX}px ${
        mouseY - window.scrollY
      }px, #FE0000, transparent)`;
    };

    window.addEventListener("mousemove", handleMouseMove);
    window.addEventListener("scroll", handleScroll);

    this.cleanup = () => {
      window.removeEventListener("mousemove", handleMouseMove);
      window.removeEventListener("scroll", handleScroll);
    };
  }, // No comma here
};
</script>

<style scoped></style>
