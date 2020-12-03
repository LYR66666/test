<template>
	<view>
		<view class="circle1">
			<image class="circle2" src="../../static/shouru-icon-shuju@2x.png">
				<text class="ye">可用余额(元)</text>
				<text class="num">9245</text>
				<text class="lj">累计收益</text>
				<text class="num1">20000.00</text>
			</image>
		</view>
		<view class="rect">
			<view @click="gomx">
				<image class="mx" src="../../static/icon-details@2x.png">
					<text class="mx2">收入明细</text>
					<text class="eng">My Income details</text>
				</image>
			</view>
				<view class="tx">
					<button class="button" @click="goDetail">一键提现</button>
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
			goDetail(){
				uni.navigateTo({
					url:'/pages/tixian/tixian'
				})
			},
			gomx(){
				uni.navigateTo({
					url:'../mingxi/mingxi'
				})
			}
		}
	}
</script>

<style lang="scss">
	@import './index.scss';
</style>
