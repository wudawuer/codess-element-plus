## epp
#### 数据展示: Pagination
element-plus <el-pagination>
```
<el-pagination
	@size-change="${1:sizeChange}"
	@current-change="${2:currentChange}"
	v-model:currentPage="${3:currentPage}"
	:page-sizes="${4:[20, 40, 80, 100]}"
	:page-size="${5:pageSize}"
	layout="total, sizes, prev, pager, next, jumper"
	:total="${6:totalNum}" background>
	:pager-count="${7:7}">
</el-pagination>
${8}
```