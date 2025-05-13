<script>
	import image from '$lib/mini-projects/email-subscribe/images/image.jpg';
</script>

<svelte:head>
	<title>Email Subscribe | Mini Projects</title>
</svelte:head>

<!-- Background -->
<div class="flex h-full items-center justify-center px-6">
	<!-- Card -->
	<div class="mx-6 rounded-2xl bg-zinc-800 p-2">
		<!-- Flex container-->
		<div class="flex flex-col rounded-l-xl md:flex-row">
			<!-- Image -->
			<img
				src={image}
				class="object-fit h-80 transform rounded-xl duration-200 hover:scale-105 hover:rounded-xl md:h-64 md:rounded-l-xl md:rounded-r-none"
				alt=""
			/>
		</div>
		<!-- Content -->
		<div class="p-6 md:p-12">
			<h2 class="text-center font-serif text-xl font-medium text-white md:text-left">
				Get dite and fitness tips in your inbox.
			</h2>
			<p class="my-4 max-w-xs text-center text-xs leading-5 tracking-wide text-white md:text-left">
				Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ut facere voluptate voluptatum.
			</p>
			<div class="mt-5 flex flex-col space-y-4 md:flex-row md:space-y-0 md:space-x-3">
				<input
					type="text"
					class="border border-zinc-600 bg-zinc-800 p-2 px-4 text-center
					 text-white  placeholder:text-center
					  placeholder:text-xs focus:outline-none md:text-left placeholder:md:text-left"
					placeholder="Enter your email"
				/>
				<button class="">Subscribe</button>
			</div>
		</div>
	</div>
</div>
