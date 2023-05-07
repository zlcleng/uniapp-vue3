<template>
  <!-- #ifdef MP-WEIXIN -->
	<view class="nav" :style="{background: $props.barBackground}">
		<view :style="{paddingTop:nav.top+'px',height:nav.height+'px',boxSizing:'content-box'}">
			<view class="nav-title" >{{ $props.barName }}</view>
		</view>
	</view>
  <!-- #endif -->
</template>
<script>
export default {
  onLaunch: function () {
    console.log('App Launch')
  },
  onShow: function () {
    console.log('App Show')
  },
  onHide: function () {
    console.log('App Hide')
  },
}
</script>

<style>
/*每个页面公共css */
</style>
