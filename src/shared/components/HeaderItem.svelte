<script>
	export let icon = 'star';
	export function clickevent() {}
</script>

<button on:click={clickevent}>
	<div class="material-icons">{icon}</div>
	<span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span>
	<slot />
</button>

<style>
	button {
		cursor: pointer;
		background: transparent;
		border: none;
		display: inline-block;
		color: #fff;
		font-size: 1.17em;
		padding: 0;
		padding-left: 10px;
		padding-right: 10px;
		margin: 0;
		position: absolute;
		top: 0;
		height: 2rem;
	}

	button:hover {
		background: #ffffff50;
	}

	div {
		display: inline-block;
		position: absolute;
		top: 0.1rem;
	}
</style>
