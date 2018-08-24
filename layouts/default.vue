<template>
	<div>
		<Header/>
		<Breadcrumbs/>
		<nuxt/>
		<Footer/>
	</div>
</template>

<script>
import Header from '~/components/Header.vue'
import Breadcrumbs from '~/components/Breadcrumbs.vue'
import Footer from '~/components/Footer.vue'
export default {
	components: {
		Header,
		Breadcrumbs,
		Footer
	}
}
</script>

<style lang="sass">
	#__nuxt, #__layout, #__main-wrapper
		height: 100%
</style>
