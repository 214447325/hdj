<template>
	<view class="rz">
		<view class="rz1">
			<view class="rz11">公司（项目）名称</view>
			<view class="rz12">
				<input type="text" class="input1" placeholder="请输入公司名称" />
			</view>
		</view>

		<view class="rz1">
			<view class="rz11">姓名</view>
			<view class="rz12">
				<input type="text" class="input1" placeholder="请输入姓名" />
			</view>
		</view>

		<view class="rz1">
			<view class="rz11">微信号</view>
			<view class="rz12">
				<input type="text" class="input1" placeholder="请输入微信号" />
			</view>
		</view>

		<view class="rz1">
			<view class="rz11">互换微信</view>
			<view class="rz12">
				<view class="radios">
					<view class="radiosw"></view>
					<view class="radiostext">免审核</view>
				</view>
				<view class="radios">
					<view class="radiosw"></view>
					<view class="radiostext">待审核</view>
				</view>
				<!-- <radio-group @change="radioChange">
					<label class="uni-list-cell uni-list-cell-pd" v-for="(item, index) in items" :key="item.value">
						<view>
							<radio :value="item.value" :checked="index === current" />
						</view>
						<view>{{item.name}}</view>
					</label>
				</radio-group> -->
			</view>
		</view>

		<view class="rz1">
			<view class="rz11">职务标签</view>
			<view class="rz12">
				<picker @change="bindPickerChange" :value="index" :range="zwbq">
					<view class="uni-input">{{zwbq[index]}}</view>
				</picker>
			</view>
		</view>

		<view class="rz1">
			<view class="rz11">所在行业</view>
			<view class="rz12">
				<picker @change="bindPickerChange" :value="index" :range="hy">
					<view class="uni-input">{{hy[index]}}</view>
				</picker>
			</view>
		</view>

		<view class="rz1">
			<view class="rz11">所在城市</view>
			<view class="rz12">
				<picker @change="bindPickerChange" :value="index" :range="citity">
					<view class="uni-input">{{citity[index]}}</view>
				</picker>
			</view>
		</view>

		<!-- <view class="lxfs">联系方式：18888888888</view> -->
	</view>
</template>

<script>
	export default {
		data() {
			return {
				items: [{
						value: 'msh',
						name: '免审核',
						checked: 'true'
					},
					{
						value: 'dsh',
						name: '待审核'
					}
				],
				index: 0,
				zwbq: ['工程师', '设计师', '主管', 'CEO'],
				hy: ['金融', '教育', 'AI'],
				citity: ['北京', '上海', '广州']
			}
		},
		methods: {
			radioChange() {

			},
			bindPickerChange() {

			}
		}
	}
</script>

<style scoped>
	.rz {
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

	.rz1 {
		width: 100%;
		height: 100rpx;
		/* background: red; */
		display: flex;
		align-items: center;
		border-bottom: 1px solid #C4C4C4;
	}

	.rz11 {
		width: 130px;
		height: auto;
		font-size: 16px;
		color: #383838;
		flex-shrink: 0
	}

	.rz12 {
		width: 100%;
		height: 100%;
		display: flex;
		align-items: center;
		margin-left: 20rpx;
		display: flex;
		align-items: center;
		/* flex-directio; */
	}

	.input1 {
		width: 100%;
		height: 100%;
	}

	.lxfs {
		width: 100%;
		height: auto;
		position: absolute;
		left: 0;
		bottom: 30px;
		right: 0;
		text-align: center;
		font-size: 16px;
		color: #C4C4C4;
	}

	.radios {
		width: fit-content;
		height: auto;
		display: flex;
		align-items: center;
		margin-right: 10px;
	}
	
	.radiosw {
		width: 15px;
		height: 15px;
		border: 1px solid #C4C4C4;
		border-radius: 20px;
	}
	.radiostext {
		margin-left: 10px;
	}
</style>