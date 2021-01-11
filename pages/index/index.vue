<template>
	<view class="content">
		  首页
	</view>
</template>

<script>
	export default {
		data() {
			return {
		
			}
		},
		onLoad() {
		   uni.setTabBarBadge({
		     index: 3,
		     text: '4'
		   })
		},
		methods: {

		}
	}
</script>

<style scoped>

</style>
