<template>
	<Navbar />
	<section class="flex flex-col items-center mt-20">
		<!-- Info  -->
		<div class="mb-6 text-center">
			<div class="space-y-1">
				<span class="text-[#f56300]">New</span>
				<h2 class="text-[32px] font-medium">iMac</h2>
				<p class="text-[21px] font-medium">Say hello.</p>
				<p class="text-[17px] font-medium">From $1299</p>
			</div>
			<div class="flex flex-col items-center space-y-3 mt-4">
				<a
					class="
						bg-[#0071e3]
						w-16
						text-center text-white
						px-4
						py-2
						rounded-full
					"
					href="#"
					>Buy</a
				>
				<a class="text-[#06c]" href="#"
					><span class="hover:underline">Learn more</span> &gt;</a
				>
			</div>
		</div>

		<!-- Image  -->
		<div class="md:hidden">
			<img
				src="https://www.apple.com/v/mac/home/bi/images/overview/hero_imac_24__eq5phrdpwjyq_small.jpg"
				alt=""
			/>
		</div>
		<div class="hidden md:block">
			<img
				src="https://www.apple.com/v/mac/home/bi/images/overview/hero_imac_24__eq5phrdpwjyq_large.jpg"
				alt=""
			/>
		</div>
	</section>
</template>

<script setup>
import Navbar from './components/Navbar.vue';
</script>
