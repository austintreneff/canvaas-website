<script>
	import sc_store from '$lib/images/sc-store.jpg';
	import sc_carmen from '$lib/images/sc-carmen.jpg';
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section class="columns-2 gap-0">
	<div class="flex h-screen items-center justify-center bg-neutral-100">
		<h1 class="text-3xl font-bold">Hello Canvaas</h1>
	</div>
	<div class="relative flex h-screen items-center justify-center bg-white">
		<h1 class="text-3xl font-bold">Hello World</h1>
		<div class=" no-scrollbar absolute h-full w-full overflow-scroll">
			<div class="scroll-element relative my-16 flex h-1/4 w-full">
				<img class="absolute left-20 top-4 w-1/3" src={sc_store} alt="sole classics" />
				<img class="absolute left-2/3 top-20 w-1/5" src={sc_carmen} alt="sole classics" />
			</div>
			<div class="scroll-element relative my-16 flex h-1/4 w-full">
				<img class="absolute left-24 top-4 w-1/5" src={sc_store} alt="sole classics" />
				<img class="absolute left-2/4 top-1/4 w-1/3" src={sc_store} alt="sole classics" />
			</div>
			<div class="scroll-element relative my-16 flex h-1/4 w-full">
				<img class="absolute left-20 top-4 w-1/3" src={sc_carmen} alt="sole classics" />
				<img class="absolute left-2/3 top-20 w-1/5" src={sc_store} alt="sole classics" />
			</div>
			<div class="scroll-element relative my-16 flex h-1/4 w-full">
				<img class="absolute left-24 top-4 w-1/5" src={sc_store} alt="sole classics" />
				<img class="absolute left-2/4 top-1/4 w-1/3" src={sc_carmen} alt="sole classics" />
			</div>
			<div class="scroll-element relative my-16 flex h-1/4 w-full">
				<img class="absolute left-20 top-4 w-1/3" src={sc_store} alt="sole classics" />
				<img class="absolute left-2/3 top-20 w-1/5" src={sc_carmen} alt="sole classics" />
			</div>
			<div class="scroll-element relative my-16 flex h-1/4 w-full">
				<img class="absolute left-24 top-4 w-1/5" src={sc_store} alt="sole classics" />
				<img class="absolute left-2/4 top-1/4 w-1/3" src={sc_store} alt="sole classics" />
			</div>
			<div class="scroll-element relative my-16 flex h-1/4 w-full">
				<img class="absolute left-20 top-4 w-1/3" src={sc_carmen} alt="sole classics" />
				<img class="absolute left-2/3 top-20 w-1/5" src={sc_store} alt="sole classics" />
			</div>
			<div class="scroll-element relative my-16 flex h-1/4 w-full">
				<img class="absolute left-24 top-4 w-1/5" src={sc_store} alt="sole classics" />
				<img class="absolute left-2/4 top-1/4 w-1/3" src={sc_carmen} alt="sole classics" />
			</div>
			<div class="scroll-element relative my-16 flex h-1/4 w-full">
				<img class="absolute left-20 top-4 w-1/3" src={sc_store} alt="sole classics" />
				<img class="absolute left-2/3 top-20 w-1/5" src={sc_carmen} alt="sole classics" />
			</div>
			<div class="scroll-element relative my-16 flex h-1/4 w-full">
				<img class="absolute left-24 top-4 w-1/5" src={sc_carmen} alt="sole classics" />
				<img class="absolute left-2/4 top-1/4 w-1/3" src={sc_store} alt="sole classics" />
			</div>
		</div>
	</div>
</section>

<style>
	.no-scrollbar::-webkit-scrollbar {
		display: none;
	}

	/* Hide scrollbar for IE, Edge and Firefox */
	.no-scrollbar {
		-ms-overflow-style: none; /* IE and Edge */
		scrollbar-width: none; /* Firefox */
	}

	.scroll-element {
		animation: primary 15s linear infinite;
	}

	@keyframes primary {
		from {
			top: 0%;
		}
		to {
			top: -100%;
		}
	}
</style>
