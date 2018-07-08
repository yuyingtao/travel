<template>
	<div>
	    <HomeHeader></HomeHeader>	
	</div>
</template>

<script>
//	引入组件
import HomeHeader from './components/Header'
export default{
	name:'Home',
	components:{
		HomeHeader // es6 的写法
	}
}
</script>

<style>
</style>