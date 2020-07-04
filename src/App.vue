<template>
	<div id="app">
    <SignIn />
	</div>
</template>

<script>
import SignIn from './components/SingIn'

export default {
	name: 'app',
	components: {
		SignIn
	}
}
</script>

<style>
	body {
		margin: 0;
		padding: 0;
		font-family: 'Roboto Condensed', sans-serif;

	}
	#app {
		font-family: Tahoma;
		font-size: 1.6rem;
		color: #222;
		background-color: #ccc;
		height: 100vh;
		display: flex;
		justify-content: center;
		align-items: center;
		font-family: 'Roboto Condensed', sans-serif;

	}
</style>
