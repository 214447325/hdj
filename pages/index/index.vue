<template>
	<view class="content">
		<view class="content_top">
			<image src="../../static/icons/tx.png" class="tx" alt="" />
			<view class="content_text">大狗创工厂</view>
		</view>
		<view class="content_nr">
			<view class="content_ss_box">
				<image src="../../static/icons/fdj.png" class="fdj"></image>
				<input type="text" placeholder="关键词搜索项目" class="inputs" />
			</view>

			<view class="content_tabs">
				<view class="content_tabs_box" @click="fbxms">
					<image src="../../static/icons/book.png" class="tabs_icon"></image>
					<view class="tabs_content">项目转让</view>
				</view>
				<view class="content_tabs_box" @click="sgf">
					<image src="../../static/icons/sgf.png" class="tabs_icon"></image>
					<view class="tabs_content">收购方</view>
				</view>
				<view class="content_tabs_box" @click="hyzx">
					<image src="../../static/icons/hyzx.png" class="tabs_icon"></image>
					<view class="tabs_content">行业资讯</view>
				</view>
			</view>


			<view class="content_tjxm">
				<view class="content_tjxm_title">
					<view class="content_tjxm_left">推荐项目</view>
					<view class="content_tjxm_right">更多</view>
				</view>

				<view class="content_xm">
					<view class="content_xm_top">
						<image src="../../static/icons/xm1.png" class="xm"></image>
						<view class="content_xm_top_content">
							<view class="content_xm_title">Ai直播项目</view>
							<view class="content_xm1">时间：2024-01-27 14:00～17:00</view>
							<view class="content_xm2">
								<view class="content_xm1">行业：技术</view>
								<view class="content_xm1">标签：AI</view>
							</view>
							<view class="content_xm3">
								<view class="content_xm4">地址：</view>
								<view class="content_xm5">杭州市余杭区连胜路3号期望名作D座4楼</view>
							</view>
						</view>
					</view>
					<view class="content_xm6">
						<view class="content_xm4">简介：</view>
						<view class="content_xm5">项目建议书是项目发展周期得初始阶段，是国家选择项目得依据，也是可行性研究得依据。</view>
					</view>
				</view>


				<view class="content_xm">
					<view class="content_xm_top">
						<image src="../../static/icons/xm2.png" class="xm"></image>
						<view class="content_xm_top_content">
							<view class="content_xm_title">Ai慧对接项目</view>
							<view class="content_xm1">时间：2024-01-27 14:00～17:00</view>
							<view class="content_xm2">
								<view class="content_xm1">行业：技术</view>
								<view class="content_xm1">标签：社交</view>
							</view>
							<view class="content_xm3">
								<view class="content_xm4">地址：</view>
								<view class="content_xm5">杭州市余杭区连胜路3号期望名作D座4楼</view>
							</view>
						</view>
					</view>
					<view class="content_xm6">
						<view class="content_xm4">简介：</view>
						<view class="content_xm5">项目建议书是项目发展周期得初始阶段，是国家选择项目得依据，也是可行性研究得依据。</view>
					</view>
				</view>


			</view>

		</view>



	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: 'Hello'
			}
		},
		onLoad() {

		},
		methods: {
			fbxms() {
				uni.navigateTo({
					url: '/pages/components/fbxm'
				})
			},
			sgf() {
				uni.navigateTo({
					url: '/pages/components/zy'
				})
			},
			hyzx() {
				uni.switchTab({
					url: '/pages/index/activity'
				})
			}
		}
	}
</script>

<style scoped>
	.content {
		width: 100%;
		height: 100%;
		display: flex;
		flex-direction: column;
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
	}

	.content_nr {
		width: 100%;
		height: 100%;
		box-sizing: border-box;
		padding: 20rpx;
		/* background: red; */
	}

	.content_ss_box {
		width: 100%;
		height: 80rpx;
		background: rgba(204, 204, 204, .3);
		border-radius: 80rpx;
		overflow: hidden;
		display: flex;
		align-items: center;
		box-sizing: border-box;
		padding: 0 20px;
	}

	.fdj {
		width: 23px;
		height: 20px;
	}

	.inputs {
		margin-left: 20px;
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
		width: fit-content;
		height: 100%;
		display: flex;
		flex-direction: column;
		align-items: center;
		margin-right: 20px;
	}

	.tabs_icon {
		width: 40px;
		height: 40px;
	}

	.tabs_content {
		font-size: 24rpx;
		color: #000000;
		margin-top: 20rpx;
	}

	.content_tjxm {
		width: 100%;
		height: auto;
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

	.content_xm {
		width: 100%;
		height: auto;
		box-sizing: border-box;
		padding: 20rpx;
		box-shadow: 0 0 15px 0 rgba(204, 204, 204, .8);
		margin-top: 20rpx;
		border-radius: 10rpx;
	}

	.content_xm_top {
		width: 100%;
		height: auto;
		display: flex;
		align-items: center;
	}

	.xm {
		width: 240rpx;
		height: 180rpx;
		flex-shrink: 0;
	}

	.content_xm_top_content {
		width: 100%;
		height: auto;
		display: flex;
		flex-direction: column;
		margin-left: 10rpx;
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

	.content_xm2 {
		width: 100%;
		height: auto;
		display: flex;
		align-items: center;
	}

	.content_xm3 {
		width: 100%;
		height: auto;
		display: flex;
		/* align-items: center; */

	}

	.content_xm4 {
		font-size: 24rpx;
		color: #000000;
		flex-shrink: 0;
	}

	.content_xm5 {
		font-size: 24rpx;
		color: #000000;
	}

	.content_xm6 {
		width: 100%;
		height: auto;
		display: flex;
		margin: 20rpx 0;
	}
</style>