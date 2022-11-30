<script setup lang="ts"></script>

<template>
  <div class="flex flex-col justify-center items-center mt-10 space-y-5">
    <div class="text-3xl font-bold text-red-600">hello</div>

    <div class="flex space-x-3">
      <router-link to="/home"> Home </router-link>

      <!-- better way to show the route name -->
      <router-link to="/about"> About </router-link>

      <router-link to="/jobs">
        <p>Jobs</p>
      </router-link>
    </div>
    <router-view></router-view>
  </div>
</template>

<style scoped></style>
