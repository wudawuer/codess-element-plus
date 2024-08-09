## epmecon
#### Notice: Messagebox Confirm
element-plus $confirm
```
\$app.\$confirm('${1:确认删除？}', '${2:提示}', {
	confirmButtonText: '${3:确认}',
	cancelButtonText: '${4:取消}',
	type: '${5|success,info,warning,erro|}',
}).then(() => {
	del(id).then(() => {
	\$app.\$message.success('删除成功！')
	getList()
})
}).catch(() => {
	${7}
});
${8}
```