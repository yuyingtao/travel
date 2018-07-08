<template>
	<div>
	    <HomeHeader></HomeHeader>
	    <Swiper></Swiper>
	</div>
</template>

<script>
//	引入组件
import HomeHeader from './components/Header'
import Swiper from './components/Swiper'
export default{
	name:'Home',
	components:{
		HomeHeader,
		Swiper// es6 的写法
	}
}
</script>

<style>
</style>