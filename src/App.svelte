<script>
	import Empty from './Empty.svelte';

	let active = false;
</script>

<p>
	Toggle the checkbox and watch the console. It should log 'mounted' when active
	becomes true and 'destroyed' when it becomes false, but it doesn't
</p>

<label>
	<input type="checkbox" bind:checked={active} />
	active
</label>

<svelte:component this={active ? Empty : null} />
