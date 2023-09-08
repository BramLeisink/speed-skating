<script>
	export let race;
</script>

<div class="flex flex-wrap">
	<div class="overflow-x-auto w-96 m-4 rounded-lg border">
		<table class="table">
			<thead class="bg-base-200">
				<tr class="bg-base-300 italic">
					<th>{race[0]['startLane']}</th>
					<th
						>{race[0]['competitor']['skater']['firstName']}
						{race[0]['competitor']['skater']['lastName']}</th
					>
					<th>{race[0]['competitor']['skater']['country']}</th>
				</tr>
				<tr>
					<th>Lap</th>
					<th>Lap time</th>
					<th>Split time</th>
				</tr>
			</thead>
			<tbody>
				{#each race[0]['laps'] as lap (lap.number)}
					<tr>
						<th>{lap.number}</th>
						<td>{lap.time}</td>
						<td>{lap.passageTime}</td>
					</tr>
				{/each}
			</tbody>
		</table>
	</div>
	<div class="flex m-2">
		<div class="avatar m-2">
			<div
				class="w-20 h-20 rounded-full bg-white ring {race[0]['time'] > race[1]['time']
					? 'ring-red-600'
					: 'ring-green-600'}"
			>
				<img
					src={race[0]['competitor']['skater']['photo']}
					alt={race[0]['competitor']['identifier']}
				/>
			</div>
		</div>
		<div class="avatar m-2">
			<div
				class="w-20 h-20 rounded-full bg-white ring {race[1]['time'] > race[0]['time']
					? 'ring-red-600'
					: 'ring-green-600'}"
			>
				<img
					src={race[1]['competitor']['skater']['photo']}
					alt={race[1]['competitor']['identifier']}
				/>
			</div>
		</div>
	</div>
	<div class="overflow-x-auto w-96 m-4 rounded-lg border">
		<table class="table">
			<thead class="bg-base-200">
				<tr class="bg-base-300 italic">
					<th>{race[1]['startLane']}</th>
					<th
						>{race[1]['competitor']['skater']['firstName']}
						{race[1]['competitor']['skater']['lastName']}</th
					>
					<th>{race[1]['competitor']['skater']['country']}</th>
				</tr>
				<tr>
					<th>Lap</th>
					<th>Lap time</th>
					<th>Split time</th>
				</tr>
			</thead>
			<tbody>
				{#each race[1]['laps'] as lap (lap.number)}
					<tr>
						<th>{lap.number}</th>
						<td>{lap.time}</td>
						<td>{lap.passageTime}</td>
					</tr>
				{/each}
			</tbody>
		</table>
	</div>
</div>
