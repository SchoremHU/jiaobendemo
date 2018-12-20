		             +-----------------------+
      		       |	操作说明	 
+----------------+-----------------------+------------------------------+
|export PATH="jiaoben的绝对路径:$PATH" //临时使用
|
|1、demo-bash.sh 								  			
|	jiaoben的绝对路径/demo-bash.sh xxx  //xxx为创建文件夹名
|
|2、demo-node.sh							
|	node jiaoben的绝对路径/demo-node.sh xxx  //xxx为创建文件夹名		
|									
|3、demo-node.js									
|	node jiaoben的绝对路径/demo-node.js xxx  //xxx为创建文件夹名		
|									
|demo.sh xxx 可在当前目录下生成目录 xxx，demo.sh yyy 可生成目录 yyy	
|									
|如果要生成的目录已经存在，则直接退出					
+-----------------------------------------------------------------------+


	      +--------+
	      |最终效果
+-------+--------+--------------+
|生成的目录结构如下：		
| ├── css			
| │   └── style.css		
| ├── index.html		
| └── js			
|     └── main.js		
|				
|index.html 的内容为		
| <!DOCTYPE>			
| <title>Hello</title>		
| <h1>Hi</h1>			
|				
|css/style.css 的内容为		
| h1{color: red;}		
|				
|js/main.js 的内容为		
| var string = "Hello World"	
| alert(string)			
+-------------------------------+
