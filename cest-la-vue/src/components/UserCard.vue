<script>
export default {
  props: {
    user: {
      type: Object,
      required: true,
    },
  },
};
</script>

<template>
  <div>
    <li class="user-card">{{ user.name }}: {{ user.website }}</li>
  </div>
</template>

<style>
.user-card {
  border: 2px solid black;
  padding: 10px;
}
</style>
