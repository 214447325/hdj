<template>
	<view class="fbxms">
		<view class="fbxm1">
			<view class="fbxm1_left">我的头像</view>
			<view class="tx_view">
				<image src="../../static/icons/tx.png" class="txImage"></image>
			</view>
		</view>

		<view class="fbxm1">
			<view class="fbxm1_left">项目名称</view>
			<input type="text" placeholder="请填写项目名称" class="input_text" />
		</view>

		<view class="fbxm1">
			<view class="fbxm1_left">行业</view>
			<input type="text" placeholder="请填写行业" class="input_text" />
		</view>

		<view class="fbxm1">
			<view class="fbxm1_left">城市</view>
			<input type="text" placeholder="请填写城市" class="input_text" />
		</view>

		<view class="fbxm1">
			<view class="fbxm1_left">联系人</view>
			<input type="text" placeholder="请填写联系人" class="input_text" />
		</view>

		<view class="fbxm1">
			<view class="fbxm1_left">微信号</view>
			<input type="text" placeholder="请填写微信号" class="input_text" />
		</view>

		<view class="fbxm1">
			<view class="fbxm1_left">项目简介</view>
			<textarea placeholder="请填写项目简介" class="fbxm1_right" />
		</view>

		<view class="reads">
			<label class="radio"><radio value="r1" checked="true" />勾选代表同意<text class="xy">《发布项目协议》</text></label>
		</view>
		
		<view class="btns">提交</view>
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
	.fbxms {
		width: 100%;
		height: 100%;
		/* background: red; */
		position: absolute;
		top: 0;
		left: 0;
		right: 0;
		bottom: 0;
		box-sizing: border-box;
		padding: 20rpx;
	}

	.fbxm1 {
		width: 100%;
		height: auto;
		min-height: 50rpx;
		border-bottom: 1px solid #C4C4C4;
		display: flex;
		align-items: center;
		box-sizing: border-box;
		padding: 20rpx 0;
	}

	.fbxm1_left {
		width: 100px;
		min-height: 50rpx;
		color: #383838;
		font-size: 16px;
		flex-shrink: 0;
		/* margin-right: 20rpx; */
	}

	.tx_view {
		width: 50px;
		height: 50px;
		background: rebeccapurple;
		border-radius: 50px;
		overflow: hidden;
	}

	.txImage {
		width: 100%;
		height: 100%;
	}

	.input_text {
		width: 100%;
		height: 100%;
	}

	.fbxm1_right {
		width: 100%;
		height: 100px;
		border: 1px solid #C4C4C4;
		box-sizing: border-box;
		padding: 20rpx;
		border-radius: 5rpx;
	}

	.reads {
		width: 100%;
		height: 100px;
		display: flex;
		justify-content: center;
		align-items: center;
		margin: 20px 0;
	}
	.xy {
		color: rgb(1, 172, 254);
	}
	
	.btns {
		width: 100%;
		height: 50px;
		font-size: 16px;
		background: rgb(1, 172, 254);
		color: white;
		display: flex;
		align-items: center;
		justify-content: center;
		border-radius: 5px;
	}
</style>