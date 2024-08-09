## i
#### 路由界面-ts-结构代码
路由界面-ts-结构代码
```
<template>
<div>
 <view-title title='授权申请记录（原授权管理平台）'></view-title>
 <FilterBox @query='_query' />
 <Content ref='content' />
</div>
</template>
	
<script lang='ts'>
import { defineComponent, ref, toRefs } from 'vue'
import FilterBox from './components/FilterBox.vue'
import Content from './components/Content.vue'
	
export default defineComponent({
name: 'before',
components: { FilterBox, Content },
setup() {
 const doms = {
content: ref<any>(null)
}
const _query = (param: any) => {
doms.content.value._filterSearch(param)
}
 return {
 ...toRefs(doms),
 _query
}
}
})
</script>
	
<style lang='stylus' scoped></style>
	
```