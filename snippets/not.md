## not
#### Notice: Notification with type
element-plus $notify.type
```
\$app.\$notify.${1|info,success,warning,error|}({
	title: '${2:title}',
	message: '${3:message}',
	duration: '${4|4500, 0|}',
	position: '${5|top-right,top-left,bottom-right,bottom-left|}',
	showClose: '${6:true}',
});
${7}
```