<template>
	<v-app>
		<v-main>
			<v-img
				src="@/assets/images/cooking.png"
				width="80px"
				class="ml-6 mr-6"
			></v-img>
		</v-main>
	</v-app>
</template>

<script>
	import HelloWorld from './components/HelloWorld.vue'

	export default {
		name: 'App',

		components: {
			HelloWorld
		},

		data: () => ({
			//
		})
	}
</script>
