<script>
	import Column from './Column.svelte';
</script>

<div class="rounded-card">
	<slot />
</div>

<style>
	.rounded-card {
		background-color: var(--tertiary-color);
		height: 84px;
		width: 84px;
		display: flex;
		border-radius: 42px;
		align-items: center;
		justify-content: center;
	}
</style>
