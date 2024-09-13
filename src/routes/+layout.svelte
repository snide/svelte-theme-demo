<script lang="ts">
	let { children } = $props();
	import '../styles/globals.css';
	import { ModeWatcher, toggleMode } from 'mode-watcher';
</script>

<ModeWatcher />

<button onclick={toggleMode}>Toggle Mode</button>

{@render children()}
