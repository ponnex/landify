<template>
	<div class="hero-bg dark:bg-black text-black dark:text-white">
		<div class="flex flex-col max-w-screen-lg mx-auto md:px-20 xl:px-0">
			<landify-header-3 />
			<div class="flex justify-between mb-5 mt-20">
				<div class="mt-24">
					<span class="block font-extrabold text-gray-900 text-6xl mb-8 leading-snug">
						Organise projects.<br>
						Get more done.
					</span>
					<button class="block rounded-lg bg-purple-600 font-bold text-white py-4 px-10 text-xl">
						Get Started
					</button>
				</div>
				<img src="@/assets/images/phone-mockup.png" alt="phone-mockup" class="-mr-12">
			</div>
			<logo-clouds-1 />
			<div class="h-20 mb-5 mt-20" />
		</div>
	</div>
</template>

<script lang="ts">
import { Vue, Component } from 'nuxt-property-decorator';

@Component
export default class IndexPage extends Vue {}
</script>

<style lang="scss" scoped>
.hero-bg {
	background-image: url('~assets/images/svg/hero-3.svg');
	background-repeat: no-repeat;
	background-position: right 0px top -50px;
}
</style>
