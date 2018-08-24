<template>
	<div class="container">
		<div class="header">
			<nuxt-link to="/">
				<Logo/>
			</nuxt-link>
		</div>
	</div>
</template>

<script>
import Logo from '~/components/Logo.vue'
export default {
	components: {
		Logo
	}
}
</script>
