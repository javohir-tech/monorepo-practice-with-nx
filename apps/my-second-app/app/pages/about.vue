<script setup lang="ts">
import { MyButton } from "@my-workspace/shared"
</script>

<template>
  <div class="about">
    <h1>This is an about page.</h1>
    <MyButton />
  </div>
</template>

<style>
@media (min-width: 768px) {
  .about {
    max-width: 768px;
    margin-left: auto;
    margin-right: auto;
    padding: 0 1rem;
  }
}
</style>
