# I-Love-My-BlackHuHu
<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8" />
		<title>我爱我的黑乎乎</title>
		<style type="text/css">
		
			
		</style>
		<!--引入reset.css用来清除浏览器的默认样式-->
		<link rel="stylesheet" type="text/css" href="css/reset.css" />
		<!--引入自己写的123.css-->
			<link rel="stylesheet" type="text/css" href="css/123.css"/>
	</head>
	<body>
		
		<!--
			id class和文件名的命名规范：
			  -命名时尽量使用英文，如果不会的话就使用拼音，但是不要英文和拼音混用。
			命名格式：
			   -驼峰命名法：首字母小写，每个单词的开头字母大写
			   例子：aaaBbbCcc helloWorld
			   -也可以所有的字母都小写，单词之间使用-或者_连接
			  例子：aaa-bbb-ccc aaa_bbb_ccc
		-->
		<!--创建头部div header-->
		<!--header的开始-->
		<div class="header w">
			<!--创建一个无序列表-->
			<ul class="list">
					<li>
						<a href="#">HOME</a>
						<p>
							Back to home
						</p>
					</li>
					<li>
						<a href="#">PRODUCTS</a>
						<p>
						What we have for you
						</p>
					</li>
					<li>
						<a href="#">SERVICES</a>
						<p>
							Things we do
						</p>
					</li>
					<li>
						<a href="#">BLOG</a>
						<p>
							Follow our updates
						</p>
					</li>
					<li>
						<a href="#">CONTACT</a>
						<p>
							Ways to reach us
						</p>
					</li>
			</ul>
			<!--在div中创建一个logo-->
			<div class="logo">
				<a href="#" title="一个非常非常好的网站">
					<img src="img/logo.png" alt="logo图片">
				</a>
			</div>
		</div>
				
		</header>
		<!--header的结束-->
		<!--banner的开始-->
		<div class="banner w">
			<img src="img/banner/banner01.png" alt="显眼的图片"/>

<!--创建一个div，用于放置导航按钮-->
<div class="pointer">
<a href="#"></a>
<a href="#"></a>
<a href="#"></a>
<a href="#"></a>
<a href="#"></a>
<a href="#"></a>
</div>
</div>
<!--banner的结束-->
		<!--content的开始-->
		<div class="content w clearfix">
			<h1>Lorem ipsum dolor sit amet, consectetur adipisicing elit</h1>
		
		<div class="Perfect">
			<h2>Perfect Logic</h2>
			<h3>All you want your website to do.</h3>
			<!--创建一个图片的div-->
			<div class="babyPicture">
				<img src="img/pict/pict01.jpg" alt="照片" />
			</div>
			<p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo</p>
			<a class="learn" href="#">Learn More</a>
		</div>
		
		
		<div class="Complete">
			<h2 class="jt">Complete Solution</h2>
			
			<!--创建一个图片的div-->
			<div class="babyPicture02">
				<img src="img/pict/pict02.jpg" alt="照片" />
			</div>
			<p>Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciun tdolore magnam aliquam quaerat voluptatem.</p>
			<a class="learn" href="#">Learn More</a>
		</div>
		
		<div class="Uber">
			<h2>Uber Culture</h2>
			<h3>Fresh. Modern and ready for future</h3>
			<!--创建一个图片的div-->
			<div class="babyPicture03">
				<img src="img/pict/pict03.jpg" alt="照片" />
			</div>
			<p>Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem.</p>
			<a class="learn" href="#">Learn More</a>
		</div>
		</div>
		<!--content的结束-->
		<!--shadow的开始-->
		<div class="myShadow">
			<img src="img/myShadow.png" alt="myShadow" />
		</div>
		<!--shadow的结束-->
			<!--contact的开始-->
			<div class="contact w clearfix">
				<!--创建3个div-->
				<div class="Social clearfix">
					<h2 class="Social02">Social Connection</h2>
					<p>At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium</p>
					<div class="little">
						<a class="little01" href="#"><img src="img/little01.png" alt="little01" ></a>
						<a class="little02" href="#"><img src="img/little02.png" alt="little02" /></a>
						<a class="little03" href="#"><img src="img/little03.png" alt="little03" /></a>
						<a class="little04" href="#"><img src="img/yt.png" alt="little04" /></a>
						<a class="little05" href="#"><img src="img/little05.png" alt="little05" /></a>
					
					</div>
					<h2 class="Social03">Newslettle</h2>
					<p>At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium</p>
					<table>
						<input class="txt txt1" placeholder="your email adress" type="text"></input>
					</table>
					<buttom class="buttom"><a class="buttomA" href="#">Subscribe</a></buttom>
					
				</div>
				<div class="Contact01 clearfix">
					<!--创建一个标题-->
					<h2 class="contact02">Contact</h2>
					<!--创建一个表单-->
					<form action="#">
						<!--在文本框和文本域中可以通过placeholder来指定提示文字（即水印）
							但是这个属性在ie8及以下的浏览器中是不支持的，需要使用javascript来解决
						-->
						<input class="txt" placeholder="your name" type="text" />
						<input class="txt" placeholder="email address" type="text" />
						<textarea class="area" placeholder="message" value="message"></textarea>
					</form>
					<buttom class="buttom"><a class="buttomA" href="#">Send it</a></buttom>
				</div>
				<div class="News clearfix">
					<h2 class="News02">News Updates</h2>
					
				    <div class="firefox">
				    	<div class="firefox01">
				    	<img src="img/firefox.png" alt="这是一个火狐图片"/>
				        </div>
				        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
				    </div>
				    <div class="violet">
				    	<div class="violet01">
				    	<img src="img/violet.png" alt="这是一个紫色球球图片"/>
				        </div>
				        <p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam.</p>
				    </div>
				    <div class="picture">
				    	<div class="picture01">
				    	<img src="img/picture.png" alt="这是一个风景图片"/>
				    	</div>
				   
				    <p>At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium.</p>
				    </div>
					<buttom class="buttom"><a class="buttomA" href="#">Visit Our Blog</a></buttom>
				
				</div>
			</div>
			<!--contact的结束-->
		<!--foot的开始-->
		<div class="foot">
			<div class="foot02">Copyright 2010. Studio VIVROCKS. All Rights Reserved.</div>
			
			<div class="foot01">Site Powered by Wordpress. Design and Developed by VIVROCKS.

             <a class="foota" href="#">Home</a> | <a class="foota" href="#">About</a> | <a class="foota" href="#">Products</a> | <a class="foota" href="#">Services</a> | <a class="foota" href="#">Contact</a><br />

             <a class="foota" href="#">Privacy Policy</a> | <a class="foota" href="#">Terms of use</a></div>
            <!--cursor:用来设置鼠标指针的样式，一般为point-->
		</div>
		<!--foot的结束-->
		<!--处理ie6图片的透明问题-->
	  <!--[if IE6]>
	  	<script type="text/javascript" src="js/DD_belatedPNG_0.0.8a-min.js"></script>
	  	<script type="text/javascript">DD_belatedPNG.fix("*");</script>
	  <![endif]-->
	</body>
</html>
