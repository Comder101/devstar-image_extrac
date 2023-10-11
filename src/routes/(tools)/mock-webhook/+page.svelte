<script lang="ts">
	import { Input, ButtonGroup, Label, Textarea, Helper } from 'flowbite-svelte';
	import CountrySelector from '$lib/CountrySelector.svelte';
	import Copy from '$lib/Copy.svelte';
	import Intro from '$lib/Intro.svelte';
	export let data;
</script>

<Intro heading={data.meta.title} description={data.meta.description} />

<section class="bg-white dark:bg-gray-900">
	<div class="py-8 px-4 mx-auto max-w-screen-xl lg:px-12">
		<div class="card gap-16 items-center mx-auto max-w-screen-xl overflow-hidden rounded-lg">
			<div class="p-8">
				Hello World
			</div>
		</div>
	</div>
</section>

<style>
	.card {
		box-shadow: rgba(0, 0, 0, 0.1) 0 0 0 2px;
	}

	:is(.dark .card) {
		box-shadow: rgba(255, 255, 255, 0.5) 0 0 0 2px;
	}
</style>
