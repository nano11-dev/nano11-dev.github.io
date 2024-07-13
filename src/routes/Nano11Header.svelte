<script>
	import Card from '$lib/Card.svelte';
	import { Button, IconButton, TextBlock } from 'fluent-svelte';
	import TopSpeed from "@fluentui/svg-icons/icons/top_speed_20_regular.svg?raw";
	import Box from "@fluentui/svg-icons/icons/box_20_regular.svg?raw";
	import User from "@fluentui/svg-icons/icons/person_20_regular.svg?raw";
	import 'fluent-svelte/theme.css';
</script>

<section class="z-50">
	<div class="h-[100vh] w-[100vw] flex text-white content-center items-center justify-center flex-col z-50 gap-4">
		<TextBlock variant="display" class="z-50">Nano11</TextBlock>
		<TextBlock variant="subtitle" class="z-50">The best Windows 11 superlite build</TextBlock>
		<div class="flex flex-wrap gap-2 justify-center">
			<Card class="w-80">
				<svelte:fragment slot="header" >
					<div class="flex gap-2 fill-white justify-between">
						<TextBlock variant="subtitle" class="">Better performance</TextBlock>
						{@html TopSpeed}
					</div>
					</svelte:fragment>
						<TextBlock variant="body">By removing useless features packed in stock Windows 11, Nano11 can give more performances, even on low-end PCs.</TextBlock>
			</Card>
			<Card class="w-80">
				<svelte:fragment slot="header" >
					<div class="flex gap-2 fill-white justify-between">
						<TextBlock variant="subtitle" class="">More space for what you need</TextBlock>
						{@html Box}
					</div>
					</svelte:fragment>
						<TextBlock variant="body">Nano11 only takes up 10GB of disk space, so you will have more space for what you really need.</TextBlock>
			</Card>
			<Card class="w-80">
				<svelte:fragment slot="header" >
					<div class="flex gap-2 fill-white justify-between">
						<TextBlock variant="subtitle" class="">Better user experience</TextBlock>
						{@html User}
					</div>
					</svelte:fragment>
						<TextBlock variant="body">Nano11 has a few minor tweaks that make the UX better.</TextBlock>
			</Card>
		</div>
		<div id="buttons" class="flex gap-2 flex-wrap justify-center">
			<Button variant="accent" href="https://archive.org/details/nano11-24h2">Download Nano11 24H2</Button>
			<Button variant="accent" href="https://archive.org/details/nano11-24h2-copilot">Download Nano11 24H2 Copilot Edition</Button>
			<Button variant="standard" href="https://mega.nz/folder/8StwhBAQ#_ZBA8U-t5tf_XYna_C-2LA">Get Nano11 Extras</Button>
			<Button variant="standard" href="https://github.com/nano11-dev/Nano11Toolkit">Toolkit Repo</Button>
			<Button variant="standard" href="https://github.com/nano11-dev/nano11-post-setup">Post-Setup Repo</Button>
			<Button variant="standard" href="https://discord.gg/u6tHeZJe">More in our Discord</Button>
		</div>
	</div>
</section>

<style>
	div {
		z-index: 4;
	}
</style>
