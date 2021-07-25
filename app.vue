<template> 
<div id="app">
		<h1>My Todo App!</h1>
		<dog dog="woof"/>
	</div>
</template>

<script>
import dog from './components/dog.vue';

export default {
  components: {
    dog
  }
}
</script>