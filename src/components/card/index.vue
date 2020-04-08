<template>
  <div class="Card">
    <div class="Card-title">{{ title }}</div>
    <div class="Card-content">
      <!-- 内容区域 -->
      <slot />
    </div>
  </div>
</template>

<script>
export default {
  name: "Card",
  props: {
    // 标题
    title: String
  }
};
</script>
