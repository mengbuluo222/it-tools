<script setup>
import { onMounted } from 'vue';

onMounted(() => {
  (window.adsbygoogle = window.adsbygoogle || []).push({});
});
</script>

<template>
  <div class="ad-container">
    <ins
      class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-2051847344395083"
      data-ad-slot="1464414734"
      data-ad-format="auto"
      data-full-width-responsive="true"
    />
  </div>
</template>

<style scoped lang="less">
.ad-container{
    width: 100%;
    height: auto;
    // background: #ddd;
    text-align: center;
    margin: 20px auto;
}
</style>
