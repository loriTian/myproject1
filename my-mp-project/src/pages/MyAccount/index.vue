<template>
	<div>
		<div>
			
			
		</div>
		<div>
			<i-grid>
					<i-grid-item>
						<i-grid-icon>
							<image src="../../static/tabs/wodexunjia_.png" />
						</i-grid-icon>
							<i-grid-label>我的询价</i-grid-label>
					</i-grid-item>
					<i-grid-item>
						<i-grid-icon>
							<image src="../../static/tabs/wodefabiao.png" />
						</i-grid-icon>
							<i-grid-label>我的发表</i-grid-label>
					</i-grid-item>
					<i-grid-item>
						<i-grid-icon>
							<image src="../../static/tabs/wodeshoucang.png" />
						</i-grid-icon>
							<i-grid-label>我的收藏</i-grid-label>
					</i-grid-item>
					<i-grid-item>
						<i-grid-icon>
							<image src="../../static/tabs/liulanjilu.png" />
						</i-grid-icon>
							<i-grid-label>浏览记录</i-grid-label>
					</i-grid-item>
			</i-grid>
		</div>
		<div>
			<i-cell-group>
				<i-cell title="消息中心" is-link></i-cell>
				<i-cell title="拼购订单" is-link></i-cell>
				<i-cell title="意见反馈" is-link></i-cell>
				<i-cell title="合作联系" is-link></i-cell>
				<i-cell title="关于我们" is-link></i-cell>
				<i-cell title="跳转到首页" is-link url="/pages/dashboard/index"></i-cell>		
			</i-cell-group>
		</div>
	</div>
</template>

<script>


export default {
  data () {
    return {
      site: 'Hello miniprograme',
      
    }
  },
}
</script>

<style>
</style>
