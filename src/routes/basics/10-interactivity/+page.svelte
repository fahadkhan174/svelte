<svelte:head>
	<title>Interactivity</title>
</svelte:head>

<div>
	<div>
		<!-- Hover State Styling -->
		<button class="rounded-lg bg-black px-4 py-2 text-white hover:bg-amber-300 hover:text-black"
			>Submit</button
		>

		<!-- Focus State Styling -->
		<button class="rounded-lg bg-black px-4 py-2 text-white focus:bg-red-300 focus:text-white"
			>Submit</button
		>

		<!-- Active State Styling -->
		<button
			class="rounded-lg bg-black px-4 py-2 text-white shadow active:bg-emerald-300 active:text-black"
			>Submit</button
		>
	</div>
	<br />

	<!-- Styling based on parent state -->
	<div
		class="group mx-auto block max-w-xs cursor-pointer space-y-3 rounded-lg bg-white p-6 shadow-lg hover:bg-sky-300"
	>
		<h1 class="group-hover:text-white">Card Title</h1>
		<p class="group-hover:text-white">This is card text</p>
	</div>
	<br />

	<!-- Pseudo Classes -->
	<ul>
		<li class="odd:bg-orange-100 even:bg-green-100">item 1</li>
		<li class="odd:bg-orange-100 even:bg-green-100">item 2</li>
		<li class="odd:bg-orange-100 even:bg-green-100">item 3</li>
		<li class="odd:bg-orange-100 even:bg-green-100">item 4</li>
		<li class="odd:bg-orange-100 even:bg-green-100">item 5</li>
		<li class="odd:bg-orange-100 even:bg-green-100">item 6</li>
	</ul>
	<br />

	<!-- Appearance -->
	<!-- Use appearance-none to reset any browser specific styling on an element. This utility is often used when creating custom form components. -->
	<select name="" id="" class="appearance-none">
		<option value="yes">Yes</option>
		<option value="no">No</option>
	</select>
	<br />

	<!-- Cursor -->
	<div>
		<button
			class="cursor-pointer rounded-lg bg-black px-4 py-2 text-white focus:bg-red-300 focus:text-white"
			>Submit</button
		>
	</div>

	<!-- Resize -->

	<!-- User Select -->
	<div class="select-none">Lorem ipsum dolor sit amet.</div>
	<div class="select-all">Lorem ipsum dolor sit amet.</div>
	<div class="select-text">Lorem ipsum dolor sit amet.</div>
	<div class="select-auto">Lorem ipsum dolor sit amet.</div>
	<br />
	<!-- Smooth Scroll Example -->
	<a href="#item" class="block text-blue-500 underline">Go to #Item</a>
	<div>
		Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos ratione odit, consequatur
		deleniti, excepturi explicabo debitis quia placeat, maxime assumenda laborum incidunt. Ab
		reprehenderit ducimus tenetur quae beatae, impedit sunt illum qui dolorum? Aliquid officia
		ratione corporis nisi quia quam labore nulla voluptatum? Optio distinctio laborum vero, quae
		ratione rem tempore asperiores, ipsa nam debitis rerum harum? Corporis adipisci rem vel, facilis
		laborum tempora dolorum optio possimus maxime nobis modi itaque velit sit sunt quidem nisi
		officia reprehenderit porro eum quae hic et dolores ipsum suscipit. Provident enim vero odio
		aliquid, porro laudantium nam cum hic doloribus suscipit earum ipsam quibusdam doloremque.
		Accusamus similique porro dolor sit hic sequi asperiores cum natus repellat, molestiae
		consectetur aliquam obcaecati voluptatum iusto quibusdam nesciunt odio maiores architecto illum
		excepturi recusandae non ipsa ea labore! Recusandae assumenda doloribus pariatur! Impedit culpa
		consequatur mollitia fugit excepturi quia sed, voluptates cupiditate suscipit explicabo, ad ex
		corrupti harum vero? Officiis quia nam error quas. Odio perferendis doloremque quos quas, qui
		nemo eos delectus, iusto saepe aliquam explicabo non repudiandae ea ipsam enim praesentium
		voluptas laudantium temporibus. Illo accusamus vero nulla nemo in pariatur quae sapiente, libero
		quis recusandae, cum tenetur sit vitae, odio reiciendis omnis explicabo voluptatum. Ipsa, cum?
		Blanditiis provident commodi obcaecati magni eveniet deleniti alias, magnam cum consectetur!
		Sunt expedita sit perferendis. Similique id libero dolorum omnis perspiciatis aut! Illum
		veritatis nesciunt sequi non recusandae aliquam explicabo consectetur id aliquid laborum totam
		eaque assumenda pariatur accusantium voluptatum corporis, velit culpa earum, dignissimos eveniet
		iure quidem itaque cum. Perspiciatis quisquam eveniet ea! Rem tempore distinctio quod nam
		tenetur et accusamus! Itaque ipsam ducimus facere nulla in. Nam ratione dolores dolore hic
		mollitia architecto dignissimos consectetur facilis unde fuga quod veniam neque id, repellendus
		eius eum possimus animi sapiente saepe, rem voluptatem voluptates nihil, quibusdam voluptatibus.
		Blanditiis.
	</div>
	<br />
	<div id="item">
		<p>
			<strong>Item</strong>
		</p>
		Lorem ipsum dolor sit amet, consectetur adipisicing elit. Rerum quibusdam, quisquam natus at minima
		odit! Commodi atque necessitatibus laudantium. Debitis, laudantium possimus. Voluptas, quo unde pariatur
		nihil voluptatem enim tenetur.
	</div>
</div>

<style>
	:global(html) {
		scroll-behavior: smooth;
	}
</style>

<!-- Cursor
  cursor-auto	          cursor: auto;
  cursor-default	      cursor: default;
  cursor-pointer	      cursor: pointer;
  cursor-wait	          cursor: wait;
  cursor-text	          cursor: text;
  cursor-move	          cursor: move;
  cursor-help	          cursor: help;
  cursor-not-allowed	  cursor: not-allowed;
  cursor-none	          cursor: none;
  cursor-context-menu	  cursor: context-menu;
  cursor-progress	      cursor: progress;
  cursor-cell	          cursor: cell;
  cursor-crosshair	    cursor: crosshair;
  cursor-vertical-text	cursor: vertical-text;
  cursor-alias	        cursor: alias;
  cursor-copy	          cursor: copy;
  cursor-no-drop	      cursor: no-drop;
  cursor-grab	          cursor: grab;
  cursor-grabbing	      cursor: grabbing;
  cursor-all-scroll	    cursor: all-scroll;
  cursor-col-resize	    cursor: col-resize;
  cursor-row-resize	    cursor: row-resize;
  cursor-n-resize	      cursor: n-resize;
  cursor-e-resize	      cursor: e-resize;
  cursor-s-resize	      cursor: s-resize;
  cursor-w-resize	      cursor: w-resize;
  cursor-ne-resize	    cursor: ne-resize;
  cursor-nw-resize	    cursor: nw-resize;
  cursor-se-resize	    cursor: se-resize;
  cursor-sw-resize	    cursor: sw-resize;
  cursor-ew-resize	    cursor: ew-resize;
  cursor-ns-resize	    cursor: ns-resize;
  cursor-nesw-resize	  cursor: nesw-resize;
  cursor-nwse-resize	  cursor: nwse-resize;
  cursor-zoom-in	      cursor: zoom-in;
  cursor-zoom-out	      cursor: zoom-out;
-->

