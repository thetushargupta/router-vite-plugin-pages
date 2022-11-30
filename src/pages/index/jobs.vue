<script setup lang="ts"></script>

<template>
  <div class="text-3xl text-green-600">This is Job view</div>

  <div class="flex space-x-3">
    <router-link to="/jobs/OldPostings"> Old Jobs</router-link>

    <router-link to="/jobs/NewPostings">
      <p>New Jobs</p>
    </router-link>
  </div>
  <router-view></router-view>
</template>

<style scoped></style>
