## epdi
#### Others: Dialog
element-plus <el-dialog>
```
<el-dialog
	title="$1"
	v-model="$2"
	width="${3:30%}"
	:before-close="$4">
	<span>$5</span>
	<template #footer>
	<span>
		<el-button @click="$2 = false">Cancel</el-button>
		<el-button type="primary" @click="$6">OK</el-button>
	</span>
	</template>
</el-dialog>
${7}
```