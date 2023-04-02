<!DOCTYPE html>
<html>
<head>
	<title>Interactive I in Eye</title>
	<style>
		.eye {
			position: relative;
			display: inline-block;
			width: 200px;
			height: 200px;
			background-color: #777000;
			border-radius: 50%;
			overflow: hidden;
			box-shadow: 0px 0px 5px #888888;
		}
		.pupil {
			position: absolute;
			top: 50%;
			left: 50%;
			width: 60px;
			height: 60px;
			background-color: #020320;
			border-radius: 50%;
			transform: translate(-50%, -50%);
			transition: all 0.3s ease-in-out;
		}
		.eye:hover .pupil {
			width: 80px;
			height: 80px;
		}
		.eye .pupil i {
			position: absolute;
			top: 50%;
			left: 50%;
			transform: translate(-50%, -50%);
			font-size: 50px;
			color: white;
		}
	</style>
</head>
<body>
	<div class="eye">
		<div class="pupil">
			<i>I</i>
		</div>
	</div>
</body>
</html>
# hnsdemo
<a href="https://reg.uncensorednames.com/tld/hnsdemo">hnsdemo</a>
