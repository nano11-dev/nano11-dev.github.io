<script>
  import Nano11Description from './Nano11Description.svelte';
  export const prerender = true;
  export const handleHtppError = 'warn';
  import Nano11Header from './Nano11Header.svelte';

	import {Button, TextBlock} from "fluent-svelte"
	import "fluent-svelte/theme.css";
</script>

<svelte:head>
	<title>Nano11</title>
	<meta name="description" content="Nano11: the best windows 11 superlite" />
</svelte:head>
<section>
	<div>	
		<Nano11Header/>
	</div>
	<Nano11Description></Nano11Description>
</section>
	
<style>
	:global(body) {
		margin: 0;
		height: 100%;
		background: #010101;
	}

	section {
		height: 100vh;
		color: white;
		width: 100%;
		text-align: center;
		background-size: cover;
		background-image: url("https://xpower7125.signed.host/BIkoa.jpg");
	}
	

	
	div {
		backdrop-filter: blur(15px);
		background-size: cover;
		height: 100vh;
		scroll-behavior: smooth;
	}

</style>
