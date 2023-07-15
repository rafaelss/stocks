<script>
	import '../app.css';
</script>

<slot />

<style lang="postcss">
	:global(html) {
		/* background-color: theme(colors.gray.100); */
		@apply p-5;
	}
</style>
