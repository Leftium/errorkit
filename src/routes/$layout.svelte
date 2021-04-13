<script context="module">
	export async function load({ page, fetch, session, context }) {
		return {
			status: 499,
			error: new Error(`Could not load`)
		};
	}
</script>

<script>
	import '../app.css';
</script>

<slot />
