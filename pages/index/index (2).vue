<template>
	<view>
		<view class="menu-item">
			<text id="rm">热门问题</text>
			<text id="sr" @click="goDetail">工资收入</text>
			<text id="sk" @click="goDetail">接单上课</text>
			<text id="gz" @click="goDetail">等级规则</text>
			<text id="tiaowen"></text>
			<text id="tiaowen1"></text>
			<text id="tiaowen2"></text>
			<text id="tiaowen3"></text>
		</view>
		<view class="content">
				<text class="rk">进阶培训入口</text>
				<image src="../../static/icon-pex@2x.png" class="picture"></image>
				<image src="../../static/icon-arrow@2x.png" class="picture1" @click="goDetail"></image>
				<text class="tw1"></text>
				<image src="../../static/icon-pex@2x.png" class="picture2"></image>
				<text class="bm">专业度考核报名</text>
				<image src="../../static/icon-arrow@2x.png" class="picture3" @click="goDetail"></image>
				<text class="tw2"></text>
				<image src="../../static/icon-pex@2x.png" class="picture4"></image>
				<text class="zx">在线订单试听课资料包</text>
				<image src="../../static/icon-arrow@2x.png" class="picture5" @click="goDetail"></image>
				<text class="tw3"></text>
				<image src="../../static/icon-pex@2x.png" class="picture6"></image>
				<text class="bl">伯乐奖</text>
				<image src="../../static/icon-arrow@2x.png" class="picture7" @click="goDetail"></image>
				<text class="tw4"></text>
				<image src="../../static/icon-pex@2x.png" class="picture11"></image>
				<text class="sy">生源、投递订单、课时费相关问题</text>
				<image src="../../static/icon-arrow@2x.png" class="picture8" @click="goDetail"></image>
				<text class="tw5"></text>
				<image src="../../static/icon-pex@2x.png" class="picture9"></image>
				<text class="jc">基础培训报名入口</text>
				<image src="../../static/icon-arrow@2x.png" class="picture10" @click="goDetail"></image>
				<text class="tw6"></text>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			}
		},
		onLoad() {

		},
		methods: {
			goDetail(){
				uni.navigateTo({
					url:'/pages/detail/detail1'
				})
			}
				}
		}
</script>

<style lang="scss">
	@import './index.scss';
</style>
