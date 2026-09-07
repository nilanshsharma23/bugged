<script lang="ts">
	let { heading, children } = $props();
</script>

<div class="border-b border-b-border py-2 text-xl font-bold">
	{heading}
</div>
<div class="py-2">
	{@render children?.()}
</div>
