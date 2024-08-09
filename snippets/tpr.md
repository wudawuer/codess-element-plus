## tpr
#### Form 表单组件 TimePicker Range
element-plus <el-time-picker is-range>
```
<el-time-picker v-model="$1" size="${2|normal,medium,small,mini|}" arrow-control
	is-range range-separator="${3:-}" start-placeholder="$4" end-placeholder="$5"
	:picker-options="{
		selectableRange: '${6:18:30:00} - ${7:20:30:00}'
	}">
</el-time-picker>
${8}
```