## epmen
#### Navigation: NavMenu Menu
element-plus <el-menu> with <el-submenu> and <el-menu-item>
```
<el-menu mode="${1|horizontal,vertical|}" default-active="$2" @select="$3">
	<el-sub-menu v-for="(${4:submenus}, ${5:index}) in ${6:menus}"
		:index="${5:index} + 1"
		:key="${4:submenus}.${7:key}">
		<template #title>{{${4:submenus}.${8:title}}}</template>
		<el-menu-item v-for="(${9:item}, ${10:subIndex}) in ${4:submenus}.${11:menus}"
			:index="(${5:index} + 1) + '-' + (${10:subIndex} + 1)"
			:key="${9:item}.${12:key}">
				{{${9:item}.${13:title}}}
		</el-menu-item>
	</el-submenu>
</el-menu>
${14}
```