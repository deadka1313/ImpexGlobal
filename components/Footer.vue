<template>
	<div class="container ">
		<div class="footer flex-row">
			<div class="flex-row">
				<div class="footer-logo">
					<LogoGrey/>
				</div>
				<ul class="footer-menu flex-row">
					<li>
						<nuxt-link to="/" class="footer-menu_item">User agreement</nuxt-link>
					</li>
					<li>
						<nuxt-link to="/" class="footer-menu_item">ImpexGlobal</nuxt-link>
					</li>
					<li>
						<nuxt-link to="/" class="footer-menu_item">Our services</nuxt-link>
					</li>
					<li>
						<nuxt-link to="/" class="footer-menu_item">Contacts</nuxt-link>
					</li>
				</ul>
			</div>
			<div class="flex-row">
				<span class="mr-10">Разработка сайта —  Студия Артема Городецкого</span> <img src="~assets/img/logo-studio.png" alt=".ag">
			</div>
		</div>
	</div>
</template>

<script>
import LogoGrey from '~/components/LogoGrey.vue'
export default {
	components: {
		LogoGrey
	}
}
</script>
