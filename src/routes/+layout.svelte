<script>
      import {Button, TextBlock} from "fluent-svelte"
      import "fluent-svelte/theme.css";
      import "./styles.css"
  </script>

<iframe src="/FirstLogonAnim.html" title="First Logon Animation" />

<div>
    <slot />
</div>

<style>
    iframe {
        position: absolute;
        left:0;
        top:0;
        width: 100vw;
        height: 100vh;
    }
    :global(body) {
        overflow-x: hidden;
    }

</style>

