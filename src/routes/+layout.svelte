<script>
      import {Button, TextBlock} from "fluent-svelte"
      import "fluent-svelte/theme.css";
  </script>

<nav>
	<Button href="/" variant="hyperlink">Home</Button>
	<Button href="/blog" variant="hyperlink">Blog</Button>
	<Button href="https://www.youtube.com/redirect?event=comments&redir_token=QUFFLUhqbnNSb19oM0dLblA5NFUtQzZQM2dkN3dNTkdHUXxBQ3Jtc0tsZFdQWmM2bVlheVZYUDg4R2tqN1FPSmEzMGhkbEh4SVNxUkk4S0NtUkRtM1lMd05wa3BZN3RSR2gzLVFvWnNac0lfMjBfUXBLSW1XbkJkWjc0bS1PSGplczBJbllPekVVaWtRaWc2a3JrU0FINHFobw&q=https%3A%2F%2Fdrive.google.com%2Ffile%2Fd%2F1rzUBwvj9qNr07MjzF8z1F6oJLOCn8UGF%2Fview%3Fusp%3Ddrive_link " variant="hyperlink">Download latest version</Button>
</nav>

<slot />

<style>
    nav {
        position: fixed;
        z-index: 99;
        background: none;
        
    }
</style>
