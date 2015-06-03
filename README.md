# jquery.voteStar.js
### 一个评分插件

#####[Example](http://jmjweb.github.io/jquery.voteStar.js/voteStar.html)


### 安装

###### step1:
```html
<link rel="stylesheet" href="dist/voteStar.css">
```

###### step2:
```html
<script src="path/to/jquery-1.9.1.min.js"></script>
<script src="path/to/jquery.voteStar.js"></script>
```


###### step2: 
```javascript
$(function(){
	$('.event_star').voteStar({
		callback: function(starObj, starNum){
			alert(starNum)
		}
	})		
})
```

