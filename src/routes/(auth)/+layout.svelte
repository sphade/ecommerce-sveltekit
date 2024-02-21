<script lang="ts">
	let { children } = $props();
</script>

<div class="flex h-full items-center justify-center">
	{@render children()}
</div>
