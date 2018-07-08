<template>
	<div class="header">
		<div class="header-left">
			<div class="iconfont back-icon">&#xe624;</div>
		</div>
		<div class="header-input">
			<span class="iconfont">&#xe632;</span>
			输入城市/景点/游玩主题</div>
		<div class="header-right">城市
		<span class="iconfont arrow-icon">&#xe600;</span>
		</div>
	</div>
</template>
<script>
export default{
	name:'HomeHeader'
}
</script>

<style lang="stylus" scoped>
/*scoped 关键字代表只对这个文件的元素有效stalus 的写法
    1 可以改变css的写法
    2 可以使用变量
 * */
@import '~styles/varibles.styl'
.header 
  height:.86rem
  display:flex
  background:$bgColor
  color:#fff
  line-height:.86rem
  .header-left
   width:.64rem
   float:left
    .back-icon
     text-align:center
  .header-input
   flex:1
   height:.64rem 
   line-height:.64rem 
   margin-top:.12rem
   margin-left:.2rem
   background:#fff
   color:#ccc
   border-radius:.1rem
   padding-left:.2rem
  .header-right
   width:1.24rem
   float:right
   text-align:center
   .arrow-icon
    margin-left:-.04rem
    font-size:.24rem
</style>