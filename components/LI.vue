<template>
  <div>
    <div class="flex items-start my-2">
      <div
        class="h-[6px] w-[6px] inline-block bg-teal-400 top-1.5 relative flex-shrink-0"
      ></div>
      <div
        class="sm:text-sm text-[13px] text-slate-600 dark:text-slate-200 mr-2"
      >
        <slot></slot>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped></style>
