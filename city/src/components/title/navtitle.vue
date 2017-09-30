<template>
	<div class="nav-title">
		<div class="title-address">
			<span>深圳</span>
		</div>
		<div class="title-list">
			<ul>
				<li class="active">招募中</li>
				<li>举办中</li>
				<li>已举办</li>
			</ul>
		</div>
	</div>
</template>
<style lang="less">
	@import "../../../static/less/index";

	.nav-title{
		width: 100%;
		.h(44);
		background-color: #fff;
		box-shadow: 1px 1px 3px #eee;
		position: relative;
		.title-address{
			position: absolute;
			.left(10);
			.top(14);
			span{
				.fs(15);
				color: #252324;
			}
		}
		.title-list{
			.w(342/2);
			.h(52/2);
			position: absolute;
			left: 0;
			top: 0;
			right: 0;
			bottom: 0;
			margin: auto;
			ul{
				display: flex;
				justify-content: space-around;
				align-items: center;
				height: 100%;
				border: 1px solid #252324;
				border-radius: 20px;
				li{
					height: 100%;
					.lh(52/2);
					flex: 1;
					text-align: center;
					border-right: 1px solid #252324;
					color: #252324;
				}
				li:first-child{
					border-radius: 10px 0 0 10px;
				}
				li:last-child{
					border-right: none;
					border-radius: 0 10px 10px 0;
				}
				.active{
					background-color: #252324;
					color: #f6d87f;
				}
			}
		}
	}
</style>
<script type="text/javascript">
	export default {
		data() {
			return {}
		},
		computed: {},
		props: {},
		methods: {},
		components: {}
	}
</script>
