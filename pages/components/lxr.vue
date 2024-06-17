<template>
	<view class="activity">
		<view class="activity_box">
			<view class="a_line" @click="callPhone('10086')">
				<view class="a_title">陈鹏</view>
				<view class="a_time">10086</view>
			</view>


			<!-- <view class="a_line">
				<view class="a_title">陈鹏</view>
				<view class="a_time">18888888888</view>
			</view> -->

			<!-- <view class="a_line">
				<view class="a_title">步行者</view>
				<view class="a_time">2023-10-31</view>
			</view>
			
			<view class="a_line">
				<view class="a_title">每周一贴</view>
				<view class="a_time">2023-10-31</view>
			</view>
			<view class="a_line">
				<view class="a_title">01建社群的5大条件</view>
				<view class="a_time">2023-10-31</view>
			</view>
			<view class="a_line">
				<view class="a_title">慧对接资源中心NO.9空间喜报</view>
				<view class="a_time">2023-10-31</view>
			</view>
			
			<view class="a_line1">慧对接（杭州）信息有限公司</view> -->
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
			callPhone(phone) {
				uni.makePhoneCall({
					phoneNumber: phone,
					success: function() {
						console.log('拨号成功')
					},
					fail: function() {
						console.log('拨号失败')
					}
				})
				// uni.navigateTo({
				// 	url: '/pages/components/gywm'
				// })
			}
		}
	}
</script>

<style scoped>
	.a_line1 {
		width: fit-content;
		height: auto;
		margin: 20rpx auto;
		font-size: 26rpx;
		color: rgb(1, 172, 254);
	}

	.a_line {
		width: 100%;
		height: 60rpx;
		/* background: red; */
		border-bottom: 1px solid #B1BEBE;
		display: flex;
		align-items: center;
		justify-content: space-between;
		box-sizing: border-box;
		font-size: 26rpx;

	}

	.a_title {
		color: #000000;
		font-weight: bolder;
	}

	.a_time {
		color: #B1BEBE;
	}

	.activity {
		width: 100%;
		height: auto;
		/* box-sizing: border-box; */
		/* padding: auto; */
	}

	.activity_title {
		width: 100%;
		height: 260rpx;
		background: #01ACFE;
		font-size: 40rpx;
		color: #FFFFFF;
		display: flex;
		justify-content: center;
		align-items: center;
	}

	.activity_box {
		width: 100%;
		height: auto;
		box-sizing: border-box;
		padding: 40rpx;
	}

	.content_tjxm_title {
		width: 100%;
		height: auto;
		display: flex;
		align-items: center;
		justify-content: space-between;
		margin-top: 40rpx;
	}

	.content_tjxm_left {
		color: #000000;
		font-size: 40rpx;
	}

	.content_tjxm_right {
		font-size: 32rpx;
		color: #B1BEBE;
	}

	.activity_boxs {
		width: 100%;
		height: auto;
		display: flex;
		align-items: center;
		box-sizing: border-box;
		padding: 20rpx;
		box-shadow: 0 0 15px 0 rgba(204, 204, 204, .8);
		margin-top: 20rpx;
		border-radius: 10rpx;
	}

	.hd {
		width: 200rpx;
		height: 120rpx;
		flex-shrink: 0;
	}

	.activity_boxs1 {
		width: 100%;
		height: auto;
		display: flex;
		flex-direction: column;
		justify-content: space-between;
		margin-left: 20rpx;
	}

	.content_xm_title {
		font-size: 40rpx;
		color: #000000;
		font-weight: bolder;
	}

	.content_xm1 {
		font-size: 24rpx;
		color: #000000;
		margin-right: 20rpx;
		margin-bottom: 10rpx;
	}
</style>