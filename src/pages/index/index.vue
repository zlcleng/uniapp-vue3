<template>
  <!-- #ifndef H5 -->
  <uni-nav-bar title="首页" :border="false" />
  <!-- #endif -->
  <view class="content">
	<text class="title">{{ title }}</text>
  </view>
</template>

<script setup>
import { ref } from 'vue'
import uniNavBar from '@/uni_modules/uni-nav-bar/components/uni-nav-bar/uni-nav-bar.vue'

const title = ref('Hello')
</script>

<style>
.content {
  margin: 350rpx 0;
  text-align: center;
}
.title {
  font-size: 36rpx;
  color: #8f8f94;
}
</style>
