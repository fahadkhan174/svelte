<script lang="ts">
	let checked = $state(false);

	$effect(() => {
		const mode = localStorage.getItem('mode') || 'light';
		checked = mode === 'dark';
	});

    $effect(()=>{
        const mode = checked ? 'dark' : 'light';
        document.documentElement.setAttribute('data-theme', mode);
		localStorage.setItem('mode', mode);
    });
</script>

<svelte:head>
	<title>Dark Mode</title>
	<script>
		const mode = localStorage.getItem('mode') || 'light';
		document.documentElement.setAttribute('data-mode', mode);
	</script>
</svelte:head>

<div >
	<div class="mb-2 flex items-center gap-2">
		<input
			id="switch-link"
			type="checkbox"
			bind:checked={checked}
			class="relative inline-block h-6 w-12 cursor-pointer appearance-none rounded-full before:absolute before:top-0 before:left-0 before:inline-block before:h-full before:w-full before:rounded-full before:bg-stone-200 before:transition-colors before:duration-200 before:ease-in after:absolute after:top-2/4 after:left-0 after:h-6 after:w-6 after:-translate-y-2/4 after:rounded-full after:border after:border-stone-200 after:bg-white after:transition-all after:duration-200 after:ease-in checked:before:bg-stone-800 checked:after:translate-x-full checked:after:border-stone-800 disabled:cursor-not-allowed disabled:opacity-50 dark:after:bg-white"
		/>
		<label for="switch-link" class="cursor-pointer font-sans text-base text-stone-600 antialiased">
			Toggle Dark Mode
		</label>
	</div>
	<div class="rounded-lg bg-white px-6 py-8 shadow-xl ring ring-gray-900/5 dark:bg-gray-800">
		<div>
			<span class="inline-flex items-center justify-center rounded-md bg-indigo-500 p-2 shadow-lg">
				<svg class="h-6 w-6 stroke-white">
					<!-- ... -->
				</svg>
			</span>
		</div>
		<h3 class="mt-5 text-base font-medium tracking-tight text-gray-900 dark:text-white">
			Writes upside-down
		</h3>
		<p class="mt-2 text-sm text-gray-500 dark:text-gray-400">
			The Zero Gravity Pen can be used to write in any orientation, including upside-down. It even
			works in outer space.
		</p>
	</div>
</div>
