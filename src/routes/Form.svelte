<script lang="ts">
	let message = '';
</script>

<form method="POST">
	<slot {message} />
</form>
