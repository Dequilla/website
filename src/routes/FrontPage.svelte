<script>
	import Navigation from "../components/Navigation.svelte";
	import ScrollIcon from "../components/ScrollIcon.svelte";
</script>

<div>
	<section id="section-one">
		<Navigation></Navigation>
		<img id="forest" src="images/nature-test-white.png"/>
		<h1 class="title">Edwin Wallin</h1>
		<h2 class="sub-title">Nature and wildlife</h2>
		<div id="scroll"><ScrollIcon></ScrollIcon></div>
	</section>
	<section id="section-two">
		<p>Second section further down!</p>
	</section>
</div>


<style>
	div {
		
	}

	section {
		width: 100%;
		display: inline-block;
		text-align: center;
	}

	#section-one {
		background-image: url("/images/07062019-IMG_9410.jpg");
		background-position: center;
		background-size: cover;
		min-height: 100vh;
	}

	#section-two {
		color: #333;
		font-size: 3em;
	}

	#forest {
		width: 14vw;
		margin-top: 10vh;
		margin-bottom: -10vh;
		display: inline-block;
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

	#scroll {
		margin-top: 45vh;
	}
</style>