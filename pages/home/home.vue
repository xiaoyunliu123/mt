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
				<view class="moreFour" style="width: 80%;background-color: #FFFFFF;height: 147px;margin: 10px auto;
    border-radius: 12px;display: flex;flex-direction: column;justify-content: space-evenly;">
					<view class="more1" style="width: 94%;height: 20%;border: #000000 1px solid;display: flex;margin: 0 auto;">
						<text style="display: block;font-size: 20px;color: #DD524D;line-height: 29.4px;">神 价 格</text>
						<text style="display: block;margin-left: 5px;color: #999999;line-height: 29.4px;">这么买更实惠</text>
						<view class="" style="display: flex;margin-left: 32%;">
							<text style="display: block;line-height: 29.4px;font-size: 12px;color: #999999;">更多</text>
							<image src="../../static/images/more.png" mode="aspectFill" style="width: 22px;height: 22px;margin-top: 2.7px;"></image>
						</view>
					</view>
					<view class="" style="width: 94%;height: 62%;border: #007AFF 1px solid;margin: 0 auto;">
						
					</view>
				</view>
				
				<view class="special-list">
				 <scroll-view scroll-x="true" class="special-scroll">
				         <view class="special-item">
				            <image src="https://res.wx.qq.com/wxdoc/dist/assets/img/0.4cb08bb4.jpg" class="image" mode="aspectFit"></image>
				          <view class="name">啊啊啊啊啊</view>
				          <view class="price">￥456{{index}}</view>
				         </view>
						 <view class="special-item">
						    <image src="https://res.wx.qq.com/wxdoc/dist/assets/img/0.4cb08bb4.jpg" class="image" mode="aspectFit"></image>
						  <view class="name">啊啊啊啊啊</view>
						  <view class="price">￥456{{index}}</view>
						 </view>
						 <view class="special-item">
						    <image src="https://res.wx.qq.com/wxdoc/dist/assets/img/0.4cb08bb4.jpg" class="image" mode="aspectFit"></image>
						  <view class="name">啊啊啊啊啊</view>
						  <view class="price">￥456{{index}}</view>
						 </view>
						 <view class="special-item">
						    <image src="https://res.wx.qq.com/wxdoc/dist/assets/img/0.4cb08bb4.jpg" class="image" mode="aspectFit"></image>
						  <view class="name">啊啊啊啊啊</view>
						  <view class="price">￥456{{index}}</view>
						 </view>
						 <view class="special-item">
						    <image src="https://res.wx.qq.com/wxdoc/dist/assets/img/0.4cb08bb4.jpg" class="image" mode="aspectFit"></image>
						  <view class="name">啊啊啊啊啊</view>
						  <view class="price">￥456{{index}}</view>
						 </view>
				         <view class="special-item-last">
				            <view style="font-size: 36rpx">+10</view>
				            <view style="font-size:24rpx;">查看全部单品</view>
				         </view>
			   </scroll-view>
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
		width: 80%;
		margin-left: 10%;
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
		width: 80%;
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
		width: 70%;
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
		width: 80%;
		height: 166rpx;
		margin: 0 auto;
		margin-top: 20rpx;
		border-radius: 20rpx;
	}
	.middles{
		width: 80%;
		height: 230px;
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
		height: 30%;
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
		margin: 3px 0 0 8px;
	}
	.midd-item1-c1 text{
		border: #FF7744 1px solid;
		border-radius: 5px;
		color: #FF7744;
	}
	.midd-item2{
		width: 94%;
		height: 18%;
		margin-left: 3%;
		display: flex;
		
	}
	.midd-item2 view{
		height: 20px;
		width: auto;
		margin-right: 5px;
		border-radius: 3px;
		border: #FFCCCC 1px solid;
		background-color: #FDF5E6;
	}
	.midd-item2 view{
		color: #FF4500;
	}
	.midd-item3{
		width: 94%;
		margin: 0 auto;
		height: 75%;
		display: flex;
		justify-content: space-between;
	}
	.midd-item3-a1{
		width: 30%;
		height: 100%;
		
	}
	.midd-item3-a1 view{
		display: flex;
	}
	.midd-item3-a1 image{
		width: 100%;
		height: 64%;
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
		width: 16%;
		height: 100%;
	}
	.midd-item1-a1 image{
		width: 100%;
		height: 100%;
		border-radius: 20rpx;
	}
	.midd-item1-a2{
		width: 65%;
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
		margin:0 12px;
	}
	
	
	
	
	 .special-list{
	    width: 100%;
	    height: 307rpx;
	    overflow: hidden;
	    padding: 20rpx 0 0 38rpx;
	    background: #fff;
	    white-space: nowrap;
		}
	    .special-scroll{
	      height: 330rpx;width: auto;overflow:hidden;
	    }
	    .special-item{
	      height:184rpx;
	      width: 184rpx;
	      display: inline-block;
	      margin-right:40rpx;
	      background-color: #aaa;
	    }
		.image{
		  height:184rpx;
		  width: 184rpx;
		}
	    .name{
	      font-size: 20rpx;
	      color: $normalGrayFont;
	      -webkit-line-clamp:1;
	      overflow: hidden;
	      display:-weblit-box;
	      word-break: break-all;
	      text-overflow: ellipsis;
	    }
	    .price{
	      font-size:28rpx;
	    }
	    .special-item-last{
	      height:184rpx;
	      width: 184rpx;
	      border:2rpx solid #ddd;
	      border-radius:2rpx;
	      display: inline-block;
	      margin-right:40rpx;
	      text-align: center;
	      vertical-align: top;
	      padding:44rpx 0;
	    }
	  
</style>
