## epcolla
#### Others: Collapse
element-plus <el-collapse> with <el-collapse-item>
```
<el-collapse v-model="${1:activeNames}" :accordion="${2:false}" @change="$3">
	<el-collapse-item v-for="${4:item} in ${5:items}"
		:key="${4:item}.${6:id}"
		:title="${4:item}.${7:title}"
		:name="${4:item}.${6:id}">
		${8:<!-- content -->}
	</el-collapse-item>
</el-collapse>
${9}
```