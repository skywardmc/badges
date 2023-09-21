<script lang="ts">
	import '$lib/css/badge.scss';
	import Badges from '$lib/components/Badges.svelte';
	import Badge from '$lib/components/Badge.svelte';
	import BadgeRaw from '$lib/components/BadgeRaw.svelte';
</script>

<h1>Welcome to your library project</h1>
<p>Create your package using @sveltejs/package and preview/showcase your work with SvelteKit</p>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>


<BadgeRaw id="cute" name="Cute" head="You are" link="#" />
<BadgeRaw id="cute" name="Amazing" head="You are" link="#" />
