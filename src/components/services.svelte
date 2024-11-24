<script>
	import { ArrowUpRight, ChartNetwork, Triangle } from 'lucide-svelte';
</script>

<div class="container mx-auto pb-10 md:flex">
	<!-- LEFT COL -->
	<div>
		<div class="flex items-center">
			<button class="flex h-12 w-12 items-center justify-center rounded-full bg-white">
				<span class="rotate-90 text-black">
					<Triangle fill="black" size="12" />
				</span>
			</button>
			<div class="p-1 text-sm font-extralight ml-2">
				<p class="">Let's See</p>
				<p class="">How We Did It</p>
			</div>
		</div>

		<!-- Services -->
		<div class="my-4 space-y-2 text-xs font-extralight">
			<div class="inline-block rounded-full border border-gray-700 px-6 py-2">WEB ANALYTICS</div>
			<div class="inline-block rounded-full border border-gray-700 px-6 py-2">EMAIL MARKETING</div>
			<br />
			<div class="inline-block rounded-full border border-gray-700 px-6 py-2">SEO 2.0</div>
		</div>
	</div>


	<!-- RIGHT COL -->
	<div class="container grid gap-2 text-black md:grid-cols-3">
		<!-- Unique Business Solutions -->
		<div
			class="flex aspect-square flex-col justify-between rounded-3xl bg-[#FD5E08] p-4 text-xs font-extralight h-48 w-full"
		>
			<div class="mb-auto">
				<p class="font-medium">UNIQUE</p>
				<p class="font-medium">BUSINESS SOLUTIONS</p>
			</div>
			<div class="text-end text-4xl flex">
				<ChartNetwork size="48" class="flex-end"/>️
			</div>
		</div>

		<!-- Case Studies -->
		<div
			class="flex aspect-square flex-col justify-between rounded-3xl bg-[#E1E1E0] p-5 text-black h-48 w-full"
		>
			<div class="self-end font-extralight">
				<ArrowUpRight size="48" strokeWidth={0.6} />
			</div>
			<div class="flex">
			<p class="flex-end font-semibold text-2xl leading-7">OUR CASE STUDIES</p>
			</div>
		</div>

		<!-- Successful Projects -->
		<div
			class="flex aspect-square flex-col justify-between rounded-3xl bg-[#FCC859] p-5 text-black h-48 w-full"
		>
			<p class="font-medium">SUCCESSFUL<br />PROJECTS</p>
			<div class="flex">
			<p class="flex-end text-6xl font-medium">700<sup>+</sup></p>
			</div>
		</div>
	</div>
</div>
