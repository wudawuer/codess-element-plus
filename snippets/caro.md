## caro
#### Others: Carousel
element-plus <el-carousel> with <el-carousel-item>
```
<el-carousel height="${1:150px}" type="${2|default,card|}" direction="${3|horizontal,vertical|}"
	:initial-index="${4:0}" :autoplay="${5|true, false|}" :interval="${6:3000}" :loop="${7|true,false|}"
	trigger="${8|hover,click|}" indicator-position="${9|outside,inside,none|}" arrow="${10|hover,always,never|}">
	<el-carousel-item v-for="${11:item} in ${12:items}" :key="${11:item}.${13:key}" :label="${14}">
		${15:<!-- content -->}
	</el-carousel-item>
</el-carousel>
${16}
```