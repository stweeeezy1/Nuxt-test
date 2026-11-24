<template>
  <div class="p-8 space-y-6">
    <h1 class="text-2xl font-bold">Nuxt UI Test</h1>

    <div class="flex gap-3">
      <UButton label="Primary button" />
      <UButton label="Secondary" color="neutral" />
      <UButton label="Delete" color="error" />
    </div>

    <UInput placeholder="Enter your name" />

    <UTextarea placeholder="Write something..." />

    <UAlert title="Success!" description="Nuxt UI works correctly." color="success" />

    <UCard>
      <template #header> Blog post </template>
      This is a test blog post.
    </UCard>
  </div>
</template>
