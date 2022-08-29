<script lang="ts">
	import '../app.css';
</script>

<div class="flex flex-col w-full min-h-screen gap-10 justify-center">
	<h1 class="text-3xl font-bold text-center">
		Template with Sveltekit and Tailwindcss in typescript
	</h1>
	<div class="justify-center flex w-full">
		<a class="relative items-center group" href="https://kit.svelte.dev">
			<span
				class="border absolute inset-0 w-full h-full transition duration-200 ease-out transform translate-x-1 translate-y-1 bg-orange-600 group-hover:-translate-x-0 group-hover:-translate-y-0"
			/>
			<span
				class="absolute inset-0 w-full h-full bg-white border-2 border-orange-600 group-hover:bg-orange-600"
			/>
			<h2 class="relative w-full p-3 text-orange-600 text-lg group-hover:text-orange-50">
				Read Sveltekit documentation
			</h2>
		</a>
	</div>

	<div class="justify-center flex w-full">
		<a class="relative items-center group" href="https://tailwindcss.com/docs/">
			<span
				class="border absolute inset-0 w-full h-full transition duration-200 ease-out transform translate-x-1 translate-y-1 bg-sky-500 group-hover:-translate-x-0 group-hover:-translate-y-0"
			/>
			<span
				class="absolute inset-0 w-full h-full bg-white border-2 border-sky-500 group-hover:bg-sky-500"
			/>
			<h2 class="relative w-full p-3 text-sky-500 text-lg group-hover:text-sky-50">
				Read Tailwind documentation
			</h2>
		</a>
	</div>
</div>
