<script setup>
const ROUTE = useRoute()
const { id } = ROUTE.params
</script>

<template>
  <div>
    <h1>這裡是 Users 動態路由頁面</h1>
    <p>匹配到的 id 是：{{ id }}</p>
  </div>
</template>
