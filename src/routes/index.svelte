<script>
	import { onMount } from 'svelte';

	onMount(()=>{
		// safe for browser only code - e.g. fetch
		console.log('only runs in the browser');
	});
	
</script>
<style>
	h1, p {
		text-align: center;
		margin: 0 auto;
	}

	h1, p {
		text-align: center;
		margin: 0 auto;
	}

	h1 {
		font-size: 2em;
		text-transform: uppercase;
		font-weight: 700;
		margin: 0 0 .5em 0;
	}

	.no-text-logo {
		display: block;
		margin: 0 auto;
		max-height: 100px;
		width: auto;
	}

	a {
		margin-top: 40px;
	}

	div {
		margin-top: 60px;
		text-align: center;
	}

	@media (min-width: 480px) {
		h1 {
			font-size: 4em;
		}
	}
</style>

<svelte:head>
	<title>Job Ninja</title>
</svelte:head>

<div>
	<div>
		<img class="no-text-logo" src="no-text-logo.png" alt="logo"/>
	</div>
	<h1>Jobs for Ninjas!</h1>
	<p>Find your next assignment right Here</p>
	<a href="jobs" class="btn">View Jobs</a>
</div>