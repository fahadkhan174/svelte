<script>
	import img1 from '$lib/img/img1.jpg';
</script>

<svelte:head>
	<title>Background & Shadows</title>
</svelte:head>

<div>
	<!-- Background Classes -->
	<div
		class="h-64 w-72 bg-cover bg-center bg-no-repeat"
		style="background-image: url({img1});"
	></div>
	<br />

	<!-- Gradients -->
	<div class="h-24 bg-gradient-to-r from-cyan-500 to-blue-500"></div>
	<br />

	<!-- Shadows -->
	<div class="mt-4 w-96 p-3 shadow">
		Lorem ipsum dolor sit amet consectetur adipisicing elit. Perspiciatis facere ducimus quisquam
		impedit saepe aut, tenetur iure ipsa qui officia.
	</div>
	<div class="mt-4 w-96 p-3 shadow-md shadow-teal-400/50">
		Lorem ipsum dolor sit amet consectetur adipisicing elit. Perspiciatis facere ducimus quisquam
		impedit saepe aut, tenetur iure ipsa qui officia.
	</div>
	<div class="mt-4 w-96 p-3 shadow-lg">
		Lorem ipsum dolor sit amet consectetur adipisicing elit. Perspiciatis facere ducimus quisquam
		impedit saepe aut, tenetur iure ipsa qui officia.
	</div>
	<div class="mt-4 w-96 p-3 shadow-xl">
		Lorem ipsum dolor sit amet consectetur adipisicing elit. Perspiciatis facere ducimus quisquam
		impedit saepe aut, tenetur iure ipsa qui officia.
	</div>
	<div class="mt-4 w-96 p-3 shadow-inner shadow-blue-400/50">
		Lorem ipsum dolor sit amet consectetur adipisicing elit. Perspiciatis facere ducimus quisquam
		impedit saepe aut, tenetur iure ipsa qui officia.
	</div>
	<div class="mt-4 w-96 p-3 shadow-2xl">
		Lorem ipsum dolor sit amet consectetur adipisicing elit. Perspiciatis facere ducimus quisquam
		impedit saepe aut, tenetur iure ipsa qui officia.
	</div>
	<br />

	<!-- Mix Blend -->
	<div class="flex justify-center -space-x-24">
		<div class="bg-blue-400 mix-blend-multiply">
			Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ipsa incidunt debitis facere aperiam
			magni obcaecati delectus quibusdam enim in voluptatem.
		</div>
		<div class="bg-pink-400 mix-blend-multiply">
			Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestiae, maiores atque. Placeat
			animi quasi autem! Laboriosam molestias iusto architecto vero.
		</div>
	</div>
</div>
