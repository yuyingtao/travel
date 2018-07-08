<template>
	<div class="wrraper">
	    <swiper :options="swiperOption" >
    <!-- slides -->
	    	<swiper-slide v-for="item of swiperList" :key="item.id">
	      		<img class="swiper-img" :src="item.imgUrl">
	    	</swiper-slide>
	    <!-- Optional controls -->
	    	<div class="swiper-pagination "  slot="pagination"></div>
	  	</swiper>
	</div>
	
</template>

<script>
	export default{
		name:'HomeSwiper',
		data (){
			return {
				swiperOption:{
					pagination:'.swiper-pagination',
					loop:true
				},
				swiperList:[{
					id:"0001",
					imgUrl:"http://img1.qunarzz.com/piao/fusion/1803/5c/969bfa7af00a2702.jpg_750x200_b99b8e07.jpg"
				},{
					id:"0002",
					imgUrl:"http://img1.qunarzz.com/piao/fusion/1807/66/e5a5cec881702f02.jpg_750x200_67bb5691.jpg"
				},
				]
			}
		}
	}
</script>

<style lang="stylus" scoped="">
    .wrraper
     overflow:hidden
     width:100%
     height:0
     padding-bottom:31.25%
	.swiper-img
	  width:100%
	.wrraper >>> .swiper-pagination-bullet 
	 background:#fff
</style>