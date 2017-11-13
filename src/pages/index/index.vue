<template>
	<el-container class="index_page">
		<el-header class="index_page_header">
			<el-header class="index_header_top">
				<el-row :type="flex" :justify="center">
					<el-col :span="12">您好，杭州贝乐文化传播有限公司欢迎您！</el-col>
					<el-col :span="12">
						<el-button type="text">登录</el-button>
						<el-button type="text">注册</el-button>
					</el-col>
				</el-row>
				<el-row :type="flex" :justify="center">
					<el-col :span="12">贝乐文化</el-col>
					<el-col :span="12">
						
					</el-col>
				</el-row>
			</el-header>
		</el-header>
	</el-container>
</template>

<script>
	export default {
		name: 'index',
		data () {
			return {}
		}
	}
</script>

<style lang="stylus" rel="stylesheet/stylus">
	@import './index.styl'
</style>