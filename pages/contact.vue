<template>
  <div>
    <div class="mx-auto text-center">
      <h1 class="font-bold text-5xl md:text-9xl md:px-24">
        <span
          class="bg-clip-text text-transparent bg-gradient-to-r from-yellow-200 to-orange-900"
          >Say Hi!</span
        >, and tell me about your idea
      </h1>
    </div>

    <div class="px-8 md:px-64">
      <form class="space-y-6 flex flex-col my-20">
        <div>
          <label
            for="name"
            class="block text-sm font-medium text-gray-700 dark:text-white"
            >Name</label
          >
          <div class="mt-1">
            <input
              id="name"
              type="text"
              required
              placeholder="Hello..."
              class="block w-full appearance-none border-b border-b-white px-3 py-2 placeholder-gray-900 shadow-sm focus:border-red focus:outline-none focus:ring-red dark:bg-transparent dark:border-gray-600 dark:text-white dark:placeholder-gray-700 dark:focus:border-red-500 dark:focus:ring-red-500 sm:text-sm"
            />
          </div>
        </div>
        <div>
          <label
            for="email"
            class="block text-sm font-medium text-gray-700 dark:text-white"
            >Email Address</label
          >
          <div class="mt-1">
            <input
              id="email"
              type="email"
              required
              placeholder="Where can I reply?"
              class="block w-full appearance-none border-b border-b-white px-3 py-2 placeholder-gray-900 shadow-sm focus:border-red focus:outline-none focus:ring-red dark:bg-transparent dark:border-gray-600 dark:text-white dark:placeholder-gray-700 dark:focus:border-red-500 dark:focus:ring-red-500 sm:text-sm"
            />
          </div>
        </div>
        <div>
          <label
            for="company_name"
            class="block text-sm font-medium text-gray-700 dark:text-white"
            >Company Name</label
            >
            <div class="mt-1">
              <input
              id="company_name"
              name="company_name"
              placeholder="Your company or website"
              type="company_name"
              class="block w-full appearance-none border-b border-b-white px-3 py-2 placeholder-gray-900 shadow-sm focus:border-red focus:outline-none focus:ring-red dark:bg-transparent dark:border-gray-600 dark:text-white dark:placeholder-gray-700 dark:focus:border-red-500 dark:focus:ring-red-500 sm:text-sm"
            />
          </div>
        </div>
        <button
          type="submit"
          class="max-w-max rounded-3xl border border-transparent bg-red px-4 py-2 text-sm font-medium text-white hover:bg-red-500 focus:outline-none focus:ring-2 focus:ring-red focus:ring-offset-2 dark:bg-red dark:border-transparent dark:hover:bg-red dark:focus:ring-red dark:focus:ring-offset-2 disabled:cursor-wait disabled:opacity-50"
        >
          Submit
        </button>
      </form>
    </div>
  </div>
</template>

<script setup></script>

<style scoped></style>
