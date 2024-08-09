## ti
#### Others: Collapse Timeline
element-plus <el-timeline> with <el-timeline-item>
```
<el-timeline :reverse="$1">
	<el-timeline-item v-for="${2:item} in ${3:items}"
		:key="${2:item}.${4:id}"
		:timestamp="${2:item}.${5:timestamp}"
		placement="${6|top,bottom|}"
		type="${7|primary,success,warning,danger,info|}"
		size="${8|normal,large|}">
		${9:<!-- content -->}
	</el-timeline-item>
</el-timeline>
${10}
```