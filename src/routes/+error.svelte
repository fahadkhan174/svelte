<script>
	import { base } from '$app/paths';
</script>

<main class="grid min-h-full place-items-center bg-white px-6 py-24 sm:py-32 lg:px-8">
	<div class="text-center">
		<p class="text-base font-semibold text-blue-600">404</p>
		<h1 class="mt-4 text-5xl font-semibold tracking-tight text-balance text-gray-900 sm:text-7xl">
			Page not found
		</h1>
		<p class="mt-6 text-lg font-medium text-pretty text-gray-500 sm:text-xl/8">
			Sorry, we couldn’t find the page you’re looking for.
		</p>
		<div class="mt-10 flex items-center justify-center gap-x-6">
             
			<a href="{base}/" class="rounded-m text-black py-2.5 text-lg font-semibold hover:underline"
				>&larr; Home</a
			>
			<!-- <a href="#" class="text-sm font-semibold text-gray-900">Contact support <span aria-hidden="true">&rarr;</span></a> -->
		</div>
	</div>
</main>
