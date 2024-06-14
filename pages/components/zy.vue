<template>
	<view class="content">
		<view class="content_top">
			<image src="../../static/icons/tx.png" class="tx" alt="" />
			<view class="content_text">大狗创工厂</view>
		</view>
		<view class="content_nr">
			<view class="content_ss_box">
				<image src="../../static/icons/fdj.png" class="fdj"></image>
				<input type="text" placeholder="关键词搜索收购方" class="inputs" />
			</view>

			<!-- <view class='zy_box'>
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


			</view> -->

			<view class="zy_box">

				<view class="zy_box1">
					<view class="zy_title1">
						海信集团有限公司
						<text class="zy_splice">-</text>
						<text class="qyxx">企业信息</text>
					</view>
					<view class="zy_children_title">1979年成立 小微企业 开业</view>
					<view class="zy_contentsd">
						<view class="zy_c_left">
							<image class="zy_c_image" src="https://gimg3.baidu.com/search/src=https%3A%2F%2Fzhengxin-pub.cdn.bcebos.com%2Flogopic%2F447480221f376151f576c2d9e738938c_fullsize.jpg&refer=http%3A%2F%2Fwww.baidu.com&app=2021&size=w256&n=0&g=0n&q=100&fmt=auto?sec=1718470800&t=c52034a3225476494fc8250b3079189f"></image>
							<view class="zy_c_info">
								<view class="zy_c_info1">法定代表人：郭进</view>
								<view class="zy_c_info2">企业已认领</view>
							</view>
						</view>
						<view class="zy_c_right">
							<button class="lxs">联系</button>
						</view>
					</view>
					
					<view class="zy_c_info1">注册资本：80617万元</view>
					<view class="zy_c_info1">企业地址：青岛市市南区东海西路17号</view>
					<view class="zy_c_info1">经营范围：国有资产委托营运...</view>
					
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
	.zy_c_info2 {
		width: fit-content;
		height: auto;
		font-size: 26rpx;
		border: 1px solid rgba(51, 102, 255, 0.5);
		box-sizing: border-box;
		padding: 10rpx;
		border-radius: 10rpx;
		color: rgb(51, 102, 255);
	}
	
	.zy_c_info1 {
		font-size: 26rpx;
		color: #33;
		margin-bottom: 10rpx;
	}
	.zy_c_info {
		width: 100%;
		height: auto;
		display: flex;
		display: flex;
		flex-direction: column;
		justify-content: center;
		margin-left: 20rpx;
	}
	.zy_c_image {
		width: 160rpx;
		height: 160rpx;
		border-radius: 20rpx;
		flex-shrink: 0;
	}
	.zy_c_left {
		width: 100%;
		height: auto;
		display: flex;
		align-items: center;
	}
	
	uni-button:after{
		border: 0;
	}
	.lxs {
		width: 160rpx;
		height: 60rpx;
		line-height: 60rpx;
		font-size: 28rpx;
		flex-shrink: 0;
		border: 0;
		background: #e8f7ff;
		color:#36f ;
	}
	.zy_contentsd {
		width: 100%;
		height: auto;
		display: flex;
		justify-content: space-between;
		align-items: center;
		margin: 10rpx 0;
	}

	.zy_children_title {
		font-size: 26rpx;
		color: #333;
		margin: 20rpx 0;
	}

	.qyxx {
		color: #2440b3;
	}

	.zy_splice {
		font-weight: bolder;
		color: #444;
		margin: 0 10rpx;
		/* font-size: ; */
	}

	.zy_box1 {
		width: 100%;
		height: auto;
	}

	.zy_title1 {
		width: 100%;
		height: auto;
		font-size: 36rpx;
		color: #f73131;
	}

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
		padding: 40rpx;
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
		padding: 40rpx;
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

	.zy5_right1 {
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