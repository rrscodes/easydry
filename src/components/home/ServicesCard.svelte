<script>
	import Card from '../Card.svelte';
	import Row from '../Row.svelte';
	import DryCleaningImg from '$lib/assets/img/shirt.png';
	import LaundryImg from '$lib/assets/img/dryer.png';
	import WetCleaningImg from '$lib/assets/img/washbasin.png';
	import IroningImg from '$lib/assets/img/iron-board.png';
	import RoundedCard from '../RoundedCard.svelte';
	import Column from '../Column.svelte';
</script>

<div class="service-card">
	<Card>
		<div class="space-between">
			<Column>
				<RoundedCard>
					<img src={DryCleaningImg} alt="Dry Cleaning" class="service-img" />
				</RoundedCard>
				<p>Dry Cleaning</p>
			</Column>
			<Column>
				<RoundedCard>
					<img src={WetCleaningImg} alt="Wet Cleaning" class="service-img" />
				</RoundedCard>
				<p>Wet Cleaning</p>
			</Column>
			<Column>
				<RoundedCard>
					<img src={LaundryImg} alt="Laundry" class="service-img" />
				</RoundedCard>
				<p>Laundry</p>
			</Column>
			<Column>
				<RoundedCard>
					<img src={IroningImg} alt="Ironing" class="service-img" />
				</RoundedCard>
				<p>Ironing Clothes</p>
			</Column>
		</div>
		<div class="space-between">
			<Column>
				<RoundedCard>
					<img src={DryCleaningImg} alt="Dry Cleaning" class="service-img" />
				</RoundedCard>
				<p>Dry Cleaning</p>
			</Column>
			<Column>
				<RoundedCard>
					<img src={WetCleaningImg} alt="Wet Cleaning" class="service-img" />
				</RoundedCard>
				<p>Wet Cleaning</p>
			</Column>
			<Column>
				<RoundedCard>
					<img src={LaundryImg} alt="Laundry" class="service-img" />
				</RoundedCard>
				<p>Laundry</p>
			</Column>
			<Column>
				<RoundedCard>
					<img src={IroningImg} alt="Ironing" class="service-img" />
				</RoundedCard>
				<p>Ironing Clothes</p>
			</Column>
		</div>
	</Card>
</div>

<style>
	.service-card {
		width: 80vw;
		margin: 0 auto;
		margin-top: -15vh;
	}
	.service-img {
		width: 48px;
		height: 48px;
	}
	.space-between {
		display: flex;
		flex-direction: row;
		justify-content: space-evenly;
		padding-top: 20px;
		padding-bottom: 20px;
	}
	.space-between p {
		font-size: 20px;
		font-weight: 500;
		color: var(--heading-color);
	}
</style>
