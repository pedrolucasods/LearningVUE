<template>
	<PrimeiroComponente/>
  <p>O dado de app é: {{ testando }}</p>
  <LifeCycle/>
</template>

<script>
  import PrimeiroComponente from './components/PrimeiroComponente.vue'
  import LifeCycle from './components/LifeCycle.vue'

	export default {
		name: "#App",
    components:{
      PrimeiroComponente,
      LifeCycle
    },
    data(){
      return{
        testando:"Testando"
      }
    }
	}
</script>
