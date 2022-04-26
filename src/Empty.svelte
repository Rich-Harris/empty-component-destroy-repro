<script>
	import { onMount } from 'svelte';
	
	onMount(() => {
		console.log('mounting');
		return () => console.log('destroying');
	});
</script>