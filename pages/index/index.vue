<template>
	<view class="sortHome">
		<view class="sortHome1">
			<view class="sort1" v-on:click="is_sortByName()">
				<text>{{sortByName}}</text>
			</view>
			<view class="sort1">
				<text>{{sortAddressName}}</text>
			</view>
			<view class="sort1">
				<text>{{screenByName}}</text>
			</view>
		</view>
		
		
		
		<!-- 综合排序下拉 -->
		<view class="sort1-item" v-show="flag"  v-for="(g, index) in sortBy" :key="index">
			<view class="" v-on:click="clickz(g.name)">
				<text>{{g.name}}</text>
			</view>
			
		</view>
	</view>
	
	
</template>

<script>
	export default {
		data() {
			return {
				flag:false,
				currentScrt: 0,
				isScrt:false,//综合排序
				isAdress:false,//全国
				isScreen:false,//筛选
				sortByName:"综合排序",
				sortAddressName:"销量高",
				screenByName:"速度快",
				sortBy:[
				  { name:  "综合排序", select: false},
				  { name: "距离最近", select: false },
				  { name: "评分最高", select: false },
				  { name: "起送价最低", select: false },
				  { name: "人均高到低", select: false },
				  { name: "人均低到高", select: false }
				],
				sortAddress:[
				  {name:"郑州",select:false},
				  { name: "北京", select: false },
				  { name: "上海", select: false },
				  { name: "深圳", select: false },
				  { name: "广州", select: false },
				],
				screenBy:[
				  { title: "商家服务", select: false},
				  { title: "优惠活动", select: false }
				],
			}
		},
		methods: {
			is_sortByName(){
				this.flag=!this.flag
			},
			clickz(clickz){
				this.sortByName=clickz
			}
		}
	}
</script>

<style>
	.sortHome1{
		width: 94%;
		height: 50rpx;
		border: #000000 1rpx solid;
		display: flex;
		justify-content: space-around;
	}
	.sort1-item view{
		border-bottom: #C0C0C0 1px solid;
		width: 94%;
		height: 50rpx;
	}
</style>
