<script>
	import Navigation from "./components/Navigation.svelte";
</script>

<main>
	<Navigation></Navigation>
	<section>
		<img id="forest" src="images/nature-test-white.png"/>
		<h1 class="title">Edwin Wallin</h1>
		<h2 class="sub-title">Nature and wildlife</h2>
	</section>
</main>


<style>
	main {
		background-image: url("/images/07062019-IMG_9410.jpg");
		background-position: center;
		background-size: cover;
		min-height: 100vh;
	}

	section {
		width: 100vw;
		display: inline-block;
		text-align: center;
	}

	#forest {
		width: 14vw;
		margin-top: 10vh;
		margin-bottom: -10vh;
	}

	section h1 {
		margin-top: 10vh;
		font-size: 4em;
		text-transform: uppercase;
	}

	section h2 {
		margin-top: 0;
		font-size: 1.6em;
		text-transform: uppercase;
	}
</style>