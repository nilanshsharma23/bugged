<script lang="ts">
	let { children, onclick } = $props();
</script>

<button
	{onclick}
	class="cursor-pointer rounded-xl border-2 border-black bg-emerald-600 px-8 py-2 text-3xl text-white shadow-[3px_3px_0px_#000] transition-all hover:shadow-[0px_0px_0px_#000]"
	>{@render children?.()}</button
>
