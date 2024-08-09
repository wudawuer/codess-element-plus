## opg
#### Form 表单组件 Select Option Group
element-plus <el-option-group>
```
<el-option-group v-for="${1:group} in ${2:options}"
	:key="${1:group}.${3:value}"
	:label="${1:group}.${4:label}">
	<el-option v-for="${5:item} in ${1:group}.${6:options}"
		:key="${5:item}.${7:value}"
		:label="${5:item}.${8:label}"
		:value="${5:item}.${9:value}">
	</el-option>
<el-option-group>
${10}
```