<script lang="ts">
	import BadgeRaw from '$lib/components/BadgeRaw.svelte';
	import type Badge from '$lib/types';
	export let badge: Badge;
	export let id = badge.id;
	export let rel = badge.rel;
	export let link = badge.link;
	export let name = badge.name;
	export let head = badge.head;
	export let title = badge.title || `${head} ${name}`;


</script>

<BadgeRaw rel="{rel}" id="{id}" link="{link}" name="{name}" title="{title}" alt="{name} Logo" head="{head}"/>
