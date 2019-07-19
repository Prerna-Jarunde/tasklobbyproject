<template>
  <div class="home">
  <div class="banner">
		<HeaderSection/>
		<SubHeader/>
		<cardImage/>
		</div>
</div>
</template>

<script>
import HeaderSection from '@/components/headerSection.vue';
import SubHeader from '@/components/subHeader.vue';
import cardImage from '@/components/cardImage.vue';

export default {
	name: 'mainPage',
	components: {
		HeaderSection,
		SubHeader,
		cardImage,
	},
};
</script>
<style lang="scss">
.banner {
	background-position: 100%;
	overflow: auto;
	background-image: url('../assets/images/background.jpg');
	background-size: cover;
	background-repeat: no-repeat;
	height: 100vh;
	width: 100%;
}
</style>
