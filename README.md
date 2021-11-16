<!DOCTYPE html>
<html>
<head>
    <title></title>
<style>
.layout{
	width: 500px;
}
.layout .top{
	padding: 15px;
	background-color: lightgreen;
}
.layout .main{
	background-color: white;
}
.layout .main:after{ clear: both; display: block; content: '' }

.layout .main .left{
	float: left;
	width: 100px;
	height: 254px;
	background-color: orange;
}
.layout .main .rightt{
	float: left;
	width: 400px;
}
.layout .down{
	padding: 15px;
	background-color: #ddd;
}
</style>
<div class="layout">
	<div class="top">MY blog page
</div>
	<div class="main">
		<div class="left">Link</div>
		<div class="right"></div>
	</div>
	<div class="down">
		copyright(c)2021 hong
	</div>
  </div>
