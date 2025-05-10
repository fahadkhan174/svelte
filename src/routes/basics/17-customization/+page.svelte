<script>
	import { browser } from '$app/environment';

	function showBrowserWidth() {
		const width =
			window.innerWidth || document.documentElement.clientWidth || document.body.clientWidth;

		const h1Element = document.querySelector('h1');
		if (h1Element) {
			h1Element.innerHTML = `Width: ${width}`;
		} else {
			console.error('No h1 element found in the document');
		}
	}

	if (browser) {
		window.onload = showBrowserWidth;
		window.onresize = showBrowserWidth;
	}
</script>

<div
	class="md:bg-primary bg-black sm:bg-green-800 lg:bg-yellow-800 xl:bg-purple-800 2xl:bg-orange-800"
>
	<h1 class="text-xl text-white md:text-3xl xl:text-5xl">Tailwind is awesome</h1>
</div>
<div class="border-secondary border p-6">
	<h1 class="text-primary text-xl md:text-3xl xl:text-5xl">Tailwind is awesome</h1>
</div>
