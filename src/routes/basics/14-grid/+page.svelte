<svelte:head>
	<title>Grid</title>
</svelte:head>

<div>
	<div>
		<!-- Grid cols and rows -->

		<div class="grid-col-1 grid md:grid-cols-3">
			<div class="border border-blue-600 bg-blue-100 p-10 md:col-span-2 md:row-span-2">item 1</div>
			<div class="border border-blue-600 bg-blue-100 p-10">item 2</div>
			<div class="border border-blue-600 bg-blue-100 p-10">item 3</div>
			<div class="border border-blue-600 bg-blue-100 p-10">item 4</div>
			<div class="border border-blue-600 bg-blue-100 p-10">item 5</div>
			<div class="border border-blue-600 bg-blue-100 p-10">item 6</div>
			<div class="border border-blue-600 bg-blue-100 p-10 md:col-span-2">item 7</div>
			<div class="border border-blue-600 bg-blue-100 p-10">item 8</div>
			<div class="border border-blue-600 bg-blue-100 p-10 md:col-span-3">item 9</div>
		</div>

		<!-- Col and row span -->
	</div>

	<!-- 
  Grid Template Columns
  grid-cols-1	    grid-template-columns: repeat(1, minmax(0, 1fr));
  grid-cols-2	    grid-template-columns: repeat(2, minmax(0, 1fr));
  grid-cols-3	    grid-template-columns: repeat(3, minmax(0, 1fr));
  grid-cols-4	    grid-template-columns: repeat(4, minmax(0, 1fr));
  grid-cols-5	    grid-template-columns: repeat(5, minmax(0, 1fr));
  grid-cols-6	    grid-template-columns: repeat(6, minmax(0, 1fr));
  grid-cols-7	    grid-template-columns: repeat(7, minmax(0, 1fr));
  grid-cols-8	    grid-template-columns: repeat(8, minmax(0, 1fr));
  grid-cols-9	    grid-template-columns: repeat(9, minmax(0, 1fr));
  grid-cols-10	  grid-template-columns: repeat(10, minmax(0, 1fr));
  grid-cols-11	  grid-template-columns: repeat(11, minmax(0, 1fr));
  grid-cols-12	  grid-template-columns: repeat(12, minmax(0, 1fr));
  grid-cols-none	grid-template-columns: none;
 -->

	<!-- Grid Template Rows
  grid-rows-1	    grid-template-rows: repeat(1, minmax(0, 1fr));
  grid-rows-2	    grid-template-rows: repeat(2, minmax(0, 1fr));
  grid-rows-3	    grid-template-rows: repeat(3, minmax(0, 1fr));
  grid-rows-4	    grid-template-rows: repeat(4, minmax(0, 1fr));
  grid-rows-5	    grid-template-rows: repeat(5, minmax(0, 1fr));
  grid-rows-6	    grid-template-rows: repeat(6, minmax(0, 1fr));
  grid-rows-none	grid-template-rows: none;
  -->
</div>
