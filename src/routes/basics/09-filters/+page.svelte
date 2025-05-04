<script>
	import img1 from '$lib/img/img1.jpg';
	import img2 from '$lib/img/img2.jpg';
	import img3 from '$lib/img/img3.jpg';
	import img4 from '$lib/img/img4.jpg';
	import img5 from '$lib/img/img5.jpg';
	import img6 from '$lib/img/img6.jpg';
	import img7 from '$lib/img/img7.jpg';
</script>

<svelte:head>
	<title>Filters</title>
</svelte:head>

<!-- Blur -->
<div class="blur-sm">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Tempora, enim.</div>
<br />
<div class="blur">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Tempora, enim.</div>
<br />
<!-- svelte-ignore a11y_img_redundant_alt -->
<img src={img1} alt="image 1" class="blur-sm" />
<br />

<!-- Brightness -->
<!-- svelte-ignore a11y_img_redundant_alt -->
<img src={img2} alt="image 2" class="brightness-50" />
<br />
<!-- svelte-ignore a11y_img_redundant_alt -->
<img src={img2} alt="image 2" class="brightness-75" />
<br />
<!-- svelte-ignore a11y_img_redundant_alt -->
<img src={img2} alt="image 2" class="brightness-100" />
<br />
<!-- svelte-ignore a11y_img_redundant_alt -->
<img src={img2} alt="image 2" class="brightness-150" />
<br />
<!-- svelte-ignore a11y_img_redundant_alt -->
<img src={img2} alt="image 2" class="brightness-200" />
<br />

<!-- Contrast -->
<!-- svelte-ignore a11y_img_redundant_alt -->
<img src={img3} alt="image 3" class="contrast-0" />
<br />
<!-- svelte-ignore a11y_img_redundant_alt -->
<img src={img3} alt="image 3" class="contrast-50" />
<br />
<!-- svelte-ignore a11y_img_redundant_alt -->
<img src={img3} alt="image 3" class="contrast-75" />
<br />
<!-- svelte-ignore a11y_img_redundant_alt -->
<img src={img3} alt="image 3" class="contrast-100" />
<br />
<!-- svelte-ignore a11y_img_redundant_alt -->
<img src={img3} alt="image 3" class="contrast-150" />
<br />
<!-- svelte-ignore a11y_img_redundant_alt -->
<img src={img3} alt="image 3" class="contrast-200" />
<br />

<!-- Grayscale -->
<!-- svelte-ignore a11y_img_redundant_alt -->
<img src={img4} alt="image 4" class="grayscale-0" />
<br />
<!-- svelte-ignore a11y_img_redundant_alt -->
<img src={img4} alt="image 4" class="grayscale-25" />
<br />
<!-- svelte-ignore a11y_img_redundant_alt -->
<img src={img4} alt="image 4" class="grayscale-50" />
<br />
<!-- svelte-ignore a11y_img_redundant_alt -->
<img src={img4} alt="image 4" class="grayscale-75" />
<br />
<!-- svelte-ignore a11y_img_redundant_alt -->
<img src={img4} alt="image 4" class="grayscale-100" />
<br />

<!-- Invert -->
<!-- svelte-ignore a11y_img_redundant_alt -->
<img src={img5} alt="image 5" class="invert-50" />
<br />
<!-- svelte-ignore a11y_img_redundant_alt -->
<img src={img5} alt="image 5" class="invert-100" />
<br />

<!-- Sepia -->
<!-- svelte-ignore a11y_img_redundant_alt -->
<img src={img6} alt="image 6" class="sepia-50" />
<br />
<!-- svelte-ignore a11y_img_redundant_alt -->
<img src={img6} alt="image 6" class="sepia-100" />
<br />

<!-- Hue Rotate -->
<!-- svelte-ignore a11y_img_redundant_alt -->
<img src={img7} alt="image 7" class="hue-rotate-30" />
<br />
<!-- svelte-ignore a11y_img_redundant_alt -->
<img src={img7} alt="image 7" class="hue-rotate-90" />
<br />

<!-- Blur
  blur-none	    filter: blur(0);
  blur-sm	      filter: blur(4px);
  blur	        filter: blur(8px);
  blur-md	      filter: blur(12px);
  blur-lg	      filter: blur(16px);
  blur-xl	      filter: blur(24px);
  blur-2xl	    filter: blur(40px);
  blur-3xl	    filter: blur(64px);
-->

<!-- Brightness
  brightness-0	    filter: brightness(0);
  brightness-50	    filter: brightness(.5);
  brightness-75	    filter: brightness(.75);
  brightness-90	    filter: brightness(.9);
  brightness-95	    filter: brightness(.95);
  brightness-100	  filter: brightness(1);
  brightness-105	  filter: brightness(1.05);
  brightness-110	  filter: brightness(1.1);
  brightness-125	  filter: brightness(1.25);
  brightness-150	  filter: brightness(1.5);
  brightness-200	  filter: brightness(2);
-->

<!-- Contrast
  contrast-0	  filter: contrast(0);
  contrast-50	  filter: contrast(.5);
  contrast-75	  filter: contrast(.75);
  contrast-100	filter: contrast(1);
  contrast-125	filter: contrast(1.25);
  contrast-150	filter: contrast(1.5);
  contrast-200	filter: contrast(2);
-->

<!-- Hue Rotate
  hue-rotate-0	    filter: hue-rotate(0deg);
  hue-rotate-15	    filter: hue-rotate(15deg);
  hue-rotate-30	    filter: hue-rotate(30deg);
  hue-rotate-60	    filter: hue-rotate(60deg);
  hue-rotate-90	    filter: hue-rotate(90deg);
  hue-rotate-180	  filter: hue-rotate(180deg);
-->
