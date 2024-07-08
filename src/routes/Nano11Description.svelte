<script>
	import Nano11Header from './Nano11Header.svelte';

	import { Button, TextBlock } from 'fluent-svelte';
	import 'fluent-svelte/theme.css';
</script>

<section id="descriptions">
	<TextBlock id="MeetNano11" variant="titleLarge">Meet Nano11</TextBlock>
	<TextBlock variant="body">
		Nano11 is a lightweight version of Windows 11 designed for those who prioritize speed and
		efficiency. With a small installation size of only 10GB, it takes up minimal space on your
		device and runs smoothly even on low-spec hardware. Despite its small size, Nano11 still
		provides essential features and functions of Windows 11, including the intuitive user interface
		and compatibility with a wide range of software and hardware. Whether you're using a laptop,
		tablet, or desktop computer, Nano11 offers a fast and reliable computing experience.
		</TextBlock
	>
	<TextBlock variant="titleLarge">Features</TextBlock>
	<div id="Features">
		<TextBlock variant="body"
			><ul>
				<li>
					<span class="bold">Better performances</span>: by removing useless features packed in
					stock Windows 11, Nano11 can give more performances, even on low-end PCs.
				</li>
				<li>
					<span class="bold">More space for what you need</span>: Nano11 only takes up 10GB of disk
					space, so you will have more space for what you really need.
				</li>
				<li>
					<span class="bold">Better user experience</span>: Nano11 has a few minor tweaks that make
					the UX better.
				</li>
			</ul>
		</TextBlock>
	</div>
	<TextBlock variant="titleLarge">Download</TextBlock>
	<br />
	<div id="buttons">
		<Button variant="accent" href="https://drive.google.com/file/d/1rzUBwvj9qNr07MjzF8z1F6oJLOCn8UGF/view?usp=drive_link"Download Nano11 24H2</Button>
		<Button variant="accent" href="https://drive.google.com/file/d/1n4f3SqcB3qWsEhLHYCCDFAHdtWIjzfEL/view"Download Nano11 24H2 Copilot Edition</Button>
		<Button variant="accent" href="https://mega.nz/folder/8StwhBAQ#_ZBA8U-t5tf_XYna_C-2LA">Get Nano11 Extras</Button>
		<Button variant="accent" href="https://github.com/XPower7125/nano11-post-setup">Post-Setup Repo</Button>
		<Button variant="accent" href="https://discord.gg/u6tHeZJe">More in our Discord</Button>
	</div>
</section>

<style>
	section {
		padding: 25%;
		padding-top: 10px;
		padding-bottom: 10px;
		text-align: center;
		color: white;
	}
	#Features {
		text-align: left;
	}
	.bold {
		font-weight: bold;
	}
	#buttons {
		margin: 5px;
	}
</style>
