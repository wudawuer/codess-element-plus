## cg
#### Form 表单组件 Checkbox Group
element-plus <el-checkbox-group> with <el-checkbox>
```
<el-checkbox-group v-model="$1" @change="${2}">
	<el-checkbox v-for="${3:item} in ${4:items}" :key="${3:item}.${5:key}" :label="${3:item}.${6:label}">
		{{${3:item}.${7:label}}}
	</el-checkbox>
</el-checkbox-group>
${8}
```