<script lang="ts">
	import { CLASS_BY_SIZE, type IconSize } from './utils';

	interface Props {
		size?: IconSize;
		class?: string;
	}

	let { size = 'md', class: clazz }: Props = $props();
</script>

<svg
	xmlns="http://www.w3.org/2000/svg"
	fill="currentColor"
	viewBox="0 0 24 24"
	class={clazz || CLASS_BY_SIZE[size]}
>
	<path
		fill-rule="evenodd"
		d="M6.32 2.577a49.255 49.255 0 0111.36 0c1.497.174 2.57 1.46 2.57 2.93V21a.75.75 0 01-1.085.67L12 18.089l-7.165 3.583A.75.75 0 013.75 21V5.507c0-1.47 1.073-2.756 2.57-2.93z"
		clip-rule="evenodd"
	/>
</svg>
