<script>
	// your script goes here
</script>

<!-- markup (zero or more items) goes here -->
<div class="card">
	<slot><!-- optional fallback --></slot>
</div>

<style>
	/* your styles go here */
	.card {
		min-height: 160px;
		min-width: 160px;
		/* padding: 8px; */
		background-color: white;
		border-radius: 8px;
	}
</style>
