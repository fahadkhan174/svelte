<svelte:head>
	<title>Flex</title>
</svelte:head>

<div>
	<div>
		<!-- Flex and alignment -->
		<div class="flex h-72 w-full flex-wrap items-center justify-around bg-gray-100">
			<div class="border border-blue-300 bg-blue-100 p-8">item 1</div>
			<div class="border border-blue-300 bg-blue-100 p-8">item 2</div>
			<div class="border border-blue-300 bg-blue-100 p-8">item 3</div>
			<div class="border border-blue-300 bg-blue-100 p-8">item 4</div>
			<div class="border border-blue-300 bg-blue-100 p-8">item 5</div>
			<div class="border border-blue-300 bg-blue-100 p-8">item 6</div>
			<div class="border border-blue-300 bg-blue-100 p-8">item 7</div>
			<div class="border border-blue-300 bg-blue-100 p-8">item 8</div>
		</div>
		<br />

		<!-- Flex Column, Gap and Order -->
		<div class="flex h-96 w-full flex-col items-center justify-between gap-2 bg-gray-100">
			<div class="order-3 border border-blue-300 bg-blue-100 p-8">item 1</div>
			<div class="order-2 border border-blue-300 bg-blue-100 p-8">item 2</div>
			<div class="order-4 border border-blue-300 bg-blue-100 p-8">item 3</div>
			<div class="order-1 border border-blue-300 bg-blue-100 p-8">item 4</div>
		</div>
		<br />

		<!-- Grow and shrink -->
		<div class="flex w-full bg-gray-100">
			<div class="flex-initial w-24 border border-blue-300 bg-blue-100 p-8">item 1</div>
			<div class="flex-none w-24 border border-blue-300 bg-blue-100 p-8">item 2</div>
			<div class="flex-auto w-24 border border-blue-300 bg-blue-100 p-8">item 3</div>
			<div class="flex-1 w-24 border border-blue-300 bg-blue-100 p-8">item 4</div>
			<div class="border border-blue-300 bg-blue-100 p-8">item 5</div>
			<div class="border border-blue-300 bg-blue-100 p-8">item 6</div>
			<div class="border border-blue-300 bg-blue-100 p-8">item 7</div>
		</div>
	</div>
	<!-- Justify Content
      justify-start	      justify-content: flex-start;
      justify-end	            justify-content: flex-end;
      justify-center	      justify-content: center;
      justify-between	      justify-content: space-between;
      justify-around	      justify-content: space-around;
      justify-evenly          justify-content: space-evenly;
    -->

	<!-- 
      items-start	            align-items: flex-start;
      items-end	            align-items: flex-end;
      items-center	      align-items: center;
      items-baseline	      align-items: baseline;
      items-stretch	      align-items: stretch;
     -->

	<!-- Flex Direction
      flex-row	            flex-direction: row;
      flex-row-reverse	      flex-direction: row-reverse;
      flex-col	            flex-direction: column;
      flex-col-reverse	      flex-direction: column-reverse;
    -->

	<!-- 
      flex-wrap	            flex-wrap: wrap;
      flex-wrap-reverse	      flex-wrap: wrap-reverse;
      flex-nowrap	            flex-wrap: nowrap;
     -->

	<!-- Flex Properties
      flex-none	            flex: none;     
      Prevent item from growing or shrinking

      flex-initial	      flex: 0 1 auto; 
      Allow item to shrink but not grow, taking into account its initial size

      flex-auto	            flex: 1 1 auto; 
      Allow item to grow and shrink, taking into account its initial size

      flex-1	            flex: 1 1 0%;   
      Allow item to grow and shrink as needed, ignoring its initial size
    -->
</div>
