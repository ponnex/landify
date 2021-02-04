<template>
	<div class="hero-bg">
		<landify-block-template class="flex flex-col">
			<landify-header-3 />
			<div class="flex justify-between mb-5 mt-20">
				<div class="mt-24">
					<span class="block font-extrabold text-gray-900 text-7xl mb-8 leading-snug">
						Organise projects.<br>
						Get more done.
					</span>
					<button class="block rounded-lg bg-purple-600 font-bold text-white py-4 px-10 text-xl">
						Get Started
					</button>
				</div>
				<img src="@/assets/images/phone-mockup.png" alt="phone-mockup" class="-mr-12">
			</div>
		</landify-block-template>
	</div>
</template>

<script lang="ts">
import { Vue, Component } from 'nuxt-property-decorator';

@Component
export default class LandifyHero3 extends Vue {}
</script>
