<template>
	<div class="dark:bg-black text-black dark:text-white">
		<landify-hero-3 />
		<landify-logo-clouds-1 />
		<landify-feature-multiple-5 />
		<landify-testimonial-7 />
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
