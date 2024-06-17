<template>
	<view class="my_box">

		<view class="content_top">
			<image src="../../static/icons/tx.png" class="tx" alt="" />
			<view class="content_text">
				<view>陈鹏</view>
				<view class="country">上海科技有限公司</view>
			</view>
		</view>

		<view class="my_content">

			<view class="content_tabs">
				<view class="content_tabs_box" @click="yhrz">
					<image src="../../static/icons/rz.png" class="tabs_icon"></image>
					<view class="tabs_content">用户认证</view>
				</view>
				
				<view class="content_tabs_box" @click="lxr">
					<image src="../../static/icons/phone.png" class="tabs_icon"></image>
					<view class="tabs_content">联系人</view>
				</view>

			</view>

		</view>


	</view>
</template>

<script>
	export default {
		data() {
			return {

			}
		},
		methods: {
			yhrz(){
				uni.navigateTo({
					url:'/pages/components/rz'
				})
			},
			lxr() {
				uni.navigateTo({
					url:'/pages/components/lxr'
				})
			}
		}
	}
</script>

<style scoped>
	.my_box {
		width: 100%;
		height: auto;

	}

	.content_top {
		width: 100%;
		height: 260rpx;
		background: #01ACFE;
		display: flex;
		align-items: center;
		box-sizing: border-box;
		padding: 20rpx;
		flex-shrink: 0;
	}

	.tx {
		width: 100rpx;
		height: 100rpx;
		border-radius: 100rpx;
	}

	.content_text {
		margin-left: 40rpx;
		font-size: 48rpx;
		color: #FFFFFF;
		font-family: '阿里妈妈数黑体';
		display: flex;
		flex-direction: column;
	}

	.country {
		font-size: 16px;
		color: #FFFFFF;
		margin-top: 20rpx;
	}

	.my_content {
		width: 100%;
		height: auto;
		box-sizing: border-box;
		padding: 20rpx;
	}

	.content_tabs {
		width: 100%;
		height: auto;
		/* background: red; */
		display: flex;
		/* justify-content: space-between; */
		align-items: center;
		margin-top: 20px;
	}

	.content_tabs_box {
		width: 130rpx;
		height: 100%;
		display: flex;
		flex-direction: column;
		align-items: center;
		margin-right: 40rpx;
	}

	.tabs_icon {
		width: 20px;
		height: 20px;
	}

	.tabs_content {
		font-size: 24rpx;
		color: #000000;
		margin-top: 20rpx;
	}
</style>