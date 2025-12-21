<script>
	import ardian from '$lib/assets/ARDIAN.png';
	import ibnFadl from '$lib/assets/IBN FADL.png';
	import icon from '$lib/assets/icon.svg';
</script>

<div class="flex min-h-screen items-center justify-center bg-white p-4 sm:p-8">
	<div class="flex flex-col items-center gap-4 sm:gap-6 md:flex-row md:gap-8">
		<!-- Left Image -->
		<img
			src={ardian}
			alt="Ardian"
			class="h-8 w-auto object-contain sm:h-10 md:h-12 lg:h-14"
		/>

		<!-- Center Icon (Spinning) -->
		<img
			src={icon}
			alt="Icon"
			class="h-12 w-12 animate-spin object-contain [animation-duration:32s] sm:h-16 sm:w-16 md:h-20 md:w-20 lg:h-24 lg:w-24"
		/>

		<!-- Right Image -->
		<img
			src={ibnFadl}
			alt="Ibn Fadl"
			class="h-8 w-auto object-contain sm:h-10 md:h-12 lg:h-14"
		/>
	</div>
</div>
