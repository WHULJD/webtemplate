reset.css
	用来进行浏览器重置，每个页面都必须包含的css文件。
	
jQuery.js
	jQuery压缩后的库文件，需要用到的，请放在</body>的上面。
	
1.png
	避免img空src问题（如果img的src属性为""的话，那么浏览器会向服务器的当前目录发一次请求；
如果有10个这种img的话，就会请求十次，无意义且浪费资源；将之都设置成1.png的话，就会将十次请
求降为1次）。

template.html
	前端html模板，其中jQuery的引用如果不需要，请手动删掉。