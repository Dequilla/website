<script>
	import Router from 'svelte-spa-router';

	import FrontPage from "./routes/FrontPage.svelte";
	import GalleryPage from "./routes/GalleryPage.svelte";

	const routes = {
		'/': FrontPage,
		'/gallery': GalleryPage,
		'*': FrontPage
	}
</script>

<main>
	<Router {routes}/>
</main>

<style>

</style>