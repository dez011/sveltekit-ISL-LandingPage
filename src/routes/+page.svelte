<script lang="ts">
	import Carousel from '$lib/components/Carousel.svelte';
	import PrecisionBuiltCard from '$lib/components/PrecisionBuilt.svelte';
	import Hero from '$lib/components/Hero.svelte';
	import Mobile from '$lib/components/Mobile.svelte';
	import TheWhy from '$lib/components/TheWhy.svelte';
	import HeroCards from '$lib/components/HeroCards.svelte';
	import Links from '$lib/components/Links.svelte';
</script>

<div>
	<div class="">
		<div class="">
			<Hero />
		</div>

		<!-- <div class="w-full max-w-4xl mx-auto mt-5 lg:-mt-20 px-4 lg:px-0">
			<Carousel />
		</div> -->

	</div>
	<div class="w-full max-w-4xl mx-auto">
		<TheWhy />
		<PrecisionBuiltCard />

		<div class="my-10">
			<HeroCards />
		</div>

		<!-- <div class="my-10">
			<Mobile />
		</div> -->

		<div class="my-10">
			<Links />
		</div>
	</div>
</div>
