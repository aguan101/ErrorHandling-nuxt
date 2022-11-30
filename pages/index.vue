<template>
  <div>
    <BaseApplyButton />
    <h1>這裡是首頁</h1>
    <NuxtLink to="/about">前往 About </NuxtLink>
    <NuxtLink to="/contact">前往 Contact </NuxtLink>
    <NuxtLink to="/users/ryan">前往 Users </NuxtLink>
    <NuxtLayout name="default">
      <template #header>
        <p>這段會放在 header 插槽</p>
      </template>
      <template #default>
        <p>這段會放在 Layout 的預設插槽</p>
      </template>
      <template #footer>
        <p>這段會放在 footer 插槽</p>
      </template>
    </NuxtLayout>
  </div>
</template>
