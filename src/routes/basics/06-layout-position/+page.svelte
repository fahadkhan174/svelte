<script>
	import img1 from '$lib/img/img1.jpg';
</script>

<svelte:head>
	<title>Layout & Position</title>
</svelte:head>

<div>
	<!-- Positioning -->
	<div class="relative h-12 w-1/2 bg-yellow-100">
		<p>Parent Element</p>
		<div class="absolute right-0 bottom-0 bg-yellow-400">
			<p>Absolute Child</p>
		</div>
	</div>
	<br />

	<!-- Top left corner -->
	<div class="relative h-24 w-1/2 bg-yellow-100">
		<div class="absolute top-0 left-0 h-12 w-12 bg-yellow-400"></div>
	</div>
	<br />

	<!-- Top right corner -->
	<div class="relative h-24 w-1/2 bg-yellow-100">
		<div class="absolute top-0 right-0 h-12 w-12 bg-yellow-400"></div>
	</div>
	<br />

	<!-- Bottom left corner -->
	<div class="relative h-24 w-1/2 bg-yellow-100">
		<div class="absolute bottom-0 left-0 h-12 w-12 bg-yellow-400"></div>
	</div>
	<br />

	<!-- Bottom right corner -->
	<div class="relative h-24 w-1/2 bg-yellow-100">
		<div class="absolute right-0 bottom-0 h-12 w-12 bg-yellow-400"></div>
	</div>
	<br />

	<!-- Span top edge -->
	<div class="relative h-24 w-1/2 bg-yellow-100">
		<div class="absolute inset-x-0 top-0 h-12 bg-yellow-400"></div>
	</div>
	<br />

	<!-- Span left edge -->
	<div class="relative h-24 w-1/2 bg-yellow-100">
		<div class="absolute inset-y-0 left-0 w-12 bg-yellow-400"></div>
	</div>
	<br />

	<!-- Span right edge -->
	<div class="relative h-24 w-1/2 bg-yellow-100">
		<div class="absolute inset-y-0 right-0 w-12 bg-yellow-400"></div>
	</div>
	<br />

	<!-- Span bottom edge -->
	<div class="relative h-24 w-1/2 bg-yellow-100">
		<div class="absolute inset-x-0 bottom-0 h-12 bg-yellow-400"></div>
	</div>
	<br />

	<!-- Display Classes -->
	<div>
		Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim, temporibus. Consequuntur velit
		<span class="inline text-slate-200">This is inline</span> minima! Repellat consequatur
		aspernatur voluptate sed culpa, eius ipsum. Error
		<span class="inline-block text-slate-200">This is inline block</span>
		expedita nostrum iure odio quae repellat beatae amet sit.
		<span class="block text-slate-200">This is block</span>
		Vel, beatae quis obcaecati quidem mollitia dolores architecto delectus ipsam aut eius autem sit sunt
		soluta deserunt ipsa, provident nobis!
		<span class="hidden text-slate-200">This is hidden</span>Quae ad similique neque magnam, odit
		officiis.
	</div>
	<br />

	<!-- Z-Index -->
	<div class="relative h-36">
		<div class="absolute left-20 z-20 h-24 w-24 bg-blue-100">1</div>
		<div class="absolute left-40 z-10 h-24 w-24 bg-blue-200">2</div>
		<div class="absolute left-60 h-24 w-24 bg-blue-300">3</div>
		<div class="absolute left-80 h-24 w-24 bg-blue-400">4</div>
		<div class="absolute left-100 h-24 w-24 bg-blue-500">5</div>
	</div>
	<br />

	<!-- Floats -->
	<div class="w-full">
		<!-- svelte-ignore a11y_img_redundant_alt -->
		<img class="float-left m-2 h-64 w-64" src={img1} alt="image 1" />
		<p>
			Lorem ipsum dolor, sit amet consectetur adipisicing elit. Provident magni recusandae illum.
			Sit placeat maiores voluptatum, dicta iste officia adipisci fugit quaerat saepe eaque esse
			dolor laboriosam eos earum commodi? Explicabo minus officia quae aspernatur molestiae voluptas
			et neque suscipit tempora alias itaque placeat magnam laborum eos unde assumenda, amet
			reiciendis! Inventore sapiente fuga quia ab enim, assumenda nobis quasi dolore ipsam amet
			iusto reiciendis hic, illo dolorum qui impedit maxime commodi delectus! Est quo deleniti
			maiores vel odio cumque distinctio ipsa quia, veniam amet nisi doloribus soluta quis placeat
			dolorum tempora architecto atque laboriosam fugiat! Error, qui mollitia! Facere, dicta!
			Dolorum nesciunt voluptates provident, cumque aut molestias maxime porro ipsa neque
			necessitatibus, laboriosam omnis soluta minima ut eligendi ducimus nulla nostrum laudantium
			dolor voluptatibus recusandae ab hic tenetur! Ipsum voluptatibus optio esse, recusandae
			dolorem qui dolores, inventore unde, eum animi exercitationem eligendi neque consectetur
			distinctio praesentium quia? Minus mollitia tempore aperiam ullam adipisci porro nam, rem
			omnis cum totam harum nobis. Qui, nostrum sunt? Earum rem facilis minima reiciendis provident
			ipsum explicabo reprehenderit quis et cupiditate beatae eligendi aliquid, quo, cumque vitae
			fugiat cum corrupti. Vel, aut voluptas, fugiat, saepe quia ex dolor magnam qui assumenda sed
			velit neque?
		</p>
	</div>
</div>

<!-- Position Classes
      static	    position: static;
      fixed	      position: fixed;
      absolute	  position: absolute;
      relative	  position: relative;
      sticky	    position: sticky;
    -->

<!-- Display Classes
      block	            display: block;
      inline-block	    display: inline-block;
      inline	          display: inline;
      flex	            display: flex;
      inline-flex	      display: inline-flex;
      table	            display: table;
      grid	            display: grid;
      inline-grid	      display: inline-grid;
      contents	        display: contents;
      list-item	        display: list-item;
      hidden	          display: none;
    -->

<!-- Z-Index
      z-0	    z-index: 0;
      z-10	  z-index: 10;
      z-20	  z-index: 20;
      z-30	  z-index: 30;
      z-40	  z-index: 40;
      z-50	  z-index: 50;
      z-auto	z-index: auto;
    -->

<!-- Float
      float-right	  float: right;
      float-left	  float: left;
      float-none	  float: none;
    -->
