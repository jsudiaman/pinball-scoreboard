<script>
	import { onMount } from 'svelte';

	onMount(init);

	/**
	 * This function runs ONLY when the browser is ready.
	 * Put all your "document" and "window" code inside here.
	 * - Safe: document.getElementById(...)
	 * - Safe: window.alert(...)
	 * - Safe: console.log(...)
	 */
	function init() {
		console.log('the component has mounted');
	}
</script>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://svelte.dev/docs/kit">svelte.dev/docs/kit</a> to read the documentation</p>
