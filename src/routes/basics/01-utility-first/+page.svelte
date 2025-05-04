<script>
	import warningImage from '$lib/img/warning.svg';
</script>

<svelte:head>
	<title>Utility First</title>
</svelte:head>

<div class="mx-auto mt-12 flex max-w-sm items-center space-x-4 rounded-xl bg-white p-6 shadow-xl">
	<img class="h-12 w-12" src={warningImage} alt="warning" />
	<div>
		<div class="text-xl font-medium text-black">Are you sure?</div>
		<p class="text-slate-500">You are about to delete a post</p>
	</div>
</div>
