<template>
	<section class="text-gray-600 body-font bg-black" style="z-index: 1;">
		<div
			class="container mx-auto flex px-5 py-24 md:flex-row flex-col items-center"
		>
			<div
				class="lg:flex-grow md:w-1/3 lg:pr-6 md:pr-16 flex flex-col md:items-start md:text-left mb-16 md:mb-0 items-start text-left"
			>
				<h1 class="title-font sm:text-4xl text-3xl font-medium ab-show text-left">
					About the show
				</h1>
				<div class="flex justify-start" style="width: 457px; margin-left: -15px;">
					<div class="text-border m-4"><span class="bar"></span></div>
				</div>
				<p class="mb-8 leading-relaxed w-64 about-show-text">
					So they stick around, kicking out feedback and I entertain it as if I
					need that I had a talk with my uncle and he agreed that my privacy
					about the only thing I need back as if I need that I had a talk with
					my uncle and he agreed that my privacy about the only thing.
				</p>
			</div>
			<h1 class="big-text-about">
				About the show
			</h1>
			<div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6">
				<img
					class="object-cover object-center rounded"
					alt="hero"
					src="../assets/img/Picture.png"
				/>
			</div>
		</div>
	</section>
</template>
<script>
export default {
	name: 'AbouTheShow',
	components: {
		//HelloWorld
	}
};
</script>
<style scoped>
.ab-show {
	font-size: 80px;
	font-weight: 600;
	line-height: 66px;
	text-align: left;
	letter-spacing: -3px;
	color: #ffffff;
	z-index: 1;
	width: 457px;
	height: 160px;
}
.about-show-text {
	text-align: left;
	font-weight: 500;
	line-height: 30px;
	font-size: 20px;
	letter-spacing: 0px;
	color: #cccccc;
	opacity: 1;
	z-index: 1;
	width: 457px;
}
.big-text-about {
	position: relative;
	top: -80px;
	left: -520px;
	font-family: 'Open Sans';
	font-size: 200px;
	line-height: 156px;
	width: 772px;
	height: 468px;
	opacity: 1;
	z-index: 0;
	text-align: left;
	letter-spacing: -9.72px;
	color: #232323;
	opacity: 1;
}
.text-border {
	height: 4px;
	display: block;
	position: static;
	width: 242px;
	background: #5cd0fe 0% 0% no-repeat padding-box;
	z-index: 1;
}
.text-border span {
	width: 100%;
	height: 4px;
	border-radius: 30px;
	background: #c0cad4;
	z-index: 1;
}
</style>
