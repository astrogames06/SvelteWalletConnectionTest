<script>
	import '../css/global.css'
	import '../lib/web3modal'
</script>

<div class="container">
	<w3m-button />
</div>

<style>
	.container {
		padding: 20px;
		height: 90px;
		text-align: center;

		display: flex;
		align-items: center;
		justify-content: space-around;
		gap: 100px;

		margin-bottom: 40px;

		font-size: 34px;
		font-weight: 600;
	}

	.container img {
		width: 80px;
		height: auto;
	}

	.btn img {
		width: 40px;
		height: auto;
	}
	.btn a {
		transition: all 0.2s ease;
	}

	.btn a:hover {
		transform: scale(1.1);
	}

	.btn {
		display: flex;
		align-items: center;
		justify-content: center;
		gap: 30px;
	}

	@media (max-width: 540px) {
		.container {
			gap: 0;
		}
		.btn {
			gap: 10px;
		}
	}
</style>
