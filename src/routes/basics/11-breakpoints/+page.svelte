<svelte:head>
	<title>Breakpoints & Media Queries</title>
</svelte:head>

<!-- Tailwind is mobile-first -->
<div>
	<div class="h-48 w-48 bg-black sm:bg-green-100 md:bg-red-100 lg:bg-blue-100"></div>
</div>

<!-- Breakpoint Classes
    sm	640px	  @media (min-width: 640px) { ... }
    md	768px	  @media (min-width: 768px) { ... }
    lg	1024px	@media (min-width: 1024px) { ... }
    xl	1280px	@media (min-width: 1280px) { ... }
    2xl	1536px	@media (min-width: 1536px) { ... }
  -->
