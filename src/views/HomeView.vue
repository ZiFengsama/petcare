<template>
	<el-row class="one" :gutter="20">
		<el-col :span="8">
			<div style="height: 50%;" class="bk lones">
				<div class="all title">
					AAAAAAAA
				</div>
				<Duo></Duo>
				<div class="lborderboxt borderbox1"></div>
				<div class="lborderboxt borderbox2"></div>
				<div class="lborderboxt borderbox3"></div>
				<div class="lborderboxt borderbox4"></div>
				<div class="lborderboxl borderbox5"></div>
				<div class="lborderboxl borderbox6"></div>
				<div class="lborderboxl borderbox7"></div>
				<div class="lborderboxl borderbox8"></div>
			</div>
			<div style="height: 50%;" class="bk lonex">
				<div class="all title">
					BBBBBBBBB
				</div>
				<div class="lborderboxt borderbox1"></div>
				<div class="lborderboxt borderbox2"></div>
				<div class="lborderboxt borderbox3"></div>
				<div class="lborderboxt borderbox4"></div>
				<div class="lborderboxl borderbox5"></div>
				<div class="lborderboxl borderbox6"></div>
				<div class="lborderboxl borderbox7"></div>
				<div class="lborderboxl borderbox8"></div>
			</div>
		</el-col>
		
		<el-col :span="8">
			<div style="height: 100%;" class="bk zhong">
				<div class="all title">
					XXXXXXXXXX
				</div>
				<Dlam></Dlam>
				<div class="lborderboxt borderbox1"></div>
				<div class="lborderboxt borderbox2"></div>
				<div class="lborderboxt borderbox3"></div>
				<div class="lborderboxt borderbox4"></div>
				<div class="lborderboxl borderbox5"></div>
				<div class="lborderboxl borderbox6"></div>
				<div class="lborderboxl borderbox7"></div>
				<div class="lborderboxl borderbox8"></div>
			</div>
		</el-col>
		<el-col :span="8">
			<div style="height: 50%;" class="bk rones">
				<div class="all title">
					DDDDDDDDD
				</div>
				<div class="lborderboxt borderbox1"></div>
				<div class="lborderboxt borderbox2"></div>
				<div class="lborderboxt borderbox3"></div>
				<div class="lborderboxt borderbox4"></div>
				<div class="lborderboxl borderbox5"></div>
				<div class="lborderboxl borderbox6"></div>
				<div class="lborderboxl borderbox7"></div>
				<div class="lborderboxl borderbox8"></div>
			</div>
			<div style="height: 50%;" class="bk ronex">
				<div class="all title">
					EEEEEEEEEE
				</div>
				<div class="lborderboxt borderbox1"></div>
				<div class="lborderboxt borderbox2"></div>
				<div class="lborderboxt borderbox3"></div>
				<div class="lborderboxt borderbox4"></div>
				<div class="lborderboxl borderbox5"></div>
				<div class="lborderboxl borderbox6"></div>
				<div class="lborderboxl borderbox7"></div>
				<div class="lborderboxl borderbox8"></div>
			</div>
		</el-col>
	</el-row>
	<el-row class="two">
		<el-col :span="6">
			<div style="height: 100%; " class="xm">
				<div class="all botitle">
				</div>
				<div class="lborderboxt borderbox1"></div>
				<div class="lborderboxt borderbox2"></div>
				<div class="lborderboxt borderbox3"></div>
				<div class="lborderboxt borderbox4"></div>
				<div class="lborderboxl borderbox5"></div>
				<div class="lborderboxl borderbox6"></div>
				<div class="lborderboxl borderbox7"></div>
				<div class="lborderboxl borderbox8"></div>
			</div>
		</el-col>
		<el-col :span="6">
			<div style="height: 100%;" class="xm">
				<div class="all botitle">
				</div>
				<div class="lborderboxt borderbox1"></div>
				<div class="lborderboxt borderbox2"></div>
				<div class="lborderboxt borderbox3"></div>
				<div class="lborderboxt borderbox4"></div>
				<div class="lborderboxl borderbox5"></div>
				<div class="lborderboxl borderbox6"></div>
				<div class="lborderboxl borderbox7"></div>
				<div class="lborderboxl borderbox8"></div>
			</div>
		</el-col>
		<el-col :span="6">
			<div style="height: 100%;" class="xm">
				<div class="all botitle">
				</div>
				<div class="lborderboxt borderbox1"></div>
				<div class="lborderboxt borderbox2"></div>
				<div class="lborderboxt borderbox3"></div>
				<div class="lborderboxt borderbox4"></div>
				<div class="lborderboxl borderbox5"></div>
				<div class="lborderboxl borderbox6"></div>
				<div class="lborderboxl borderbox7"></div>
				<div class="lborderboxl borderbox8"></div>
			</div>
		</el-col>
		<el-col :span="6">
			<div style="height: 100%;" class="xm">
				<div class="all botitle">
				</div>
				<div class="lborderboxt borderbox1"></div>
				<div class="lborderboxt borderbox2"></div>
				<div class="lborderboxt borderbox3"></div>
				<div class="lborderboxt borderbox4"></div>
				<div class="lborderboxl borderbox5"></div>
				<div class="lborderboxl borderbox6"></div>
				<div class="lborderboxl borderbox7"></div>
				<div class="lborderboxl borderbox8"></div>
			</div>
		</el-col>
	</el-row>
	<router-view />
</template>
<script type="text/javascript">
	// import AboutVue from "./views/AboutView.vue"
	import Duo from "../components/duolie.vue"
	import Dlam from "../components/dlam.vue"
	export default {
		components:{
			Duo,
			Dlam
		}
	}
</script>

<style>
	.two .el-col {
		border: 1px solid #000FFF;
	}

	.bk {
		position: relative;
		border: 1px solid #000FFF;
	}
	.xm{
		position: relative;
	}
	.one {
		height: 70%;
	}

	.two {
		position: relative;
		height: 20%;
		margin-top: 30px;
	}

	#app {
		/* display: flex; */
		height: 100%;

		font-family: Avenir, Helvetica, Arial, sans-serif;
		-webkit-font-smoothing: antialiased;
		-moz-osx-font-smoothing: grayscale;
		text-align: center;
		color: #2c3e50;
	}
	.all{
		position: absolute;
		width: 170px;
		height: 30px;
		background-color: #00ffff;
		/* padding-top: 10px; */
		text-align: center;
		line-height: 30px;
		color: #FFFFFF;
		font-size: 20px;
	}
	.title{
		top: -15px;
		left: 30%;
	}
	.botitle{
		top: -15px;
		left: 25%;
	}
	.lborderboxt {
		position: absolute;
		width: 30px;
		height: 5px;
		background-color: #000FFF;
		z-index: 1;
	}

	.lborderboxl {
		position: absolute;
		width: 5px;
		height: 30px;
		background-color: #000FFF;
		z-index: 1;
	}

	.borderbox1 {

		top: -5px;
		left: 0;
	}

	.borderbox2 {
		top: -5px;
		right: 0px;
	}

	.borderbox3 {
		bottom: -5px;
		left: 0;
	}

	.borderbox4 {
		bottom: -5px;
		right: 0px;
	}

	.borderbox5 {
		top: -5px;
		right: -5px;
	}

	.borderbox6 {
		top: -5px;
		left: -5px;
	}

	.borderbox7 {
		bottom: -5px;
		left: -5px;
	}

	.borderbox8 {
		bottom: -5px;
		right: -5px;
	}

	html {
		height: 100%;
		background-color: #FFFFFF;
		background-size: 100% 100%;
		/* background: url(./assets/tyloo.jpg) fixed; */
	}

	body {
		height: 100%;
	}

	nav {
		padding: 30px;
		color: aqua;
	}

	nav a {
		font-weight: bold;
		color: #2c3e50;
	}

	nav a.router-link-exact-active {
		color: #42b983;
	}
</style>
