## dr
#### Navigation: Dropdown
element-plus <el-dropdown> with <el-dropdown-item>
```
<el-dropdown trigger="${1:click}" size="${2|default,medium,small,mini|}" split-button type="${3|primary,success,warning,danger,info,text|}" @command="$4">
	${5:title}
	<template #dropdown>
	<el-dropdown-menu>
		<el-dropdown-item v-for="${6:item} in ${7:items}"
			:key="${6:item}.${8:key}" :command="${6:item}.${9:command}">
			{{${6:item}.${10:title}}}
		</el-dropdown-item>
	</el-dropdown-menu>
	</el-dropdown>
</template>
${11}
```