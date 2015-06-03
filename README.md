# jquery.voteStar.js
### 一个简单的评分插件

#####[Example](http://jmjweb.github.io/jquery.voteStar.js/voteStar.html)


### 安装：

###### step1:
```html
<link rel="stylesheet" href="dist/voteStar.css">
```

###### step2:
```html
<script src="path/to/jquery-1.9.1.min.js"></script>
<script src="path/to/jquery.voteStar.js"></script>
```


###### step3: 
```javascript
$(function(){
	$('.event_star').voteStar({
		callback: function(starObj, starNum){
			alert(starNum)
		}
	})		
})
```

### 选项：
***moveStar: 鼠标move时点亮星星***
```javascript
default: false
options: boolean (true / false)
```

***starLength: 星星数量***
```javascript
default: 5
options: number
```

***precise: 精确点亮星星***
```javascript
default: false
options: boolean (true / false)
```

***star_animate: 点亮时缓慢动画***
```javascript
default: true
options: boolean (true / false)
```
***callback: 点亮后，执行什么操作? 带参数当前点击对象和分数***
```javascript
default: null
options: function(starObj, starNum){}
```




