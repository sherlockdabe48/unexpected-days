<script>
	import Blogs from '../lib/components/Blogs.svelte';
</script>

<svelte:head>
	<title>Unexpected Days</title>
	<meta name="description" content="unexpected days web" />
</svelte:head>

<section>
	<div class="welcome">
		<h2>Welcome to</h2>
		<h1>Unexpected Days</h1>
	</div>

	<Blogs />
</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 0.6;
	}

	/* h1 {
		width: 100%;
	} */

	.welcome {
		text-align: center;
		/* font-size: 4rem; */
	}
</style>
