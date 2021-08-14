<template>
	<nav class="bg-[#3a3a3a]">
		<div
			class="
				max-w-7xl
				mx-auto
				flex
				items-center
				justify-between
				px-3
				space-x-10
			"
		>
			<div class="md:hidden">
				<svg
					xmlns="http://www.w3.org/2000/svg"
					class="icon"
					fill="none"
					viewBox="0 0 24 24"
					stroke="currentColor"
				>
					<path
						stroke-linecap="round"
						stroke-linejoin="round"
						stroke-width="2"
						d="M4 8h16M4 16h16"
					/>
				</svg>
			</div>
			<div>
				<img
					src="https://www.apple.com/ac/globalnav/6/en_US/images/be15095f-5a20-57d0-ad14-cf4c638e223a/globalnav_apple_image__cxwwnrj0urau_large.svg"
					alt="Apple Logo"
				/>
			</div>
			<div class="hidden md:flex flex-grow justify-between">
				<a class="link" href="#">Store</a>
				<a class="link" href="#">Mac</a>
				<a class="link" href="#">iPad</a>
				<a class="link" href="#">iPhone</a>
				<a class="link" href="#">Watch</a>
				<a class="link" href="#">TV</a>
				<a class="link" href="#">Music</a>
				<a class="link" href="#">Support</a>
			</div>
			<div class="hidden md:block">
				<svg
					xmlns="http://www.w3.org/2000/svg"
					class="icon"
					fill="none"
					viewBox="0 0 24 24"
					stroke="currentColor"
				>
					<path
						stroke-linecap="round"
						stroke-linejoin="round"
						stroke-width="2"
						d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"
					/>
				</svg>
			</div>
			<div>
				<svg
					xmlns="http://www.w3.org/2000/svg"
					class="icon"
					fill="none"
					viewBox="0 0 24 24"
					stroke="currentColor"
				>
					<path
						stroke-linecap="round"
						stroke-linejoin="round"
						stroke-width="2"
						d="M16 11V7a4 4 0 00-8 0v4M5 9h14l1 12H4L5 9z"
					/>
				</svg>
			</div>
		</div>
	</nav>
</template>
