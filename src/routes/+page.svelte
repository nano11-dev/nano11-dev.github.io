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
		background-image: url("https://static.wixstatic.com/media/e0c5a3_2e5f17970de4417aaf7dbc1ca802a8a9~mv2.png/v1/fill/w_1850,h_891,al_c,q_90,usm_0.66_1.00_0.01,enc_auto/e0c5a3_2e5f17970de4417aaf7dbc1ca802a8a9~mv2.png");
	}
	

	
	div {
		backdrop-filter: blur(15px);
		background-size: cover;
		height: 100vh;
		scroll-behavior: smooth;
	}

</style>