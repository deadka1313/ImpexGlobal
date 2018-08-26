<template>
	<div class="wrapper">
		<Header/>
		<Breadcrumbs/>
		<div class="content mb-40">
			<nuxt/>
		</div>
		<div class="mb-40">
			<Banner/>
		</div>
		<Footer/>
	</div>
</template>

<script>
import Header from '~/components/Header.vue'
import Breadcrumbs from '~/components/Breadcrumbs.vue'
import Footer from '~/components/Footer.vue'
import Banner from '~/components/Banner.vue'
export default {
	components: {
		Header,
		Breadcrumbs,
		Footer,
		Banner
	}
}
</script>

<style lang="sass">
	#__nuxt, #__layout, #__main-wrapper
		height: 100%
</style>
