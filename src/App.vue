<template>
    <hero></hero>
    <last-episodes></last-episodes>
	<about-the-show></about-the-show>
</template>

<script>
import AboutTheShow from './components/AboutTheShow.vue';
import Hero from './components/Hero.vue'
import LastEpisodes from './components/LastEpisodes.vue'

export default {
	name: 'App',
	components: {
		Hero, 
		LastEpisodes,
		AboutTheShow, 
	}
};
</script>

<style>

</style>
