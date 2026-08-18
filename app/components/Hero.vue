<script setup lang="ts">
import SearchIcon from "@iconify-vue/lucide/search";
</script>
<template>
  <section
    class="bg-linear-to-r min-h-[40svh] flex items-center justify-center from-secondary dark:to-primary to-black dark:from-black text-white"
  >
    <section class="max-w-(--ui-container) mx-auto px-4 sm:px-6 lg:px-8">
      <div class="container text-center mx-auto px-4 py-16">
        <h1 class="text-4xl font-bold mb-4">Welcome to Our App</h1>
        <p class="text-xl mb-8">
          Discover the power of our platform and take your productivity to the
          next level.
        </p>
        <div class="relative w-full sm:w-1/2 md:min-w-md mx-auto">
          <UButton
            class="absolute min-h-full! z-10 right-0 top-0 rounded-s-none"
            size="xl"
          >
            Submit
          </UButton>
          <UInput
            :icon="SearchIcon"
            size="xl"
            variant="outline"
            placeholder="Search..."
            class="w-full"
          />
        </div>
      </div>
    </section>
  </section>
</template>
