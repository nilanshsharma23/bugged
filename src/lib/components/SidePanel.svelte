<script lang="ts">
	let { children } = $props();
</script>

<div class="flex h-fit w-full flex-col gap-3 rounded-lg border border-border bg-panel p-4 md:w-96">
	{@render children?.()}
</div>
