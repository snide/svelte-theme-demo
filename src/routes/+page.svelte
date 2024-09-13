<script lang="ts">
	import { Button, ColorMode } from '$lib';
</script>

<p>This text will color based off the selected theme from the user, defaulting to system theme.</p>

<Button>This button will be light or dark based off the selected theme</Button>

<ColorMode mode="light">
	<div style="background-color: var(--bg)">
		<h2>Light Mode</h2>
		<p>This button and text will force light mode</p>
		<Button>Hello I'm a light button</Button>
	</div>
</ColorMode>

<ColorMode mode="dark">
	<div style="background-color: var(--bg)">
		<h2>Dark Mode</h2>
		<p>This button and text will force dark mode</p>
		<Button>Hello I'm a dark button</Button>
	</div>
</ColorMode>
