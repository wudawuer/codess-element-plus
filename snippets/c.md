## c
#### 内容区域-ts-结构代码
内容区域-ts-结构代码
```
<template>
 <div class='content-box'>
  <el-table :data='table.tableData' style='width: 100%' size='medium'>
 <el-table-column type='index' label='序号' width='50'> </el-table-column>
 <el-table-column prop='date' label='日期' width='180'> </el-table-column>
  </el-table>
 <common-pagination :total='table.total' @_handleCurrentChange='handleCurrentChange' ref='pagination' />
 </div>
</template>
	
<script lang='ts'>
import { defineComponent, onMounted, ref, toRefs } from 'vue'
import { usePagination } from '@/hooks/usePagination'
	
export default defineComponent({
setup() {
const { table, getList, handleCurrentChange } = usePagination()
const doms = {
 pagination: ref<any>(null)
 }
 const _filterSearch = (param: any) => {
 table.query = param
 doms.pagination.value.changeCurpage()
  }
 onMounted(() => {
 getList((param: any) => {
  return Promise.resolve({
 data: [
  {
  date: '2016-05-02' + param.page,
  name: '王小虎' + param.size,
  address: '上海市普陀区金沙江路 1518 弄'
 }
 ],
 total: 121
 })
  })
  })
  return { table, getList, handleCurrentChange, ...toRefs(doms), _filterSearch }
 }
 })
 </script>
	
 <style lang='stylus' scoped></style>
```