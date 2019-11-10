<template>
	<div class="container flex">
		<asideComponent></asideComponent>
		<main class="hasAside">
			<breadcrumbs></breadcrumbs>
			<filterElem></filterElem>
			<goodsTile></goodsTile>
			<showMoreBtn></showMoreBtn>
			<information></information>
		</main>
	</div>
</template>

<script>
	import asideComponent from '~/components/asideComponent.vue'
	import breadcrumbs from '~/components/breadcrumbs.vue'
	import filterElem from '~/components/filterElem.vue'
	import goodsTile from '~/components/goodsTile.vue'
	import showMoreBtn from '~/components/showMoreBtn.vue'
	import information from '~/components/information.vue'

	export default {
		components: {
			asideComponent,
			breadcrumbs,
			filterElem,
			goodsTile,
			showMoreBtn,
			information
		}
	}
</script>

<style></style>