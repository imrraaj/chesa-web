<script>
	import EventCard from './eventCard.svelte';

	import data from './data';
</script>

<section class="text-gray-600 body-font">
	<div class="container px-5 py-24 mx-auto">
		<div class="flex flex-col text-center w-full mb-20">
			<h1 class="text-5xl font-black title-font mb-4 text-gray-900">Events at a glance</h1>
		</div>

		<div class="flex flex-wrap">
			{#each data as member}
				<EventCard {...member} />
			{/each}
		</div>
	</div>
</section>
