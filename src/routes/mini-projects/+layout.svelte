<script lang="ts">
	import { base } from '$app/paths';
	import { page } from '$app/state';
	let { children } = $props();
</script>

<div class="grid grid-cols-1 gap-4 md:grid-cols-12 md:gap-4">
	<div class="col-span-3 md:col-span-3">
		<div class="container h-full max-w-lg bg-gray-50 p-6">
			<h1 class="text-3xl text-blue-800">
				<a href="{base}/mini-projects"> Mini Projects</a>
			</h1>
			<ul class="mt-6">
				<li
					class="my-4 border border-blue-200 p-2 text-lg"
					class:border-red-500={page.url.pathname === base + '/mini-projects/email-subscribe'}
				>
					<a class="text-blue-500 hover:text-blue-300" href="{base}/mini-projects/email-subscribe">
						Email Subscribe
					</a>
				</li>
                <li
					class="my-4 border border-blue-200 p-2 text-lg"
					class:border-red-500={page.url.pathname === base + '/mini-projects/pricing-grids'}
				>
					<a class="text-blue-500 hover:text-blue-300" href="{base}/mini-projects/pricing-grids">
						Pricing Grids
					</a>
				</li>
                <li
					class="my-4 border border-blue-200 p-2 text-lg"
					class:border-red-500={page.url.pathname === base + '/mini-projects/product-modal'}
				>
					<a class="text-blue-500 hover:text-blue-300" href="{base}/mini-projects/product-modal">
						Product Modal
					</a>
				</li>
                <li
					class="my-4 border border-blue-200 p-2 text-lg"
					class:border-red-500={page.url.pathname === base + '/mini-projects/image-gallery'}
				>
					<a class="text-blue-500 hover:text-blue-300" href="{base}/mini-projects/image-gallery">
						Image Gallery
					</a>
				</li>
                <li
					class="my-4 border border-blue-200 p-2 text-lg"
					class:border-red-500={page.url.pathname === base + '/mini-projects/login-modal'}
				>
					<a class="text-blue-500 hover:text-blue-300" href="{base}/mini-projects/login-modal">
						Login Modal
					</a>
				</li>
			</ul>
		</div>
	</div>
	<div class="col-span-9 md:col-span-9 bg-gray-50">
		{@render children()}
	</div>
</div>
