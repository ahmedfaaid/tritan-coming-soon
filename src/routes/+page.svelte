<section class="landing">
	<div class="landing-inner">
		<div class="content">
			<img src="/transparent-triangle-logo-2.png" alt="Tritan Logo" class="logo" />
			<h1>Tritan Group</h1>
			<p>Our website is currently undergoing scheduled maintenance. We should be back shortly.</p>
			<p>Thank you for your patience.</p>
		</div>
	</div>
</section>

<style>
	.logo {
		width: 30%;
	}

	.landing-inner {
		position: absolute;
		top: 0;
		left: 0;
		width: 100%;
		height: 100%;
		display: flex;
		align-items: center;
		justify-content: center;
		background: rgba(0, 0, 0, 0.7);
		text-align: center;
	}

	.content {
		width: 40%;
	}

	.landing {
		position: relative;
		background-image: url('/scott-graham-5fNmWej4tAA-unsplash.jpg');
		background-size: cover;
		background-position: center;
		height: 100vh;
	}

	.landing h1 {
		font-size: 50px;
	}

	.landing p {
		font-size: 20px;
	}

	@media (max-width: 650px) {
		.landing img {
			width: 70%;
		}

		.landing h1 {
			font-size: 40px;
		}
	}

	@media (max-width: 4250px) {
		.content {
			width: 80%;
		}
	}

	@media (max-height: 600px) {
		img {
			width: 20%;
		}

		p {
			display: none;
		}
	}

	@media (max-height: 400px) {
		img {
			padding-bottom: 30px;
		}

		h1 {
			display: none;
		}
	}
</style>
