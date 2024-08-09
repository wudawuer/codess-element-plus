## epcon
#### Basic: Container el-container
element-plus <el-container>
```
<el-container :direction="${1:vertical}">
	<el-header height="$2">
		${3:<!-- Header content -->}
	</el-header>
	<el-container :direction="${4:horizontal}">
		<el-aside width="${5:200px}">
			${6:<!-- Aside content -->}
		</el-aside>
		<el-container :direction="${7:vertical}">
			<el-main height="$8">
				${9:<!-- Main content -->}
			</el-main>
			<el-footer height="$10">
				${11:<!-- Footer content -->}
			</el-footer>
		</el-container>
	</el-container>
</el-container>
${12}
```