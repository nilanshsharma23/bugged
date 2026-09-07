<script lang="ts">
	import MainPanel from '$lib/components/MainPanel.svelte';
	import IntentionalBugsSection from '$lib/components/sections/IntentionalBugsSection.svelte';
	import SectionWithHeadingTemplate from '$lib/components/sections/SectionWithHeadingTemplate.svelte';
	import SidePanel from '$lib/components/SidePanel.svelte';
</script>

<svelte:head>
	<title>Bugged YSWS</title>
</svelte:head>

<MainPanel title="README.md">
	<div class="border-b border-b-border py-2 text-2xl font-bold">bugged</div>
	<div class="py-2 text-text-soft">all that glitches isn't mold.</div>
	<div class="flex flex-row flex-wrap gap-4 py-2">
		<div class="rounded-xl bg-violet-bg px-3 font-mono text-sm text-violet-label">
			status: draft
		</div>
		<div class="rounded-xl bg-amber-bg px-3 font-mono text-sm text-amber-label">
			issues: of course
		</div>
		<div class="rounded-xl bg-slate-bg px-3 font-mono text-sm text-slate-label">
			bugging it: yes
		</div>
	</div>
	<div class="py-2">
		Ship a project with intentional bugs and creative ways of exploiting them, get Security, Puzzle
		and Debugging related stuff!
	</div>
	<IntentionalBugsSection />
	<SectionWithHeadingTemplate heading="What do We Ship?">
		Debugging, Security and Puzzle related goodies! <br />
		Debugging - A Rubber Duck, A USB Drive, AI Credits etc. <br /> Security - Flipper Zero, Yubikey,
		Raspberry Pi etc. <br /> Puzzle - A Rubik's Cube and stuff!
	</SectionWithHeadingTemplate>
	<div class="pt-4">Made with ♥ by nilu and Lemong!</div>
</MainPanel>
<div class="flex flex-col gap-4">
	<SidePanel>
		<div class="text-text-soft">About</div>
		<div>It's Bugged, Baby!</div>
		<button class="w-full cursor-pointer rounded-lg bg-text py-1 text-panel">Sign Up</button>
	</SidePanel>
	<SidePanel>
		<div class="text-text-soft">Links</div>
		<a
			href="https://rsvp.hackclub.community/bugged"
			target="_blank"
			rel="noopener noreferrer"
			class="font-bold">RSVP</a
		>
		<a
			href="https://hackclub.enterprise.slack.com/archives/C0BT0SH8Z9D"
			target="_blank"
			rel="noopener noreferrer"
			class="font-bold">#bugged on slack</a
		>
	</SidePanel>
	<SidePanel>
		<div class="text-text-soft">Contributors</div>
		@nilu, @lemong, #hackclub!
	</SidePanel>
</div>
