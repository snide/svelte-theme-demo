<script lang="ts">
	let { children } = $props();
	import '$lib/globals.css';
	import { ModeWatcher, toggleMode } from 'mode-watcher';
</script>

<ModeWatcher lightClassNames={['light']} darkClassNames={['dark']} />

<button onclick={toggleMode}>Toggle Mode</button>

{@render children()}
