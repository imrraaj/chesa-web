<script>
	export let name;
	export let image;
	export let position;
</script>

<div
	class="flex flex-col items-center bg-gray-50 border rounded-md shadow md:flex-row md:max-w-md hover:scale-110 transition-all"
>
	<img
		class="object-cover w-full rounded-t-lg h-96 md:h-auto md:w-48 md:rounded-none md:rounded-l-lg"
		src={image}
		alt={name}
	/>
	<div class="p-0 md:p-4 text-center my-4">
		<h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 text-center md:text-start">
			{name}
		</h5>
		<p class="mb-3 font-normal text-gray-700 dark:text-gray-400 text-center md:text-start">
			{position}
		</p>
	</div>
</div>
