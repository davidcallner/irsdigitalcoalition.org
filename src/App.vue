<template>
    <div id="app">
        
        <Nav/>
        <router-view/>
		<div class="bg-deep-teal footer">
       	 	<Nav class="text-white"/>
		</div>
        
    </div>
</template>

<script>
    import Nav from '@/components/Nav.vue'

    export default {
      name: 'app',
      components: {
        Nav
      }
    }
</script>

<style lang="less">
    
</style>
