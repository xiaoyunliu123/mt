<template>
	<view>
		<view class="content" style="width: 100%;background-color: #FF9933;padding-top: 10px;">
			<view class="" style="background-color: #D8BFD8;width: 100%;height: auto;border-top-left-radius: 20px;border-top-right-radius: 20px;">
				<view style="height: 20px;"></view>
				<view class="input-view">
					<uni-icons class="input-uni-icon" type="search" size="22" color="#666666" />
					<input confirm-type="search" class="nav-bar-input" type="text" placeholder="输入搜索关键词" @confirm="confirm">
				</view>
				<view style="margin-top: 10px;padding: 0 15px;display: flex;justify-content: space-evenly;">
					<view class="shipin">
						<text>鱼丸汤</text>
					</view>
					<view class="shipin">
						<text>麻辣烫</text>
					</view>
					<view class="shipin">
						<text>奶茶</text>
					</view>
					<view class="shipin">
						<text>炸鸡</text>
					</view>
					<view class="shipin">
						<text>米线</text>
					</view>
					<view class="shipin">
						<text>粥</text>
					</view>
					<view class="shipin">
						<text>饺子</text>
					</view>
				</view>
				<swiper :indicator-dots="true" :autoplay="false" :interval="3000" :duration="1000" class="swip">
					<swiper-item>
						<view class="swiper-item">
							<view class="tubiao">
								<image src="/static/images/1.png"  mode=""></image>
							</view>
							<view class="tubiao">
								<image src="/static/images/2.png"  mode=""></image>
							</view>
							<view class="tubiao">
								<image src="/static/images/3.png"  mode=""></image>
							</view>
							<view class="tubiao">
								<image src="/static/images/4.png"  mode=""></image>
							</view>
							<view class="tubiao">
								<image src="/static/images/5.png"  mode=""></image>
							</view>
							<view class="tubiao">
								<image src="/static/images/6.png"  mode=""></image>
							</view>
							<view class="tubiao">
								<image src="/static/images/7.png"  mode=""></image>
							</view>
							<view class="tubiao">
								<image src="/static/images/8.png"  mode=""></image>
							</view>
							<view class="tubiao">
								<image src="/static/images/9.png"  mode=""></image>
							</view>
							<view class="tubiao">
								<image src="/static/images/10.png"  mode=""></image>
							</view>
						</view>
					</swiper-item>
					<swiper-item>
						<view class="swiper-item">
							<view class="tubiao">
								<image src="/static/images/11.png"  mode=""></image>
							</view>
							<view class="tubiao">
								<image src="/static/images/12.png"  mode=""></image>
							</view>
							<view class="tubiao">
								<image src="/static/images/13.png"  mode=""></image>
							</view>
							<view class="tubiao">
								<image src="/static/images/14.png"  mode=""></image>
							</view>
							<view class="tubiao">
								<image src="/static/images/15.png"  mode=""></image>
							</view>
							<view class="tubiao">
								<image src="/static/images/16.png"  mode=""></image>
							</view>
							<view class="tubiao">
								<image src="/static/images/17.png"  mode=""></image>
							</view>
							<view class="tubiao">
								<image src="/static/images/18.png"  mode=""></image>
							</view>
							<view class="tubiao">
								<image src="/static/images/19.png"  mode=""></image>
							</view>
							<view class="tubiao">
								<image src="/static/images/20.png"  mode=""></image>
							</view>
						</view>
					</swiper-item>
				</swiper>
				<view class="gong">
					<view class="g-item">
						<view class="g-item1">
							<image src="/static/images/hongbao.png" mode="aspectFit"></image>
						</view>
						<view class="g-item2">
							<view style="display: flex;">
								<text style="font-size: 11px;">
									饭点打卡领金币福袋
								</text>
								<view class="g-item-c3">
									<image src="../../static/images/money.png"  mode="aspectFit"></image>
								</view>
								<text class="g-item-c4">+5</text>
							</view>
							<text class="g-item-c5">下单支付满20元即可领</text>
							
						</view>
					</view>
					<view class="g-item3">
						<button>去领取</button>
					</view>
				</view>
				
				<swiper :indicator-dots="true" :autoplay="true" :interval="3000" :duration="1000" class="banner">
					<swiper-item>
						<view class="swiper-item">
							<image src="/static/images/banner1.png"></image>
						</view>
					</swiper-item>
					<swiper-item>
						<view class="swiper-item">
							<image src="/static/images/banner2.png"></image>
						</view>
					</swiper-item>
				</swiper>
				<view class="middles">
					<view class="midd-item1">
						<view class="midd-item1-a1">
							<image src="../../static/images/a1.png" mode="aspectFill"></image>
						</view>
						<view class="midd-item1-a2">
							<text class="midd-item1-b1">兰州牛肉拉面 (嘉祥里...)</text>
							<view class="midd-item1-b2">
								<view class="midd-item1-c1">
									<text>附近热卖</text>
								</view>
								<view class="midd-item1-c2">
									<image src="../../static/images/xing.png" mode="aspectFill"></image>
								</view>
								<view class="midd-item1-c3">
									<text>4.6</text>
								</view>
								<view class="midd-item1-c4">
									<text>30分钟</text>
								</view>
							</view>
						</view>
						<view class="midd-item1-a3">
							<text style="display: block">进店</text>
							<image src="../../static/images/more.png" mode="aspectFill"></image>
						</view>
					</view>
					<view class="midd-item2">
						<view>
							<text>28减2</text>
						</view>
						<view>
							<text>38减4</text>
						</view>
						<view>
							<text>50减7</text>
						</view>
						<view>
							<text>100减13</text>
						</view>
					</view>
					<view class="midd-item3">
						<view class="midd-item3-a1">
							<image src="../../static/images/a2.png" mode="aspectFill"></image>
							<text>牛肉炒刀削面</text>
							<view>
								<image src="/static/images/lingqian.png" mode="aspectFit"></image>
								<text>17</text>
							</view>
						</view>
						<view class="midd-item3-a1">
							<image src="../../static/images/a2.png" mode="aspectFill"></image>
							<text>牛肉炒刀削面</text>
							<view>
								<image src="/static/images/lingqian.png" mode="aspectFit"></image>
								<text>17</text>
							</view>
						</view>
						
						<view class="midd-item3-a1">
							<image src="../../static/images/a2.png" mode="aspectFill"></image>
							<text>牛肉炒刀削面</text>
							<view>
								<image src="/static/images/lingqian.png" mode="aspectFit"></image>
								<text>17</text>
							</view>
						</view>
					</view>
				</view>
				<view class="moreFour">
					<view class="more1">
						<text class="more1-item1" space="nbsp">神 价 格</text>
						<text class="more1-item2">这么买更实惠</text>
						<view class="more1-item3">
							<text>更多</text>
							<image src="../../static/images/more.png" mode="aspectFill"></image>
						</view>
					</view>
					<view class="more2">
						<scroll-view scroll-x="true">
							<view class="more2-item1">
								<view class="more2-item1-a">
									<image src="../../static/images/a2.png" mode="aspectFit"></image>
									<text class="more2-item1-a1">招牌肌肉腿饭</text>
									<view class="">
										<text class="more2-item1-a2">￥</text>
										<text class="more2-item1-a3">14.99</text>
										<text class="more2-item1-a4">￥26</text>
									</view>
								</view>
								<view class="more2-item1-a">
									<image src="../../static/images/a2.png" mode="aspectFit"></image>
									<text class="more2-item1-a1">招牌肌肉腿饭</text>
									<view class="">
										<text class="more2-item1-a2">￥</text>
										<text class="more2-item1-a3">14.99</text>
										<text class="more2-item1-a4">￥26</text>
									</view>
								</view>
								<view class="more2-item1-a">
									<image src="../../static/images/a2.png" mode="aspectFit"></image>
									<text class="more2-item1-a1">招牌肌肉腿饭</text>
									<view class="">
										<text class="more2-item1-a2">￥</text>
										<text class="more2-item1-a3">14.99</text>
										<text class="more2-item1-a4">￥26</text>
									</view>
								</view>
								<view class="more2-item1-a">
									<image src="../../static/images/a2.png" mode="aspectFit"></image>
									<text class="more2-item1-a1">招牌肌肉腿饭</text>
									<view class="">
										<text class="more2-item1-a2">￥</text>
										<text class="more2-item1-a3">14.99</text>
										<text class="more2-item1-a4">￥26</text>
									</view>
								</view>
								<view class="more2-item1-a">
									<image src="../../static/images/a2.png" mode="aspectFit"></image>
									<text class="more2-item1-a1">招牌肌肉腿饭</text>
									<view class="">
										<text class="more2-item1-a2">￥</text>
										<text class="more2-item1-a3">14.99</text>
										<text class="more2-item1-a4">￥26</text>
									</view>
								</view>
								<view class="more2-item1-a">
									<image src="../../static/images/a2.png" mode="aspectFit"></image>
									<text class="more2-item1-a1">招牌肌肉腿饭</text>
									<view class="">
										<text class="more2-item1-a2">￥</text>
										<text class="more2-item1-a3">14.99</text>
										<text class="more2-item1-a4">￥26</text>
									</view>
								</view>
								
								
								<view class="" style="width: 29px;height: 80%;background-color: #C0C0C0;border-radius: 10px;">
									<image src="../../static/images/xing.png" mode="aspectFill" style="width: 10px;height: 10px;margin-left: 10px;"></image>
									<view class="" style="width: 25px;height: 80%;text-align: center;">
										<text>更多惊喜</text>
									</view>
									
								</view>
							</view>
						</scroll-view>
					</view>
				</view>
				<view class="fjsj">
					<text>附近商家</text>
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
					
				</view>
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
				]
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
	@charset "UTF-8";

	/* 头条小程序组件内不能引入字体 */
	/* #ifdef MP-TOUTIAO */
	@font-face {
		font-family: uniicons;
		font-weight: normal;
		font-style: normal;
		src: url("~@/static/uni.ttf") format("truetype");
	}

	/* #endif */
	/* #ifndef APP-NVUE */
	page {
		display: flex;
		flex-direction: column;
		box-sizing: border-box;
		background-color: #efeff4;
		min-height: 100%;
		height: auto;
	}

	view {
		font-size: 14px;
		line-height: inherit;
	}

	.example {
		padding: 0 15px 15px;
	}

	.example-info {
		padding: 15px;
		color: #3b4144;
		background: #ffffff;
	}

	.example-body {
		/* #ifndef APP-NVUE */
		display: flex;
		/* #endif */
		flex-direction: row;
		flex-wrap: wrap;
		justify-content: center;
		padding: 0;
		font-size: 14px;
		background-color: #ffffff;
	}

	/* #endif */
	.example {
		padding: 0 15px;
	}

	.example-info {
		/* #ifndef APP-NVUE */
		display: block;
		/* #endif */
		padding: 15px;
		color: #3b4144;
		background-color: #ffffff;
		font-size: 14px;
		line-height: 20px;
	}

	.example-info-text {
		font-size: 14px;
		line-height: 20px;
		color: #3b4144;
	}

	.example-body {
		flex-direction: column;
		padding: 15px;
		background-color: #ffffff;
	}

	.word-btn-white {
		font-size: 18px;
		color: #FFFFFF;
	}

	.word-btn {
		/* #ifndef APP-NVUE */
		display: flex;
		/* #endif */
		flex-direction: row;
		align-items: center;
		justify-content: center;
		border-radius: 6px;
		height: 48px;
		margin: 15px;
		background-color: #007AFF;
	}

	.word-btn--hover {
		background-color: #4ca2ff;
	}

	.uni-nav-bar-text {
		font-size: 14px;
	}

	.city {
		/* #ifndef APP-PLUS-NVUE */
		display: flex;
		/* #endif */
		flex-direction: row;
		align-items: center;
		justify-content: flex-start;
		margin-left: 4px;
	}

	.input-view {
		/* #ifndef APP-PLUS-NVUE */
		display: flex;
		/* #endif */
		flex-direction: row;
		flex: 1;
		background-color: #f8f8f8;
		height: 30px;
		border-radius: 15px;
		padding: 0 15px;
		flex-wrap: nowrap;
		margin: 0 7px;
		line-height: 30px;
	}

	.input-uni-icon {
		line-height: 30px;
	}

	.nav-bar-input {
		height: 30px;
		line-height: 30px;
		/* #ifdef APP-PLUS-NVUE */
		width: 370rpx;
		/* #endif */
		padding: 0 5px;
		font-size: 14px;
		background-color: #f8f8f8;
	}

	.example-body {
		/* #ifndef APP-NVUE */
		display: block;
		/* #endif */
		padding: 0;
	}
	.shipin {
		color: black;
		font-size: 12px;
		background-color: #E6E6FA;
		padding: 2px 5px;
		border-radius: 7px;
	}
	.swip{
		background-color: #FFFFFF;
		border-radius: 12px;
		width: 90%;
		margin-left: 5%;
		margin-top: 6%;

	}
	.tubiao{
		width: 19%;
		height: 60px;
	}
	.tubiao image{
		width: 40px;
		height: 40px;
		margin-top: 10px;

	}
	.swiper-item{
		padding: 10px;
		display: flex;
		flex-wrap:wrap;
		justify-content: space-evenly;
		text-align: center;
	}
	.gong{
		display: flex;
		justify-content: space-between;
		background-color: #FFFFCC;
		width: 90%;
		height: 50px;
		margin: 0 auto;
		border-radius: 12px;
		margin-top: 10px;
	}
	.g-item{
		display: flex;
		width: 70%;
		align-items: center;
		height: 80%;
		margin-top: 5px;
	}
	.g-item1{
		width: 14%;
		height: 92%;
		margin:0 5px;
	}
	.g-item1 image{
		width: 100%;
		height: 100%;
	}
	.g-item2{
		width: 76%;
		height: 80%;
	}
	.g-item-c3{
		width: 30rpx;
		height: 30rpx;
		margin: 0 10rpx;
	}
	.g-item-c3 image{
		width: 100%;
		height: 100%;
		margin-bottom: 10rpx;
	}
	.g-item-c4{
		font-size: 11px;
		color: #FF0033;
	}
	.g-item-c5{
		font-size: 10px;
		color: #555555;
		line-height: 5rpx;
	}
	.g-item3{
		width: 20%;
		height: 60%;
		margin-top: 10px;
		margin-right: 5px;
	}
	.g-item3 button{
		width: 54px;
		height: 28px;
		font-size: 12px;
		text-align: center;
		line-height: 30px;
		background-color: #E63F00;
		padding: 0;
		color: #FFFFFF;
		line-height: 28px;
		font-weight: 550;
		margin-top: 1px;
	}
	.swiper-item{
		width: 100%;
		height: 100%;
		padding: 0;
	}
	.swiper-item image{
		width: 100%;
		height: 100%;
		border-radius: 20rpx;
	}
	.banner{
		width: 90%;
		height: 166rpx;
		margin: 0 auto;
		margin-top: 20rpx;
		border-radius: 20rpx;
	}
	.middles{
		width: 90%;
		/* height: 230px; */
		height: auto;
		margin: 0 auto;
		margin-top: 20rpx;
		background-color: #FFFFFF;
		border-radius: 20rpx;
		display: flex;
		flex-direction: column;
		justify-content: space-between;
	}
	.midd-item1{
		width: 94%;
		/* height: 30%; */
		height: 161rpx;
		margin: 0 auto;
		display: flex;
		padding: 10px 0;
		justify-content: space-between;
		
	}
	.midd-item1-b1{
		font-size: 18px;
		font-weight: 700;
	}
	.midd-item1-a3 text{
		font-size: 12px;
		margin: 6rpx 0 0 16rpx;
		width: 122rpx;
	}
	.midd-item1-c1{
		width: 130rpx;
	}
	.midd-item1-c1 text{
		border: #FF7744 1px solid;
		border-radius: 5px;
		color: #FF7744;
		font-size: 24rpx;
		
	}
	.midd-item2{
		width: 94%;
		height: 66rpx;
		margin-left: 3%;
		display: flex;
		
	}
	.midd-item2 view{
		height: 47rpx;
		width: auto;
		margin-right: 5px;
		border-radius: 3px;
		border: #FFCCCC 1px solid;
		background-color: #FDF5E6;
	}
	.midd-item2 view text{
		font-size: 26rpx;
		color: #FF4500;
	}
	.midd-item3{
		width: 94%;
		margin: 0 auto;
		height: 272rpx;
		display: flex;
		justify-content: space-between;
	}
	.midd-item3-a1{
		width: 30%;
		height: 100%;
		
	}
	.midd-item3-a1 text{
		font-size: 26rpx;
		font-weight: 700;
	}
	.midd-item3-a1 view{
		display: flex;
	}
	.midd-item3-a1 image{
		width: 100%;
		height: 57%;
		border-radius: 16rpx;
	}
	.midd-item3-a1 view image{
		width: 20px;
		height: 20px
	}
	.midd-item3-a1 view text{
		display: block;
		margin-bottom: 5px;
	}
	.midd-item1-a1{
		width: 27%;
		height: 129rpx;
	}
	.midd-item1-a1 image{
		width: 100%;
		height: 100%;
		border-radius: 20rpx;
	}
	.midd-item1-a2{
		width: 68%;
		height: 100%;
		padding-left: 10px;
	}
	.midd-item1-a3{
		width: 18%;
		height: 100%;
		display: flex;
	}
	.midd-item1-a3 image{
		width: 22px;
		height: 22px;
	}
	.midd-item1-b2{
		margin-top: 4px;
		display: flex;
	}
	.midd-item1-c2{
		width: 12px;
		height: 12px;
	}
	.midd-item1-c2 image{
		width: 100%;
		height: 100%;
		margin: 0 2px 0 10px;
	}
	.midd-item1-c3 text{
		margin:0 24rpx;
		font-size: 24rpx;
	}
	.midd-item1-c4 text{
		font-size: 24rpx;
	}
	.moreFour{
		width: 90%;
		background-color: #FFFFFF;
		margin: 10px auto;
		border-radius: 12px;
	}
	.more1{
		width: 94%;
		height: 82rpx;
		display: flex;
		margin: 0 auto;
	}
	.more1-item1{
		display: block;
		font-size: 43rpx;
		color: #DD524D;
		line-height: 104rpx;
		width: 164rpx;
	}
	.more1-item2{
		display: block;
		color: #999999;
		line-height: 104rpx;
		font-size: 28rpx;
		width: 165rpx;
	}
	.more1-item3{
		display: flex;
		margin-left: 229rpx;
		
	}
	.more1-item3 text{
		display: block;
		line-height: 104rpx;
		font-size: 19rpx;
		color: #999999;
		width: 38rpx;
	}
	.more1-item3 image{
		width: 19px;
		height: 22px;
		margin-top: 30rpx;
	}
	.more2{
		margin-left:1%;
		height: 260rpx;
	}
	.more2-item1{
		display: -webkit-box;
	}
	.more2-item1-a{
		width: 35%;
	    /* margin-right: 20rpx; */
	}
	.more2-item1-a image{
		width: 100%;
		height:75px ;
		border-radius: 12px;
	}
	.more2-item1-a1{
		font-weight: 750;
		margin-left: 14rpx;
		font-size: 33rpx;
	}
	.more2-item1-a2{
		font-size: 24rpx;
		color: red;
		margin-left: 10rpx;
	}
	.more2-item1-a3{
		font-weight: 700;
		color: red;
		font-size: 32rpx;
	}
	.more2-item1-a4{
		text-decoration:line-through;
		color: #999999;
		font-size: 22rpx;
	}
	.fjsj{
		width: 90%;
		height: 50rpx;
		margin: 10rpx auto;
	}
	.fjsj text{
		font-size: 42rpx;
		font-weight: 700;
	}
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
