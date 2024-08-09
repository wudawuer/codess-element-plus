## u
#### Form 表单组件 Upload
element-plus <el-upload>
```
<el-upload
	action="$1"
	ref="${2:upload}"
	:on-remove="$3"
	:auto-upload="false"
	multiple
	:limit="${4:5}"
	:on-exceed="$5"
	:file-list="$6">
	 <template #trigger><el-button size="small" type="primary">${7:select file}</el-button></template>
	<el-button style="margin-left: 10px;" size="small" type="success" @click="$8">${9:upload to server}</el-button>
	<template #tip><div class="el-upload__tip">${10:jpg/png files with a size less than 500kb}</div></template>
</el-upload>
${11}
```