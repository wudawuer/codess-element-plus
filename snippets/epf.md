## epf
#### Form 表单组件 Form
element-plus <el-form>
```
<el-form :model="${1:form}" ref="${2:form}" :rules="${3:rules}" label-width="80px" :inline="${4|false,true|}" size="${5|normal,medium,small,mini|}">
	<el-form-item label="$6">
		<el-input v-model="${1:form}.${7}"></el-input>
	</el-form-item>
	<el-form-item>
		<el-button type="primary" @click="onSubmit">${8:立即创建}</el-button>
		<el-button>${9:取消}</el-button>
	</el-form-item>
</el-form>
${10}
```