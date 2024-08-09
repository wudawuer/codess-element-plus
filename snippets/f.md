## f
#### filter-vue-结构代码
filter-vue-结构代码
```
<template>
<div class='filter-box'>
<div class='left-box'>
<el-input placeholder='请输入授权名称' v-model='filter.name' class='common-input' @input='query' clearable suffix-icon='el-icon-search' />
</div>
<div class='right-box'>
 <el-button type='primary'>新建授权申请</el-button>
</div>
 </div>
</template>
	
<script lang='ts'>
import { defineComponent, reactive } from 'vue'
	
export default defineComponent({
name: 'filter-box',
emits: ['query'],
setup(props, _) {
const filter = reactive({
  name: ''
})
  const query = () => {
 _.emit('query', filter)
}
  return {
  filter,
  query
 }
}
})
</script>
	
<style lang='stylus' scoped>
.filter-box
  display flex
  height 32px
  justify-content space-between
  margin-bottom 16px
</style>
```