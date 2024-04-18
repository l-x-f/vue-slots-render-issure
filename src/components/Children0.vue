<template>
  <div>
    <slot name="default">
      <component v-if="$slots.default" :is="$slots.default" />
      <template v-else> default-value</template>
    </slot>
  </div>
</template>
