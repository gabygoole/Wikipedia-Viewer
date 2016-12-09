### 示意图
![img](https://github.com/gabygoole/Wikipedia-Viewer/blob/master/diagram/diagram.png)

### 借助
1.Jquery <br>
2.从Wikipedia API返回的[JSON对象](https://en.wikipedia.org/w/api.php?callback=jQuery31009384725822128013_1481292630404&action=query&format=jsonfm&prop=extracts&generator=search&exsentences=1&exlimit=10&exintro=1&gsrsearch=gaby) <br>
3.JSONP 跨域请求 <br>

### 缺陷
1.keyCode被deprecated后，不知如何回车呈现结果。第二版将借助[Jquery插件](http://stackoverflow.com/questions/1960240/jquery-ajax-submit-form
)进一步完善<br>
2.鼠标必须移到中间点才能将字体显示为白色
