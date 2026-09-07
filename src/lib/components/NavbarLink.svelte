<script lang="ts">
	import { page } from '$app/state';

	let { route, children }: { route: string; children: any } = $props();
</script>

<a
	href={route}
	class={page.url.pathname === route
		? 'border-b-2 border-b-black px-1 pb-1 text-lg font-bold'
		: 'px-1 pb-1 text-lg text-text-soft hover:text-text'}>{@render children?.()}</a
>
