<script lang="ts">
	import type { HTMLButtonAttributes } from 'svelte/elements';

	export let type: HTMLButtonAttributes['type'] = 'button';
</script>

<button {type}><slot /></button>
