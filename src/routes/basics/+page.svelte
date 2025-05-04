<script>
	import { onMount } from 'svelte';

	const rows = 8;
	const cols = 9;
	const w = 160;
	const h = 240;
	const src =
		'https://highline.huffingtonpost.com/articles/en/poor-millennials/media/images/sprites/becky.png';

	let current = $state(0);

	onMount(() => {
		const interval = setInterval(() => {
			current = (current + 1) % (cols - 1);
		}, 100);

		return () => {
			clearInterval(interval);
		};
	});
</script>

<div class="text-2xl text-black">Learning the basics</div>

<div
	class="good-2"
	style="
        background-image: url({src});
        background-size: calc(100% * {rows}) calc(100% * {cols});
        background-position: {current * -w}px {-h}px;
        width: {w}px;
        height: {h}px;
    "
></div>
