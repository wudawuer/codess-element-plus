## tp
#### Form 表单组件 TimePicker
element-plus <el-time-picker>
```
<el-time-picker v-model="$1" size="${2|normal,medium,small,mini|}" arrow-control
	:picker-options="{
		selectableRange: '${3:18:30:00} - ${4:20:30:00}'
	}"
	placeholder="${5:任意时间点}">
</el-time-picker>
${6}
```