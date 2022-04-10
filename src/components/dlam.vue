<template>
	<div class="centerbox">
		<div class="dlam-head">
			<div class="dlam-face">
				<div class="left-eye eyes">
					<div class="left-e e">
					</div>
				</div>
				<div class="right-eye eyes">
					<div class="right-e e">
					</div>
				</div>
				<div class="nose">
				</div>
			</div>
			哆啦A梦
		</div>
		<div class="dlam-body">
		身体	
			<div class="dlam-body-box">
				口袋
			</div>
		</div>
		<div class="lefth hand">
			左手
		</div>
		<div class="righth hand">
			右手
		</div>
		
	</div>
</template>

<script>
</script>

<style>
	.centerbox{   
		position: relative;
		width: 350px;
		height: 413px;
		margin: 0 auto;
	}
	.centerbox .dlam-head{  /* 头 */
		position: relative;
		width: 300px;
		height: 300px;
		background-color: rgb(15,144,247);
		border-radius: 50%;
	}
	.centerbox .dlam-face{  /* 脸 */
		
		position: absolute;
		bottom: 0;
		left: 25px;
		width: 250px;
		height: 250px;
		border-radius: 50%;
		background-color: #FFFFFF;
	}
	.centerbox .dlam-face .nose{  /* 鼻子 */
		position: absolute;
		top: 20px;
		left: 120px;
		width: 10px;
		height: 10px;
		background-color: red;
		border-radius: 50%;
		box-shadow: 10px 10px 50px #FFFFFF;
	}
	.centerbox .dlam-face .eyes{  /* 眼睛 */
		position: relative;
		top: -20px;
		display: inline-block;
		width: 54px;
		height: 58px;
		border-radius: 50%;
		background-color: #FFFFFF;
		border:1px solid #000000;
	}
	.centerbox .dlam-face .eyes .e{  /* 眼球 */
		width: 20px;
		height: 20px;
		border-radius: 10px;
		background-color: #000000;
	}
	.centerbox .dlam-face .left-eye{  /* 左眼 */
		position: relative;
	}
	.centerbox .dlam-face .left-eye .left-e{ /* 左眼球 */
		position: absolute;
		top: 24px;
		right: 2px;
	}
	.centerbox .dlam-face .right-eye{  /* 右眼 */
		position: relative;
	}
	.centerbox .dlam-face .right-eye .right-e{ /* 右眼球 */
		position: absolute;
		top: 24px;
		left: 2px;
	}
	.centerbox .dlam-body{  /* 身体 */
		
		width: 130px;
		height: 170px;
		background-color: green;
	}
	.dlam-body-box{
		width: 100px;
		height: 80px;
		background-color: #FFFFFF;
	}
</style>
