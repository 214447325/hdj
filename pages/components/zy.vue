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

			<view class='zy_box'>
				<view class="zy1">
					<image src="../../static/icons/tx.png" class="tx1"></image>
					<view class="zy1_name">陈鹏</view>
				</view>

				<view class="zy2">
					<image src="../../static/icons/dw.png" class="dw"></image>
					<view class="zy21">杭州市余杭区连胜路3号期望名作D座4楼</view>
				</view>

				<view class="zy2">
					<view class="zy31">其他</view>

					<view class="zy32">合伙人</view>
				</view>

				<view class="zy4">
					<view class="zy_title">微信号</view>
					<view class="zy_text">****</view>
					<view class="hhwx">互换微信</view>
				</view>

				<view class="zy5">
					<view>
						<text class="zy_title">公司：</text>
						<text class="zy_text">慧对接</text>
					</view>
					<view class="zy5_right">
						<image src="../../static/icons/hy.png" class="zs" mode=""></image>
						<text>6级</text>
					</view>
				</view>

				<view class="zy5">
					<view>
						<text class="zy_title">我的资源：</text>
					</view>
					<view class="zy5_right">
						<text>慧对接值9983W</text>
					</view>
				</view>

				<view class="zy5">
					<view>
						<text class="zy_text">暂无资源</text>
					</view>
					<view class="zy5_right1">
						<text class="zy5_text">真实</text>
						<image src="../../static/icons/wjx.png" class="xx"></image>
						<image src="../../static/icons/wjx.png" class="xx"></image>
						<image src="../../static/icons/wjx.png" class="xx"></image>
						<image src="../../static/icons/wjx.png" class="xx"></image>
						<image src="../../static/icons/wjx.png" class="xx"></image>
					</view>
				</view>
				
				<view class="zy5">
					<view>
						<text class="zy_title">我的需求</text>
					</view>
					<view class="zy5_right1">
						<text class="zy5_text">资源</text>
						<image src="../../static/icons/wjx.png" class="xx"></image>
						<image src="../../static/icons/wjx.png" class="xx"></image>
						<image src="../../static/icons/wjx.png" class="xx"></image>
						<image src="../../static/icons/wjx.png" class="xx"></image>
						<image src="../../static/icons/wjx.png" class="xx"></image>
					</view>
				</view>
				
				<view class="zy5">
					<view>
						<text class="zy_text">暂无资源</text>
					</view>
					<view class="zy5_right1">
						<text class="zy5_text">利他</text>
						<image src="../../static/icons/wjx.png" class="xx"></image>
						<image src="../../static/icons/wjx.png" class="xx"></image>
						<image src="../../static/icons/wjx.png" class="xx"></image>
						<image src="../../static/icons/wjx.png" class="xx"></image>
						<image src="../../static/icons/wjx.png" class="xx"></image>
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

			}
		},
		methods: {

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

	.zy_box {
		width: 100%;
		height: auto;
		box-sizing: border-box;
		padding: 20rpx;
		box-shadow: 0 0 15px 0 rgba(204, 204, 204, .8);
		margin-top: 40rpx;
		border-radius: 5px;
	}

	.zy1 {
		width: 100%;
		height: auto;
		display: flex;
		align-items: center;
	}

	.tx1 {
		width: 100rpx;
		height: 100rpx;
		border-radius: 100rpx;
	}

	.zy1_name {
		font-size: 32rpx;
		margin-left: 20rpx;
		font-weight: bolder;
	}

	.zy2 {
		width: 100%;
		height: auto;
		margin: 20rpx 0;
		display: flex;
		align-items: center;
	}

	.dw {
		width: 30rpx;
		height: 30rpx;
		margin-right: 20rpx;
	}

	.zy21 {
		font-size: 28rpx;
		color: #000000;
	}

	.zy31 {
		width: fit-content;
		height: auto;
		background: #9DBD5A;
		font-size: 24rpx;
		color: #FFFFFF;
		box-sizing: border-box;
		padding: 10rpx 20rpx;
		border-radius: 10rpx;
		margin-right: 20rpx;
	}

	.zy32 {
		width: fit-content;
		height: auto;
		background: #5081BC;
		font-size: 24rpx;
		color: #FFFFFF;
		box-sizing: border-box;
		padding: 10rpx 20rpx;
		border-radius: 10rpx;
		margin-right: 20rpx;
	}

	.zy4 {
		width: 100%;
		height: auto;
		display: flex;
		align-items: center;
		margin-bottom: 30rpx;
	}

	.zy_title {
		font-size: 28rpx;
		color: #C4C4C4;
		margin-right: 10rpx;
	}

	.zy_text {
		font-size: 28rpx;
		color: #000000;
	}

	.hhwx {
		width: fit-content;
		height: auto;
		font-size: 28rpx;
		color: #C4C4C4;
		box-sizing: border-box;
		padding: 10rpx 20rpx;
		border: 1px solid #C4C4C4;
		margin-left: 20rpx;
		border-radius: 40rpx;
	}

	.zy5 {
		width: 100%;
		height: auto;
		display: flex;
		justify-content: space-between;
		align-items: center;
		margin-bottom: 20rpx;
	}

	.zy5_right {
		width: fit-content;
		height: auto;
		display: flex;
		align-items: center;
		font-size: 28rpx;
		color: #01ACFE;
	}
	.zy5_right1{
		width: 280rpx;
		height: auto;
		display: flex;
		align-items: center;
		font-size: 28rpx;
		color: #01ACFE;
		justify-content: end;
	}
	

	.zs {
		width: 30rpx;
		height: 30rpx;
		margin-right: 10rpx;
	}

	.zy5_text {
		font-size: 24rpx;
		color: #000000;
		margin-right: 10rpx;
	}
	
	.xx {
		width: 30rpx;
		height: 30rpx;
		margin-right: 10rpx;
	}
</style>