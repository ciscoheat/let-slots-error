<script lang="ts">
	import Form from './Form.svelte';
	export let data;
</script>

<Form let:message>
	{#if message}
		<div>{message}</div>
	{/if}

	<button type="submit">submit</button>
</Form>
