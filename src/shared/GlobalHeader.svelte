<script>
	// import Button from './components/Button.svelte';
	import HeaderItem from './components/HeaderItem.svelte';
</script>

<div class="header">
	<a href="/">SrsVnture</a>
	<div class="spacer" />
	<HeaderItem icon="star">Leaderboard</HeaderItem>
	<HeaderItem icon="face">Charts</HeaderItem>
	<!-- <div class="rightside">
		<Button action={() => (document.location.href = 'signin')}>Login</Button>
	</div> -->
</div>

<style>
	a {
		margin-top: 0.4rem;
		margin-left: 0.5rem;
		display: inline-block;
		font-size: 1.17em;
		text-decoration: none;
		color: #fff;
	}

	.header {
		background: #353535;
		position: fixed;
		top: 0;
		left: 0;
		width: 100%;
		height: 2rem;
	}

	.rightside {
		display: inline-block;
		position: absolute;
		right: 10px;
	}

	.spacer {
		display: inline-block;
		width: 40px;
	}
</style>
