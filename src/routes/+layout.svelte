<script>
      import {Button, TextBlock} from "fluent-svelte"
      import "fluent-svelte/theme.css";
  </script>

<nav>
	<Button href="/" variant="hyperlink">Home</Button>
	<Button href="/blog" variant="hyperlink">Blog</Button>
	<Button href="https://drive.google.com/file/d/1rzUBwvj9qNr07MjzF8z1F6oJLOCn8UGF/view?usp=drive_link" variant="hyperlink">Download latest version</Button>
</nav>

<slot />

<style>
    nav {
        position: fixed;
        z-index: 99;
        background: none;
        
    }
</style>
