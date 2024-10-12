<script>
  export const prerender = true;
  import Nano11Header from './Nano11Header.svelte';
	import "fluent-svelte/theme.css";
</script>

<svelte:head>
	<title>Nano11</title>
    	<meta content="Nano11" property="og:title" />
    	<meta content="The best Windows 11 superlite" property="og:description" />
    	<meta content="https://nano11-dev.github.io" property="og:url" />
    	<meta content="https://raw.githubusercontent.com/nano11-dev/nano11-dev.github.io/refs/heads/main/static/favicon.png" property="og:image" />
    	<meta content="#0E86D4" data-react-helmet="true" name="theme-color" />
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
