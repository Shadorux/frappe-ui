<script setup lang="ts">
import { LoadingIndicator } from 'frappe-ui'
</script>

<template>
  <div class="w-80 rounded-6 border border-outline-gray-1 bg-surface-base p-4">
    <div class="text-base-medium text-ink-gray-8">Revenue by month</div>
    <div class="text-sm text-ink-gray-5">Last 12 months</div>
    <div class="flex h-40 items-center justify-center text-ink-gray-5">
      <LoadingIndicator :scale="150" />
    </div>
  </div>
</template>
