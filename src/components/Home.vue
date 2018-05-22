<template>
  <div class="super_container">
		<top-navigation/>
	</div>
</template>
<script>
import TopNavigation from './TopNavigation.vue'

export default {
	data(){
		return{
			message:'hello, world'
		}
	},components:{
		TopNavigation
	}
}
</script>
