<template>
  <div :class="{ active: isActive, 'text-danger': hasError }">
    Dynamic Class Binding
  </div>
</template>

<script>
export default {
  data() {
    return {
      isActive: true,
      hasError: false,
    };
  },
};
</script>

<style>
.active {
  background-color: green;
  color: white;
}

.text-danger {
  color: red;
}
</style>
