## t
#### 数据展示: Table
element-plus <el-table>
```
<el-table :data="$1" border stripe>
	<el-table-column type="index" width="50" />
	<el-table-column v-for="${2:col} in ${3:columns}"
		:prop="${2:col}.${4:id}"
		:key="${2:col}.${4:id}"
		:label="${2:col}.${5:label}"
		:width="${2:col}.${6:width}">
	</el-table-column>
</el-table>
${7}
```