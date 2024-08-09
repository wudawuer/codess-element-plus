## eptabs
#### Navigation: Tabs
element-plus <el-tabs> with <el-tab-pane>
```
<el-tabs v-model="$1" type="${2|card,border-card,normal|}" tab-position="${3|top,left,right,bottom|}" @tab-click="$4">
	<el-tab-pane v-for="${5:item} in ${6:panes}"
		:key="${5:item}.${7:key}"
		:label="${5:item}.${8:label}"
		:name="${5:item}.${7:key}">
		$9
	</el-tab-pane>
</el-tabs>
${10}
```