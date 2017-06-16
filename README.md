# jquery.voteStar.js
### 一个简单的评分插件

#### [Example](http://wuuashen.github.io/jquery.voteStar.js/voteStar.html)


### 安装：

###### step1:
```html
<link rel="stylesheet" href="dist/voteStar.css">
```

###### step2:
```html
<span class="event_star star_in" data-starnum="3.5"><i></i></span>
```
> class有3个可选值star_in/star_big/star_small  
> data-starnum可设置默认的分数

###### step3:
```html
<script src="path/to/jquery-1.9.1.min.js"></script>
<script src="path/to/jquery.voteStar.js"></script>
```


###### step4: 
```javascript
$(function(){
	$('.event_star').voteStar({'选项名称': 选项值})		
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

***starAnimate: 点亮时缓慢动画***
```javascript
default: true
options: boolean (true / false)
```
***callback: 点亮后，执行什么操作? 带参数当前点击对象和分数***
```javascript
default: null
options: function(starObj, starNum){}
```




