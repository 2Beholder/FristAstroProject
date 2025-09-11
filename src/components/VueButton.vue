<template>
   <button class="btn" @click="count++">Vue 按钮点击：{{ count }}</button>
</template>
​
<script setup>
import { ref } from "vue";
const count = ref(0);
</script>

<style lang="scss">
.btn {
  background-color: #ff9776;
  border: none;
  border-radius: 5px;
  color: white;
  cursor: pointer;
  font-size: 1rem;
  padding: 10px 15px;
  margin-left: 0;

  margin-top: 10px;
  margin-bottom: 10px;

  &:hover {
    background-color: darken(#ff9776, 10%);
  }
}
</style>
