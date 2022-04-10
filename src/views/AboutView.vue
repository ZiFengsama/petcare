<template>

	<div class="common-layout">
		<el-container>
			<div class="boxs box1"></div>
			<div class="boxs box2"></div>
			<div class="boxs box3"></div>
			<div class="boxs box4"></div>
			<div class="boxs box5"></div>
			<div class="boxs box6"></div>
			<div class="boxs box7"></div>
			<div class="boxs box8"></div>
			<div class="boxs box9"></div>
			<el-main>
				<el-row :gutter="20">
					<el-col :span="6">
						<div class="grid-content left1" />
						<div class="grid-content left2" />
					</el-col>
					<el-col :span="12">
						<div class="grid-content main" />
					</el-col>
					<el-col :span="6">
						<div class="grid-content right1" />
						<div class="grid-content right2" />
					</el-col>
				</el-row>
			</el-main>
			<el-footer>
				<el-row :gutter="20">
					<el-col :span="6">
						<div class="grid-content button" />
					</el-col>
					<el-col :span="6">
						<div class="grid-content button" />
					</el-col>
					<el-col :span="6">
						<div class="grid-content button" />
					</el-col>
					<el-col :span="6">
						<div class="grid-content button" />
					</el-col>
				</el-row>
			</el-footer>
		</el-container>
	</div>
</template>

<style>
	html{
		background-image: url(../../one.png);
	}
	.boxs {
		position: absolute;
		width: 150px;
		height: 40px;
		background-color: #4d48e5;
	}

	.box1 {
		top: 160px;
		left: 100px;
		z-index: 1;
	}

	.box2 {
		top: 313px;
		left: 100px;
		z-index: 1;
	}

	.box3 {
		width: 300px;
		top: 160px;
		left: 530px;
		z-index: 1;
	}

	.box4 {
		top: 160px;
		left: 1110px;
		z-index: 1;
	}

	.box5 {
		top: 311px;
		left: 1110px;
		z-index: 1;
	}

	.box6 {
		top: 488px;
		left: 105px;
		z-index: 1;
	}

	.box7 {
		top: 488px;
		left: 440px;
		z-index: 1;
	}

	.box8 {
		top: 488px;
		left: 775px;
		z-index: 1;
	}

	.box9 {
		top: 488px;
		left: 1110px;
		z-index: 1;
	}

	.el-row {
		margin-bottom: 20px;
	}

	.el-row:last-child {
		margin-bottom: 0;
	}

	.el-col {
		border-radius: 4px;
	}

	.left1 {
		border-style: solid;
		border-color: #0000FF #0000FF #0000FF #0000FF;
		width: 300px;
		height: 150px;
	}

	.left2 {
		border-style: solid;
		border-color: #0000FF;
		width: 300px;
		height: 150px;
		/* background: #99a9bf; */
	}

	.right1 {
		border-style: solid;
		border-color: #0000FF #0000FF #0000FF #0000FF;
		width: 300px;
		height: 150px;
		/* background: #99a9bf; */
	}

	.right2 {
		border-style: solid;
		border-color: #0000FF;
		width: 300px;
		height: 150px;
		/* background: #99a9bf; */
	}

	.main {
		border-style: solid;
		border-color: #0000FF;
		width: 640px;
		height: 300px;
		/* background: pink; */
	}

	.button {
		border-style: solid;
		border-color: #0000FF #0000FF #0000FF #0000FF;
		width: 300px;
		height: 150px;
		/* background: #d3dce6; */
	}

	.bg-purple-light {
		background: #e5e9f2;
	}

	.grid-content {
		/* border-radius: 4px; */
		min-height: 36px;
	}

	.row-bg {
		padding: 10px 0;
		background-color: #f9fafc;
	}
</style>
