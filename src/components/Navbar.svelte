<script>
	import logo from '$lib/assets/img/logo.png';
	import Row from '../components/Row.svelte';
</script>

<div class="row">
	<Row>
		<img src={logo} alt="EasyDry" class="logo" />
		<p class="brandName">EasyDry</p>
	</Row>
</div>

<style>
	.logo {
		width: 50px;
		height: 50px;
	}
	.brandName {
		font-size: 2.5rem;
		font-weight: 500;
		font-family: var(--font-mono);
		color: var(--primary-color);
	}
	.row {
		background-color: var(--tertiary-color);
	}
</style>
