<svelte:head>
	<title>Colors</title>
</svelte:head>

<!-- Default colors -->
<!-- white, black, red, green, blue, orange, yellow, purple, lime, emerald, teal, cyan, indigo, violet, fuchsia, pink, rose, sky, gray, slate, zinc, neutral, stone, amber,  -->

<!-- Text Colors -->
<p class="text-xl text-black">Tailwind is awesome</p>
<p class="text-xl text-red-500">Tailwind is awesome</p>
<p class="text-xl text-green-300">Tailwind is awesome</p>
<p class="text-xl text-slate-500">Tailwind is awesome</p>
<p class="text-xl text-zinc-300">Tailwind is awesome</p>
<p class="text-xl text-emerald-600">Tailwind is awesome</p>
<br />

<!-- Background Colors -->
<p class="bg-black text-xl text-white">Tailwind is awesome</p>
<p class="bg-red-500 text-xl text-white">Tailwind is awesome</p>
<p class="bg-green-300 text-xl text-white">Tailwind is awesome</p>
<p class="bg-slate-500 text-xl text-white">Tailwind is awesome</p>
<p class="bg-zinc-300 text-xl text-white">Tailwind is awesome</p>
<p class="bg-emerald-600 text-xl text-white">Tailwind is awesome</p>
<br />

<!-- Text Underline -->
<p class="underline decoration-black">Tailwind is awesome</p>
<p class="underline decoration-red-500">Tailwind is awesome</p>
<p class="underline decoration-green-300">Tailwind is awesome</p>
<p class="underline decoration-slate-500">Tailwind is awesome</p>
<p class="underline decoration-zinc-300">Tailwind is awesome</p>
<p class="underline decoration-emerald-600">Tailwind is awesome</p>
<br />

<!-- Border Colors -->
<div class="border border-black">Tailwind is awesome</div>
<div class="border border-red-500">Tailwind is awesome</div>
<div class="border border-green-300">Tailwind is awesome</div>
<div class="border border-slate-500">Tailwind is awesome</div>
<br />

<!-- Divide Colors -->
<div class="divide-y divide-blue-400">
	<div>Item 1</div>
	<div>Item 2</div>
	<div>Item 3</div>
</div>
<br />

<!-- Outline Colors -->
<button class="outline outline-black">Tailwind is awesome</button>
<button class="outline outline-teal-400">Tailwind is awesome</button>
<button class="outline outline-blue-400">Tailwind is awesome</button>
<br />

<!-- Box Shadow Colors (Opacity defaults to 100, but you can set it)-->
<button class="mt-4 border border-amber-100 bg-amber-600 p-2 text-white shadow-lg shadow-amber-100">
	SUBSCRIBE
</button>
<button
	class="mt-6 rounded border border-teal-400 p-2 shadow-lg shadow-teal-400/20 hover:cursor-pointer hover:bg-teal-400 hover:text-white"
>
	SUBSCRIBE
</button>
<br />

<!-- Accent Colors -->
<div class="mt-6">
	<!-- accent not working as tailwind forms plugin normalises styles -->
	<input type="text" class="accent-red-300" />

	<!-- using normal classes -->
	<input type="text" class="focus:border-red-300 focus:ring-red-300" />
	<label>
		<input type="checkbox" class="rounded text-pink-500 focus:ring-pink-500" checked />
		Customized
	</label>
</div>
<br />

<!-- Arbitrary Colors -->
<div class="bg-[#24adbd] p-1 text-white">Hello World</div>
<div class="bg-[rgba(255, 255, 255, 0.5)]">Hello World</div>
<div class="bg-[steelblue] p-1 text-white">Hello World</div>
