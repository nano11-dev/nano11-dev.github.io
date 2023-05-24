<script>
      import {Button, TextBlock} from "fluent-svelte"
      import "fluent-svelte/theme.css";
  </script>

<nav>
	<Button href="/" variant="hyperlink">Home</Button>
	<Button href="/blog" variant="hyperlink">Blog</Button>
	<Button href="https://mega.nz/file/FfNCUKTQ#PpB2hWrMDwDv-dsVHaQe-geAbVlc0DZ9ezDc3V5qnIU " variant="hyperlink">Download latest version</Button>
</nav>

<slot />

<style>
    nav {
        position: fixed;
        z-index: 99;
        background: none;
        
    }
</style>