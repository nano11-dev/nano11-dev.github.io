<script>
	import {Button, TextBlock} from "fluent-svelte"
	import "fluent-svelte/theme.css";
</script>


<section>
	<div>
		<TextBlock variant="display">
			Nano11
		</TextBlock>
		<TextBlock variant="subtitle">
			The best Windows 11 superlite build
		</TextBlock>
		<br>
		<div style="display:inline"> 
			<Button variant="accent" href="https://archive.org/details/nano11-23h2-v1-rp">Get Nano11 (23H2)</Button> <Button href="#descriptions">See more</Button>
		</div>
	</div>
</section>
	
<style>
	section {
		height: 100vh;
		color: white;
		width: 100%;
		text-align: center;
		background-size: cover;
		background-image: url("https://static.wixstatic.com/media/e0c5a3_2e5f17970de4417aaf7dbc1ca802a8a9~mv2.png/v1/fill/w_1850,h_891,al_c,q_90,usm_0.66_1.00_0.01,enc_auto/e0c5a3_2e5f17970de4417aaf7dbc1ca802a8a9~mv2.png");
	}
	div {
		display: grid;
		backdrop-filter: blur(15px);
		align-items: center;
		justify-items: center;
		align-content: center;
		justify-content: center;
		height: 250px;
		vertical-align: middle;
		height: 100%;
		color: white;
		width: 100%;
	}
</style>

