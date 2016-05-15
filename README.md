# according
一个可以折叠的手风琴jquery组件
##案例
案例地址: http://zengqinglin.github.io/according/index.html
##用法
###step1
引用jquey
```
  <script src="js/jquery-1.9.1.min.js"></script>
```
###step2
引用js
```
  <script src="js/jquery.according.js"></script>
```
###step3
  html结构
```
 <div class="acc" id="acc">
			<h3>header</h3>
			<div class="content">wo 是内容</div>
			<h3>header2</h3>
			<div class="content">wo 是内容2</div>
			<h3 id="loadbtn">header3</h3>
			<div class="content">wo 是内容3</div>
	</div>
```
###step4
启动according
```
  $("#acc").according({"start":0});
```
