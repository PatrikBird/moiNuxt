<template>
  <button
    aria-label="Color Mode"
    class="action-btn w-12 h-12"
    @click="toggleDark()"
  >
    <Icon v-if="isDark" name="line-md:moon" />
    <Icon v-else name="line-md:sunny-outline-loop" />
  </button>
</template>
