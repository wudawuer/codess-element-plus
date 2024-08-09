## tsr
#### Form 表单组件 Time Select Range
element-plus <el-time-select> range
```
<el-time-select v-model="$1" size="${2|normal,medium,small,mini|}" placeholder="$3"
	:picker-options="{
		start: '${4}',
		step: '${5:00:30}',
		end: '${6}',
	}">
</el-time-select>
<el-time-select v-model="$7" size="${2|normal,medium,small,mini|}" placeholder="$8"
	:picker-options="{
		start: '${4}',
		step: '${5:00:30}',
		end: '${6}',
		minTime: $1
	}">
</el-time-select>
${9}
```