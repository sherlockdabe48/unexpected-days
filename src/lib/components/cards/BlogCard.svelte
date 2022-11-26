<script>
	import Card from './Card.svelte';
	export let title = '';
	export let subtitle = '';

	// your script goes here
</script>

<!-- markup (zero or more items) goes here -->
<div class="blog-card">
	<Card>
		<!-- <picture class="image-container">
			<img class="blog-image" src="https://picsum.photos/400/200?grayscale" alt="" />
		</picture> -->
		<div class="title-wrapper">
			<h1 class="title">{title}</h1>
			<h2 class="subtitle">{subtitle}</h2>
		</div>
	</Card>
</div>

<style lang="scss">
	.blog-card {
		:hover {
			cursor: pointer;
		}
		// max-width: 400px;
		// max-height: 400px;

		// .image-container {
		// 	margin: 0;
		// 	.blog-image {
		// 		border-top-right-radius: 4px;
		// 		border-top-left-radius: 4px;
		// 	}
		// }

		.title-wrapper {
			padding: 1rem;

			.title {
				font-size: 2rem;
			}

			.subtitle {
				font-size: 1rem;
			}
		}
	}
</style>
