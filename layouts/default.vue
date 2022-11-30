<template>
  <div>
    <p>這是預設的佈局，全部頁面都會使用到這個 Layout</p>
    <slot name="header" />
    <slot />
    <slot name="footer" />
    <!-- <slot /> 插槽是採用這個佈局模板的頁面元件會顯示內容的位置 -->
  </div>
</template>
