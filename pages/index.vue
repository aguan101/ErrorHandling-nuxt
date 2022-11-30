<template>
  <div class="m-4 bg-white">
    <p class="pb-4 text-2xl text-slate-600">首頁：這裡是最外層的 app.vue</p>
    <div class="my-4 flex space-x-4">
      <NuxtLink to="/about">前往 About</NuxtLink>
      <NuxtLink to="/contact">前往 Contact</NuxtLink>
      <NuxtLink to="/users/ryan">前往 Users </NuxtLink>
    </div>
    <!-- <NuxtLayout name="default"> -->
    <!-- <template #header> -->
    <p class="px-6 pt-4 text-xl text-green-500">這段會放在 header 插槽</p>
    <!-- </template> -->
    <!-- <template #default> -->
    <p class="px-6 pt-4 text-xl text-cyan-500">這段會放在 Layout 的預設插槽</p>
    <!-- </template> -->
    <!-- <template #footer> -->
    <p class="px-6 pt-4 text-xl text-blue-500">這段會放在 footer 插槽</p>
    <!-- </template> -->
    <!-- </NuxtLayout> -->
  </div>
</template>
