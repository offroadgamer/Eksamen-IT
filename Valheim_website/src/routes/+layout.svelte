<script>

</script>

<div class="navbar-box">
	<div class="logo-box">
		<a href="./"><img src="./src/lib/images/valheim_logo.png" alt="valheim logo"></a>
	</div>
	<div class="links-box">
		<a class="navbar-link-item" href="./BUILDS">BUILDS</a>
		<a class="navbar-link-item" href="./ENEMIES">ENEMIES</a>
		<a class="navbar-link-item" href="./ABOUT">ABOUT</a>
	</div>
</div>

<style>
	.navbar-box {
		background-color: #4E4E4E;
		min-height: 100px;
		margin: 0px;
		padding: 10px;
		width: 100%;
		display: flex;
		flex-direction: row;
	}

	.logo-box {
		width: 40%;
	}

	img {
		width: 220px;
	}

	.links-box {
		width: 60%;
		display: flex;
		flex-direction: row;
		justify-content: space-evenly;
		align-items: center;
		margin-right: 60px;
	}

	.navbar-link-item {
		text-decoration: none;
		color: orange;	
		font-size: 25px;
	}
</style>

<slot />