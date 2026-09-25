<script lang="ts">
	import MainPanel from '$lib/components/MainPanel.svelte';
	import SectionWithHeadingTemplate from '$lib/components/sections/SectionWithHeadingTemplate.svelte';
</script>

<svelte:head>
	<title>FAQ - Bugged YSWS</title>
</svelte:head>

<MainPanel title="FAQ.md">
	<SectionWithHeadingTemplate heading="Can I Participate?">
		Of Course! Anyone who's 13-18 years of age (18 Included!) can participate.
	</SectionWithHeadingTemplate>
	<SectionWithHeadingTemplate heading="What can I ship?">
		Anything! Can be a game, software, hardware, as long as it contains an intentional bug!
	</SectionWithHeadingTemplate>
	<SectionWithHeadingTemplate heading="Can I Use AI?">
		AI can be used for research, but assets cannot be AI-generated and no more than 10% of the code
		can be AI-generated.
	</SectionWithHeadingTemplate>
	<SectionWithHeadingTemplate heading="What counts as an 'intentional bug'?">
		Any feature that seems like it shouldn't be in the project at all, but it actually contributes
		to the functionality of it.
	</SectionWithHeadingTemplate>
</MainPanel>
