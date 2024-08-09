## sts
#### Navigation: Steps
element-plus <el-steps> with <el-step>
```
<el-steps :active="$1" direction="${2|horizontal,vertical|}" process-status="${3|wait,process,finish,error,success|}" finish-status="${4|wait,process,finish,error,success|}">
	<el-step v-for="${5:item} in ${6:items}"
		:key="${5:item}.${7:key}"
		:title="${5:item}.${8:title}"
		:description="${5:item}.${9:description}"
		:icon="${5:item}.${10:icon}">
	</el-step>
</el-steps>
${11}
```