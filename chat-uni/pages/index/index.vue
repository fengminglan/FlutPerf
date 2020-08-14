<template>
	<view class="container">
	</view>
</template>

<script>
	export default {
		data() {
			return {
				test: 1,
			}
		},
		methods: {
			onShow() {
				uni.navigateTo({
				    url: '../login/login'
				});
			}
		}
	}
</script>

<style>
	.container {
		padding: 20px;
		font-size: 14px;
		line-height: 24px;
	}
</style>
