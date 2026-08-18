<script setup lang="ts">
import ClipboardPlusIcon from "@iconify-vue/lucide/clipboard-plus";
</script>
<template>
  <UHeader>
    <template #title>
      <NuxtImg
        src="/logo.png"
        alt="Nuxt Logo"
        class="size-10"
        width="40"
        height="40"
      />
    </template>

    <template #right>
      <UColorModeButton />
      <UButton class="min-w-20">
        <ClipboardPlusIcon height="1em" />
        Add Task
      </UButton>
    </template>
  </UHeader>
</template>
