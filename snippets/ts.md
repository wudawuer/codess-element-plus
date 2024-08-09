## ts
#### Form 表单组件 Time Select
element-plus <el-time-select>
```
<el-time-select v-model="$1" size="${2|normal,medium,small,mini|}" placeholder="$3"
	:picker-options="{
		start: '${4}',
		step: '${5:00:30}',
		end: '${6}',
	}"
	change="${7}">
</el-time-select>
${8}
```