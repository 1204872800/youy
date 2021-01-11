<template>
	<view class="content">
		发现
	</view>
</template>

<script>
	export default {
		data() {
			return {

			}
		},
		onLoad() {
			uni.onTabBarMidButtonTap(function() {
				console.log(1111)
			})
			// uni.setTabBarItem({
			//   index: 2,
			//   text: '改变',
			//   iconPath: '/path/to/iconPath',
			//   selectedIconPath: '/path/to/selectedIconPath'
			// })
		},
		methods: {

		}
	}
</script>

<style scoped>

</style>
