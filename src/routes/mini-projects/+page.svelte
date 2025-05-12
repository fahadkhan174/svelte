<script lang="ts">
	import { page } from '$app/state';
	let { children } = $props();
</script>

<svelte:head>
	<title>Mini Projects</title>
</svelte:head>

<div class="bg-gray-50 py-24 sm:py-32">
	<div class="mx-auto max-w-2xl px-6 lg:max-w-7xl lg:px-8">
		<div class="mt-10 grid gap-4 sm:mt-16 lg:grid-cols-3 lg:grid-rows-2">
			<div class="relative lg:row-span-2">
				<div class="absolute inset-px rounded-lg bg-white lg:rounded-l-[2rem]"></div>
				<div
					class="relative flex h-32 flex-col overflow-hidden rounded-[calc(var(--radius-lg)+1px)] lg:rounded-l-[calc(2rem+1px)]"
				>
					<div class="px-8 pt-8 pb-3 sm:px-10 sm:pt-10 sm:pb-0">
						<p class="mt-2 text-lg font-medium tracking-tight text-gray-950 max-lg:text-center">
							<a href="{page.url.pathname}/email-subscribe" class="hover:underline"
								>Email Subscribe</a
							>
						</p>
						<p class="mt-2 max-w-lg text-sm/6 text-gray-600 max-lg:text-center">
							<!-- Anim aute id magna aliqua ad ad non deserunt sunt. Qui irure qui lorem cupidatat
							commodo. -->
						</p>
					</div>
				</div>
			</div>
			<div class="relative max-lg:row-start-1">
				<div
					class="relative flex h-32 flex-col overflow-hidden rounded-[calc(var(--radius-lg)+1px)] max-lg:rounded-t-[calc(2rem+1px)]"
				>
					<div class="px-8 pt-8 sm:px-10 sm:pt-10">
						<p class="mt-2 text-lg font-medium tracking-tight text-gray-950 max-lg:text-center">
							Performance
						</p>
						<p class="mt-2 max-w-lg text-sm/6 text-gray-600 max-lg:text-center">
							Lorem ipsum, dolor sit amet consectetur adipisicing elit maiores impedit.
						</p>
					</div>
					<div
						class="flex flex-1 items-center justify-center px-8 max-lg:pt-10 max-lg:pb-12 sm:px-10 lg:pb-2"
					>
						<!-- <img
							class="w-full max-lg:max-w-xs"
							src="https://tailwindcss.com/plus-assets/img/component-images/bento-03-performance.png"
							alt=""
						/> -->
					</div>
				</div>
			</div>
			<div class="relative max-lg:row-start-3 lg:col-start-2 lg:row-start-2">
				<div
					class="relative flex h-32 flex-col overflow-hidden rounded-[calc(var(--radius-lg)+1px)]"
				>
					<div class="px-8 pt-8 sm:px-10 sm:pt-10">
						<p class="mt-2 text-lg font-medium tracking-tight text-gray-950 max-lg:text-center">
							Security
						</p>
						<p class="mt-2 max-w-lg text-sm/6 text-gray-600 max-lg:text-center">
							Morbi viverra dui mi arcu sed. Tellus semper adipiscing suspendisse semper morbi.
						</p>
					</div>
				</div>
			</div>
			<div class="relative lg:row-span-2">
				<div
					class="absolute inset-px rounded-lg bg-white max-lg:rounded-b-[2rem] lg:rounded-r-[2rem]"
				></div>
				<div
					class="relative flex h-32 flex-col overflow-hidden rounded-[calc(var(--radius-lg)+1px)] max-lg:rounded-b-[calc(2rem+1px)] lg:rounded-r-[calc(2rem+1px)]"
				>
					<div class="px-8 pt-8 pb-3 sm:px-10 sm:pt-10 sm:pb-0">
						<p class="mt-2 text-lg font-medium tracking-tight text-gray-950 max-lg:text-center">
							Powerful APIs
						</p>
						<p class="mt-2 max-w-lg text-sm/6 text-gray-600 max-lg:text-center">
							Sit quis amet rutrum tellus ullamcorper ultricies libero dolor eget sem sodales
							gravida.
						</p>
					</div>
					<div class="relative min-h-[30rem] w-full grow">
						<div
							class="absolute top-10 right-0 bottom-0 left-10 overflow-hidden rounded-tl-xl bg-gray-900 shadow-2xl"
						>
							<div class="flex bg-gray-800/40 ring-1 ring-white/5">
								<div class="-mb-px flex text-sm/6 font-medium text-gray-400">
									<div
										class="border-r border-b border-r-white/10 border-b-white/20 bg-white/5 px-4 py-2 text-white"
									>
										NotificationSetting.jsx
									</div>
									<div class="border-r border-gray-600/10 px-4 py-2">App.jsx</div>
								</div>
							</div>
							<div class="px-6 pt-6 pb-14">
								<!-- Your code example -->
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</div>
