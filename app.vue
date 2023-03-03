<template>
	<header>
		<h1>website</h1>
		<NuxtLink class="header" to="/">home</NuxtLink>
		<NuxtLink class="header" to="/contact">contact</NuxtLink>
		<NuxtLink class="header" to="/articles">articles</NuxtLink>
	</header>

	<NuxtPage/>

	<footer>
		<div>© Tobias Kyselica</div>
	</footer>
</template>

<style>
	h1 {
		font-family: monospace;
		font-size: 40px;
		margin-top: 5px;
		margin-bottom: 10px;
	}

  h2 {
	  font-family: monospace;
	  font-size: 25px;
  }

	a.header {
		color: white;
		background-color: green;
		margin-left: 2px;
		margin-right: 2px;
		padding: 10px 25px;
		text-decoration: none;
	}

	a.header:hover {
		background-color: blue;
	}

	footer {
	  position: fixed;
	  bottom: 0;
		background-color: beige;
		width: 100%;
		height: 35px;
		margin-left: -8px;
		text-align: center;
		padding-top: 15px;
	}
</style>