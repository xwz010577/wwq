<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8">
		<title></title>
		<style>
           html{
                font-size: 15px;
           }
			ul{
				list-style: none;
				margin: 0;
				padding: 0;
			}
			h1{
				font-size: 1.5rem;
				margin: 0;
			}
			h2{
				font-size: 1.2rem;
				margin: 0;
			}
           li{
                cursor: pointer;
				  color: white;
                padding-top:5px; 
                padding-bottom:5px;
           } 
			li:hover{
                background: #984dfe;
                
			}
			ul.level1{
				background: #eeeeee;
              font-size:0; 
              text-align:center;
              	padding-top: 5px;
				padding-bottom: 5px;
			
			}
			ul.level1>li{
				display: inline-block;
				width: 200px;
				background: #5CB85C;	
              font-size:1rem; 
              position:relative;
			}
			ul.level1>li:hover>ul.level2{
				display: block;
			}
			ul.level2{
				background: #5Cee5C;
				display: none;
				position: absolute;
				width:100%;
              top:100%;
              left:0;     
			}
			ul.level2>li{
				position: relative;
			}
			ul.level2>li:hover>ul.level3{
				display: block;
			}
			ul.level3{
				background: #5Cee3C;
				display: none;
				position: absolute;
				left:100%;
				width:100%;
				top:0;
			}
			ul.level3>li{
			
			
			}
			ul.level3>li>a{
				font-size: 1rem;
				text-decoration: none;
               display:block; 
			}
		</style>
	</head>
	<body>
		<ul class="level1">
			<li>
				<h1>一级菜单1</h1>
				<ul class="level2">
					<li>
						<h2>二级菜单1</h2>
						<ul class="level3">
							<li><a href="">三级菜单1</a></li>
							<li><a href="">三级菜单2</a></li>
							<li><a href="">三级菜单3</a></li>
						</ul>
					</li>
					<li>
						<h2>二级菜单2</h2>
						<ul class="level3">
							<li><a href="">三级菜单1</a></li>
							<li><a href="">三级菜单2</a></li>
							<li><a href="">三级菜单3</a></li>
						</ul>
					</li>
				</ul>

			</li>
			<li>
				<h1>一级菜单2</h1>
				<ul class="level2">
					<li>
						<h2>二级菜单1</h2>
						<ul class="level3">
							<li><a href="">三级菜单1</a></li>
							<li><a href="">三级菜单2</a></li>
							<li><a href="">三级菜单3</a></li>
						</ul>
					</li>
					<li>
						<h2>二级菜单2</h2>
						<ul class="level3">
							<li><a href="">三级菜单1</a></li>
							<li><a href="">三级菜单2</a></li>
							<li><a href="">三级菜单3</a></li>
						</ul>
					</li>
				</ul>
			</li>
			<li>
				<h1>一级菜单3</h1>
				<ul class="level2">
					<li>
						<h2>二级菜单1</h2>
						<ul class="level3">
							<li><a href="">三级菜单1</a></li>
							<li><a href="">三级菜单2</a></li>
							<li><a href="">三级菜单3</a></li>
						</ul>
					</li>
					<li>
						<h2>二级菜单2</h2>
						<ul class="level3">
							<li><a href="">三级菜单1</a></li>
							<li><a href="">三级菜单2</a></li>
							<li><a href="">三级菜单3</a></li>
						</ul>
					</li>
				</ul>
			</li>
		</ul>

	</body>
</html>
