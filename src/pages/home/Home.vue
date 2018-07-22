<template>
	<div>
	    <home-header></home-header>
	    <Swiper></Swiper>
	    <home-icons></home-icons>
	    <home-recommend></home-recommend>
	</div>
</template>

<script>
//	引入组件
import HomeHeader from './components/Header'
import Swiper from './components/Swiper'
import HomeIcons from './components/icons'
import HomeRecommend from './components/Recommend'

export default{
	name:'Home',
	components:{
		HomeHeader,
		HomeIcons,
		Swiper,
		HomeRecommend// es6 的写法
	}
}
</script>

<style>
</style>