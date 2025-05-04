<script lang="ts">
	import { page } from '$app/state';
	import Navbar from '@/components/Navbar.svelte';
	import '../app.css';

	let { children } = $props();
</script>

<div class="container">
	<div class="pl-6">
		<!-- svelte-ignore a11y_consider_explicit_label -->
		<a
			class="mr-4 text-lg text-blue-800 hover:underline"
			class:underline={page.url.pathname === '/'}
			href="/"
		>
			<svg
				xmlns="http://www.w3.org/2000/svg"
				viewBox="0 17.350000381469727 105.05000305175781 36.05000305175781"
				data-asc="1.058"
				width="105.05000305175781"
				height="36.05000305175781"
				class="mr-2 inline h-12 w-12"
				><defs /><g
					><g
						><g transform="translate(0, 0)"
							><path
								d="M0 17.90L26 17.90L26.50 28.30L25.60 28.30Q23.75 22.90 21.32 20.95Q18.90 19.00 14.10 19.00L12.70 19.00L12.70 35.25L14.95 35.25Q17.35 35.25 18.95 33.50Q20.55 31.75 21.15 28.70L21.90 28.70L21.90 43.50L21.05 43.50Q20.25 39.75 18.82 38.15Q17.40 36.55 14.95 36.55L12.70 36.55L12.70 51.80L18.90 51.80L18.90 52.90L0 52.90L0 51.80L2.95 51.80L2.95 19.00L0 19.00L0 17.90ZM55.95 17.90L69.30 17.90L69.30 18.85L66.55 18.85L66.55 51.95L69.30 51.95L69.30 52.90L54.05 52.90L54.05 51.95L56.80 51.95L56.80 20.70L56.60 20.70L49.10 52.90L42.85 52.90L34.05 20.55L33.85 20.55L33.85 51.95L36.60 51.95L36.60 52.90L29.80 52.90L29.80 51.95L32.55 51.95L32.55 18.85L29.80 18.85L29.80 17.90L43.30 17.90L49.95 43.65L55.95 17.90ZM90.05 52.40Q92.50 52.40 93.17 51.50Q93.85 50.60 93.85 48.45L93.85 38.75L90.65 38.75L90.65 37.65L105.05 37.65L105.05 38.75L103.10 38.75L103.10 52.85L102.35 52.85Q101.45 51.60 99.80 51.60Q99.10 51.60 95.63 52.50Q92.15 53.40 89.70 53.40Q81.55 53.40 77.08 49.00Q72.60 44.60 72.60 35.78Q72.60 26.95 77.27 22.15Q81.95 17.35 89.85 17.35Q92.90 17.35 95.97 18.13Q99.05 18.90 99.55 18.90Q100.05 18.90 100.30 18.68Q100.55 18.45 100.85 17.90L101.40 17.90L101.80 28.75L100.90 28.75Q98.45 23.90 95.97 21.13Q93.50 18.35 90.45 18.35Q82.80 18.35 82.80 33.30L82.80 37.25Q82.80 44.75 84.67 48.58Q86.55 52.40 90.05 52.40Z"
							/></g
						><g transform="translate(0, 64.55)"><path d="" /></g></g
					></g
				>
			</svg>
		</a>
		<a
			class="mr-4 h-12 w-12 text-lg text-blue-800 hover:underline"
			class:underline={page.url.pathname === '/'}
			href="/"
		>
			Home
		</a>
		<a
			class="mr-4 h-12 w-12 text-lg text-blue-800 hover:underline"
			class:underline={page.url.pathname.includes('/basics')}
			href="/basics"
		>
			Basics
		</a>
	</div>
	<!-- <Navbar /> -->
	<div class="pl-6">
	</div>
	<div class="pl-6">
		{@render children()}
	</div>
</div>
