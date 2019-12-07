<html>
<head>
<meta charset="utf-8">
<title>只给静静一个人</title>
<style type="text/css">
*{margin: 0;padding: 0;}
body{overflow:hidden;background: url(images/bg.jpg);background-size: cover;}
.container{
	width:100%;
	height: 100%;

}
.photowall{
	position: relative;
	
	height: 100%; width: 100%;


	display: -webkit-box; /*使用CSS3的盒模型之流式布局*/
	display: -moz-box;
	display: box;

	-webkit-box-pack:center; /*定义盒模型内部元素在水平方向上居于中间位置*/
	-moz-box-pack:center;
	-o-box-pack:center;
	-ms-box-pack:center;
	box-pack:center;

	-webkit-box-align:center; /*定义盒模型内部元素在垂直方向上居于中间位置*/
	-moz-box-align:center;
	-o-box-align:center;
	-ms-box-align:center;
	box-align:center;




}

.photoview{
	position: relative;
	background-color:#f2eada;
	margin: 5px;padding:10px 10px 20px 10px;
	text-align: center;
	font-size:20px;
	box-shadow:.2em .2em .8em #130c0e; /*给照片添加阴影效果，富有立体感*/

	
}

.photoview p{
	margin-top:5px;  /*设置照片内显示文字段落的外上边距*/
}

.photo01{
	-weikit-transform-origin:right bottom; /*设置右下角为旋转基准点 */
	-moz-transform-origin:right bottom;
	-o-transform-origin:right bottom;
	-ms-transform-origin:right bottom;
	transform-origin:right bottom;

	transform:rotate(10deg); /*以右下角为基准点顺时针旋转10°*/
	-webkit-transform:rotate(10deg);
	-moz-transform:rotate(10deg);
	-o-transform:rotate(10deg);
	-ms-transform:rotate(10deg);


}
.photo02{
	-weikit-transform-origin:right bottom; /*设置右下角为旋转基准点 */
	-moz-transform-origin:right bottom;
	-o-transform-origin:right bottom;
	-ms-transform-origin:right bottom;
	transform-origin:right bottom;

	transform:rotate(-20deg); /*以右下角为基准点逆时针旋转20°*/
	-webkit-transform:rotate(-20deg);
	-moz-transform:rotate(-20deg);
	-o-transform:rotate(-20deg);
	-ms-transform:rotate(-20deg);
}

.photo03{
	-weikit-transform-origin:left top; /*设置左上角为旋转基准点 */
	-moz-transform-origin:left top;
	-o-transform-origin:left top;
	-ms-transform-origin:left top;
	transform-origin:left top;

	transform:rotate(20deg); /*以左上角为基准点顺时针旋转20°*/
	-webkit-transform:rotate(20deg);
	-moz-transform:rotate(20deg);
	-o-transform:rotate(20deg);
	-ms-transform:rotate(20deg);
}
.photo04{
	-weikit-transform-origin:left bottom; /*设置左下角为旋转基准点 */
	-moz-transform-origin:left bottom;
	-o-transform-origin:left bottom;
	-ms-transform-origin:left bottom;
	transform-origin:left bottom;

	transform:rotate(-20deg); /*以左下角为基准点逆时针旋转20°*/
	-webkit-transform:rotate(-20deg);
	-moz-transform:rotate(-20deg);
	-o-transform:rotate(-20deg);
	-ms-transform:rotate(-20deg);
}
</style>
<script>
window.onload=function(){
	var y=document.getElementById('xiu');
	y.onclick=function(){
	var x=window.prompt("接下来的两个问题只有静静知道，通过的话就能知道一件很重要的事，要过关吗？","说是或不是哦");
	if(x=="是"){
		var z=window.prompt("宝宝你给我唱的第一首歌是","四个字");
		  if(z=="云烟成雨"){
		  	alert("嗯，就是就是！");
		  	var d=window.prompt("那你送给我的最后一首歌是什么鸭","不灭的火焰，无论境地多么不利，我都要尝试和你在一起");
		  	if(d=="try"){
		  		alert("是啊！我想和你一直走下去，如果能一起到老，烟波里成灰，我也心满意足");
		  		alert("接着点下去吧！");
		  		window.location.href="https://0liuyuxiu.github.io/-1/";
		  	}
		  	else
		  		alert("P!NK");
		  }
		  else
		  	alert("是云字开头的哦！");
	}
    else
    	alert("我想你了");
	return ;
}
}
</script>
</head>
<body>	
<input id="xiu" style="width:100px;font:left; margin-left:400px; margin-top:500px; height:100px;background:red;" type="button" value="宝贝点这里"/>

<div class="container">
	<div class="photowall">
	
		<div class="photo01">
			<div class="photoview" >
				<img src=".\静静6.jpg" width="250" height="220">
				<p>你是那轻风细雨</p>
				<p></p>
			</div>
		</div>
		
		<div class="photo02">
			<div class="photoview" >
				<img src=".\静静5.jpg" width="250" height="220">
				<p>那明媚白昼</p>
				<p></p>
			</div>
		</div>
		
		<div class="photo03">
			<div class="photoview" >
				<img src=".\静静8.jpg" width="250" height="220">
				<p>我想你在每一分每一秒</p>
				<p></p>
			</div>
		</div>
		
		<div class="photo04">
			<div class="photoview" >
				<img src=".\静静4.jpg" width="250" height="220">
				<p>亲爱的</p>
				<p></p>
			</div>
		</div>
	
	</div>
</div>
<div style="text-align:center;margin:50px 0; font:normal 14px/24px 'MicroSoft YaHei';">

</div>
</body>
</html>
