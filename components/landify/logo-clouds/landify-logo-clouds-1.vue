<template>
	<landify-block-template class="border-b border-t gap-16 my-4 grid grid-cols-6 lg:py-6 lg:px-24">
		<img src="@/assets/images/svg/airbnb.svg" alt="airbnb">
		<img src="@/assets/images/svg/hubspot.svg" alt="hubspot">
		<img src="@/assets/images/svg/google.svg" alt="google">
		<img src="@/assets/images/svg/microsoft.svg" alt="microsoft">
		<img src="@/assets/images/svg/walmart.svg" alt="walmart">
		<img src="@/assets/images/svg/fedex.svg" alt="fedex">
	</landify-block-template>
</template>

<script lang="ts">
import { Vue, Component } from 'nuxt-property-decorator';

@Component
export default class LandifyLogoCloud1 extends Vue {}
</script>
