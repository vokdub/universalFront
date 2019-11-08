<template>
<!-- TODO
ДОБАВИТЬ АЛЬТЫ КО ВСЕМ КАРТИНКАМ
РАЗБИТЬ ФАЙЛ НА КОМПОНЕНТЫ -->
<main class="container">
	<banner></banner>
	<categoriesTile></categoriesTile>
	<ourClients></ourClients>
	<div class="reviews">
		
	</div>

</main>
</template>

<script>	
	import banner from '~/components/mainBanner.vue'
	import categoriesTile from '~/components/categoriesTile.vue'
	import ourClients from '~/components/ourClients.vue'

	export default {
		components: {
			categoriesTile, 
			banner,
			ourClients			
		}
	}
</script>

<style></style>