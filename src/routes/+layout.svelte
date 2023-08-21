<script>
      import {Button, TextBlock} from "fluent-svelte"
      import "fluent-svelte/theme.css";
  </script>

<nav>
	<Button href="/" variant="hyperlink">Home</Button>
	<Button href="/blog" variant="hyperlink">Blog</Button>
	<Button href="https://archive.org/details/nano11-v4-open-beta " variant="hyperlink">Download latest version</Button>
</nav>

<slot />

<style>
    nav {
        position: fixed;
        z-index: 99;
        background: none;
        
    }
</style>
