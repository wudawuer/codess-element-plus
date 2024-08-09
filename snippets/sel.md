## sel
#### Form 表单组件 Select
element-plus <el-select>
```
<el-select v-model="$1" value-key="$2" placeholder="$3" clearable filterable @change="$4">
	<el-option v-for="${5:item} in ${6:options}"
		:key="${5:item}.${7:value}"
		:label="${5:item}.${8:label}"
		:value="${5:item}.${9:value}">
	</el-option>
</el-select>
${10}
```