<!doctype html>
<html>
<head>
<meta charset="utf-8">
</html>
<style>
*{
	padding: 0;
	margin: 0;
}
body{ background-color: #ffdedd;}
li{
	list-style-type: none;
}
.clear{
	clear: both;
}
header{
	width: 1200px;
	height: 100px;
	margin-top: 10px;
	border-bottom: solid 5px #ffffff;
}
#logo{
	margin: 0 0px 0 10px;
	float: left;
}
#top{
	float: right;
	margin: 30px 20px 0 0;
}
nav{
	width: 1200px;
	height: 70px;
	margin-top: 10px;
}
nav li{
	float: left;
	margin: 0px 20px;
}
section{
	float: left;
	margin: 10px 10px 20px 10px;
}
aside{
	float: left;
	margin-left: 20px;
	margin-top: 10px;
}
aside li{
	margin-bottom: 44px;
}
footer{
	width: 1200px;
	border-top:solid 1px #cccccc;
	margin-top: 20px;
}
#address{
	float: left;
	margin: 30px 0 0 20px;
}
#cuatomer{
	float: left;
	margin: 30px 0 0 300px;
}
#page{/*페이지 수평맞추기, 가운데정렬*/
	width: 1400px;
	margin: auto;
	//border: solid 1px red;
}
/*스타일뒤에 헤드닫기*/
</style></head>
<body>
	<div id='page'>
	<header>
	<div id=logo>
		<img src='happy/logo.jpg'>
	</div>
	<div id=top>
		로그인 ㅣ  개요 ㅣ 경영이념 ㅣ 기업소개
	</div>
	</header>
	<div class=clear></div><!-- float  속성해제-->
	<nav>
		<ul>
			<li><img src='happy/menu02.jpg'></li>
			<li><img src='happy/menu03.jpg'></li>
			<li><img src='happy/menu04.jpg'></li>
			<li><img src='happy/menu05.jpg'></li>
		</ul>
	</nav>
	<div class=clear></div><!-- float 속성해제-->
	<section>
		<img src="happy/m.jpg" width='800'>
	</section>
	<aside>
		<ul>
			<li><img src=happy/banner001.png></li>
			<li><img src=happy/banner02.png></li>
		</ul>
	</aside>
	<div class=clear></div><!-- float 속성해제-->
	<footer>
		<div id='address'>
			<img src=happy/address.jpg>
		</div>
		<div id='cuatomer'>
		</div>
	</footer>
</body>
 </html>
