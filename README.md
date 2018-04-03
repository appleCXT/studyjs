## studyjs
html文件

```<!DOCTYPE html>
  <html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Document</title>
</head>
<body>
	dddddd
	<script type="text/javascript">
		debugger;
		var a = [];
    	for(var i = 0; i < 10; i++) {
       	  var c = i;
      	  a[i] = function() {
            console.log( c ); //每次执行都是讲function赋值到数组中
        };
    }
    a[6]();//9 //调用a数组中的第六个内容，里面放着的是一个函数，这时i已经是9了，所以打印了9<br/>
	</script>
</body>
</html>```
test.name 最终会按照test[name]去执行 用.的时候 后面跟属性名 用【】后面是一个变量或者一个属性名的字符串。
