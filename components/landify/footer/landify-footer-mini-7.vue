<template>
	<div class=" bg-black text-white">
		<landify-block-template class="flex flex-col h-64 pt-12">
			<landify-icon :reverse="true" class="mb-8" />
			<div class="justify-self-center self-center space-x-6 mb-12">
				<n-link tag="a" :to="'/'">
					About
				</n-link>
				<n-link tag="a" :to="'/'">
					Services
				</n-link>
				<n-link tag="a" :to="'/'">
					Blog
				</n-link>
				<n-link tag="a" :to="'/'">
					Jobs
				</n-link>
				<n-link tag="a" :to="'/'">
					Contact
				</n-link>
			</div>
			<div class="divider bg-gray-500 opacity-20 mb-6" />
			<div class="flex justify-between">
				<span class="text-gray-300">© 2020 Landify UI Kit. All rights reserved</span>
				<landify-social-icon />
			</div>
		</landify-block-template>
	</div>
</template>

<script lang="ts">
import { Vue, Component } from 'nuxt-property-decorator';

@Component
export default class LandifyFooterMini7 extends Vue {}
</script>

<style lang="scss" scoped>
.divider {
	height: 1px;
}
</style>
