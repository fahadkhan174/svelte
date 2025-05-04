<script>
	import { base } from '$app/paths';
	import { page } from '$app/state';

	let { children } = $props();
</script>

<div class="grid grid-cols-12 gap-4">
	<div class="col-span-3">
		<div class="container h-full max-w-lg bg-gray-50 p-6">
			<h1 class="text-3xl text-blue-800">
				<a href="{base}/basics"> Tailwind CSS Basics </a>
			</h1>
			<ul class="mt-6">
				<li
					class="my-4 border border-blue-200 p-2 text-lg"
					class:border-red-500={page.url.pathname === base + '/basics/01-utility-first'}
				>
					<a class="text-blue-500 hover:text-blue-300" href="{base}/basics/01-utility-first">
						Utility First Example
					</a>
				</li>
				<li
					class="my-4 border border-blue-200 p-2 text-lg"
					class:border-red-500={page.url.pathname === base + '/basics/02-colors'}
				>
					<a class="text-blue-500 hover:text-blue-300" href="{base}/basics/02-colors">Colors</a>
				</li>
				<li
					class="my-4 border border-blue-200 p-2 text-lg"
					class:border-red-500={page.url.pathname === base + '/basics/03-container-spacing'}
				>
					<a class="text-blue-500 hover:text-blue-300" href="{base}/basics/03-container-spacing"
						>Container & Spacing</a
					>
				</li>
				<li
					class="my-4 border border-blue-200 p-2 text-lg"
					class:border-red-500={page.url.pathname === base + '/basics/04-typography'}
				>
					<a class="text-blue-500 hover:text-blue-300" href="{base}/basics/04-typography"
						>Typography</a
					>
				</li>
				<li
					class="my-4 border border-blue-200 p-2 text-lg"
					class:border-red-500={page.url.pathname === base + '/basics/05-sizing'}
				>
					<a class="text-blue-500 hover:text-blue-300" href="{base}/basics/05-sizing">Sizing</a>
				</li>
				<li
					class="my-4 border border-blue-200 p-2 text-lg"
					class:border-red-500={page.url.pathname === base + '/basics/06-layout-position'}
				>
					<a class="text-blue-500 hover:text-blue-300" href="{base}/basics/06-layout-position"
						>Layout & Position</a
					>
				</li>
				<li
					class="my-4 border border-blue-200 p-2 text-lg"
					class:border-red-500={page.url.pathname === base + '/basics/07-backgrounds-shadows'}
				>
					<a class="text-blue-500 hover:text-blue-300" href="{base}/basics/07-backgrounds-shadows"
						>Backgrounds & Shadows</a
					>
				</li>
				<li
					class="my-4 border border-blue-200 p-2 text-lg"
					class:border-red-500={page.url.pathname === base + '/basics/08-borders'}
				>
					<a class="text-blue-500 hover:text-blue-300" href="{base}/basics/08-borders"
						>Borders & Border Radius</a
					>
				</li>
				<li
					class="my-4 border border-blue-200 p-2 text-lg"
					class:border-red-500={page.url.pathname === base + '/basics/09-filters'}
				>
					<a class="text-blue-500 hover:text-blue-300" href="{base}/basics/09-filters">Filters</a>
				</li>
				<li
					class="my-4 border border-blue-200 p-2 text-lg"
					class:border-red-500={page.url.pathname === base + '/basics/10-interactivity'}
				>
					<a class="text-blue-500 hover:text-blue-300" href="{base}/basics/10-interactivity"
						>Interactivity</a
					>
				</li>
				<li
					class="my-4 border border-blue-200 p-2 text-lg"
					class:border-red-500={page.url.pathname === base + '/basics/11-breakpoints'}
				>
					<a class="text-blue-500 hover:text-blue-300" href="{base}/basics/11-breakpoints"
						>Breakpoints</a
					>
				</li>
				<li
					class="my-4 border border-blue-200 p-2 text-lg"
					class:border-red-500={page.url.pathname === base + '/basics/12-columns'}
				>
					<a class="text-blue-500 hover:text-blue-300" href="{base}/basics/12-columns"
						>Column Layouts</a
					>
				</li>
				<li
					class="my-4 border border-blue-200 p-2 text-lg"
					class:border-red-500={page.url.pathname === base + '/basics/13-flex'}
				>
					<a class="text-blue-500 hover:text-blue-300" href="{base}/basics/13-flex">Flexbox</a>
				</li>
				<li
					class="my-4 border border-blue-200 p-2 text-lg"
					class:border-red-500={page.url.pathname === base + '/basics/14-grid'}
				>
					<a class="text-blue-500 hover:text-blue-300" href="{base}/basics/14-grid">Grid</a>
				</li>
				<li
					class="my-4 border border-blue-200 p-2 text-lg"
					class:border-red-500={page.url.pathname === base + '/basics/15-transform-transition'}
				>
					<a class="text-blue-500 hover:text-blue-300" href="{base}/basics/15-transform-transition"
						>Transform & Transitions</a
					>
				</li>
				<li
					class="my-4 border border-blue-200 p-2 text-lg"
					class:border-red-500={page.url.pathname === base + '/basics/16-animation'}
				>
					<a class="text-blue-500 hover:text-blue-300" href="{base}/basics/16-animation"
						>Animation</a
					>
				</li>
				<li
					class="my-4 border border-blue-200 p-2 text-lg"
					class:border-red-500={page.url.pathname === base + '/basics/17-customization'}
				>
					<a class="text-blue-500 hover:text-blue-300" href="{base}/basics/17-customization"
						>Customization & Config</a
					>
				</li>
				<li
					class="my-4 border border-blue-200 p-2 text-lg"
					class:border-red-500={page.url.pathname === base + '/basics/18-dark-mode'}
				>
					<a class="text-blue-500 hover:text-blue-300" href="{base}/basics/18-dark-mode"
						>Dark Mode</a
					>
				</li>
			</ul>
		</div>
	</div>
	<div class="col-span-9 p-12">
		{@render children()}
	</div>
</div>
