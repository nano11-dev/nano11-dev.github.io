<script>
  export const prerender = true;
  import Nano11Header from './Nano11Header.svelte';
	import "fluent-svelte/theme.css";
</script>

<svelte:head>
	<title>Nano11</title>
	<meta name="description" content="Nano11: the best windows 11 superlite" />
</svelte:head>
<section>
		<Nano11Header/>
</section>
	
<style>
	section {
		z-index: 9999;
		background-color: #00000065;
		backdrop-filter: blur(75px);
	}
</style>
