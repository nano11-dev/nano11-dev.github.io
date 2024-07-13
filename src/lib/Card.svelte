<script lang="ts">
	let className = "";
	export { className as class };

	let element: HTMLDivElement;

	export const getElement = () => element;
</script>

<div
	class="hero-card {className}"
	on:click
	on:blur
	on:focus
	on:dblclick
	on:contextmenu
	on:mousedown
	on:mouseup
	on:mouseover
	on:mouseout
	on:mouseenter
	on:mouseleave
	on:keypress
	on:keydown
	on:keyup
	bind:this={element}
>
	<header>
		<slot name="header" />
	</header>
	<slot />
</div>

<style lang="scss">
.hero-card {
	box-sizing: border-box;
	position: relative;
	padding: 12px;
	backdrop-filter: blur(60px) saturate(125%);
	border-radius: 8px;
	background-color: hsla(0, 0%, 100%, 5.12%);
	border: 1px solid hsla(0, 0%, 0%, 10%);
	background-clip: padding-box;
	box-shadow: 0px 2px 4px hsla(0, 0%, 0%, .13);
	transition: .25s cubic-bezier(0, 0, 0, 1);
	&:hover {
		box-shadow: 0px 8px 16px hsla(0, 0%, 0%, .14);
		transform: translateY(-4px);
	}
	header {
		margin-bottom: 12px;
	}
}
</style>