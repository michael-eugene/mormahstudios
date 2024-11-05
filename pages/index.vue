<template>
  <div>
    <div class="text-center">
      <div class="my-24">
        <h1 class="font-bold text-5xl xl:text-9xl px-10 md:px-20 xl:px-24">
          <span
            class="bg-clip-text text-transparent bg-gradient-to-r from-yellow-200 to-orange-900"
            >I'm Rotam</span
          >, a passionate designer specializing in digital solutions
        </h1>
        <br />
        <br />
        <a
          href="contact"
          class="rounded-3xl outline outline-1 outline-orange-900 px-10 py-4 text-lg text-white font-semibold shadow-md hover:bg-gradient-to-r from-yellow-200 to-orange-900 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-600"
        >
          Let's Talk<span aria-hidden="true"> →</span>
        </a>
        <br>
        <br>
        <div>
          <ul class="flex gap-4 justify-center m-8">
            <li class="text-xs underline"><a href="https://www.instagram.com/mxrmahs.realm/" target="_blank">INSTAGRAM</a></li>
            <li class="text-xs underline"><a href="#" target="_blank">BEHANCE</a></li>
            <li class="text-xs underline"><a href="#" target="_blank">DRIBBBLE</a></li>
          </ul>
        </div>
        <br>
        <br>
        <img src="../assets/img/company.svg" alt="" class="mx-auto" />
      </div>

      <div
        class="relative flex flex-col items-center justify-center"
        style="margin-left: 4em"
      >
        <div
          class="carousel scrollbar-hide flex w-full snap-x snap-mandatory gap-4 overflow-x-scroll scroll-smooth"
        >
          <div
            class="cursor-pointer relative aspect-[3/4] w-[45%] shrink-0 snap-start snap-always rounded-xl backdrop-blur-sm bg-black/30 rounded-2xl outline-black outline-1 md:w-[calc(33.33%-(32px/3))]"
          >
            <div class="absolute inset-0 flex items-center justify-center">
              <div class="flex justify-center">
                <img src="../assets/img/image1.svg" alt="" />
              </div>
            </div>
          </div>
          <div
            class="cursor-pointer relative aspect-[3/4] w-[45%] shrink-0 snap-start snap-always rounded-xl backdrop-blur-sm bg-black/30 rounded-2xl outline-black md:w-[calc(33.33%-(32px/3))]"
          >
            <div class="absolute inset-0 flex items-center justify-center">
              <div class="flex justify-center">
                <img src="../assets/img/image2.svg" alt="" />
              </div>
            </div>
          </div>
          <div
            class="cursor-pointer relative aspect-[3/4] w-[45%] shrink-0 snap-start snap-always rounded-xl backdrop-blur-sm bg-black/30 rounded-2xl outline-black md:w-[calc(33.33%-(32px/3))]"
          >
            <div class="absolute inset-0 flex items-center justify-center">
              <div class="flex justify-center">
                <img src="../assets/img/image3.svg" alt="" />
              </div>
            </div>
          </div>
          <div
            class="cursor-pointer relative aspect-[3/4] w-[45%] shrink-0 snap-start snap-always rounded-xl backdrop-blur-sm bg-black/30 rounded-2xl outline-black md:w-[calc(33.33%-(32px/3))]"
          >
            <div class="absolute inset-0 flex items-center justify-center">
              <div class="flex justify-center">
                <img src="../assets/img/cyberpunk.svg" alt="" />
              </div>
            </div>
          </div>
          <div
            class="cursor-pointer relative aspect-[3/4] w-[45%] shrink-0 snap-start snap-always rounded-xl backdrop-blur-sm bg-black/30 rounded-2xl outline-black md:w-[calc(33.33%-(32px/3))]"
          >
            <div class="absolute inset-0 flex items-center justify-center">
              <div class="flex justify-center">
                <img src="../assets/img/image2.svg" alt="" />
              </div>
            </div>
          </div>
          <div
            class="cursor-pointer relative aspect-[3/4] w-[45%] shrink-0 snap-start snap-always rounded-xl backdrop-blur-sm bg-black/30 rounded-2xl outline-black md:w-[calc(33.33%-(32px/3))]"
          >
            <div class="absolute inset-0 flex items-center justify-center">
              <div class="flex justify-center">
                <img src="../assets/img/image3.svg" alt="" />
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <br />
    <br />
    <br />
    <br />

    <div class="flex gap-1 px-8">
      <h1 class="text-3xl font-bold w-4/5">
        Design that sparks engagement and inspires action
      </h1>
      <div class="w-1/3">
        <p class="text-sm">
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Tempora
          architecto maxime at
        </p>
        <button class="button">Learn more</button>
      </div>
    </div>

    <div class="flex justify-between px-8">
      <p class="text-3xl">Selected Works</p>
      <NuxtLink to="/portfolio" class="button">View All →</NuxtLink>
    </div>
    <br />
    <div class="px-8">
      <div class="grid grid-cols-4 gap-1">
        <div class="col-span-1"><p class="font-bold">Mental.</p></div>
        <div class="col-span-2">
          <p class="text-sm">
            Lorem ipsum dolor sit amet consectetur, adipisicing elit.
            Necessitatibus aliquam eveniet labore exercitationem numquam cum
            iste minus, autem
          </p>
        </div>
        <div class="col-span-1 text-right">
          <NuxtLink to="portfolio/cyberpunk" class="button">View</NuxtLink>
        </div>
      </div>
      <br />
      <hr />
      <br />
      <div class="grid grid-cols-4 gap-1">
        <div class="col-span-1"><p class="font-bold">Mental.</p></div>
        <div class="col-span-2">
          <p class="text-sm">
            Lorem ipsum dolor sit amet consectetur, adipisicing elit.
            Necessitatibus aliquam eveniet labore exercitationem numquam cum
            iste minus, autem
          </p>
        </div>
        <div class="col-span-1 text-right">
          <NuxtLink to="portfolio/cyberpunk" class="button">View</NuxtLink>
        </div>
      </div>
      <br />
      <hr />
      <br />
      <div class="grid grid-cols-4 gap-1">
        <div class="col-span-1"><p class="font-bold">Mental.</p></div>
        <div class="col-span-2">
          <p class="text-sm">
            Lorem ipsum dolor sit amet consectetur, adipisicing elit.
            Necessitatibus aliquam eveniet labore exercitationem numquam cum
            iste minus, autem
          </p>
        </div>
        <div class="col-span-1 text-right">
          <NuxtLink to="portfolio/cyberpunk" class="button">View</NuxtLink>
        </div>
      </div>
      <br />
      <hr />
      <br />
    </div>

    <br />
  </div>
</template>

<script setup></script>

<style></style>
