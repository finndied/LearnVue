<script setup>
import Card from './Card.vue'
</script>

<template>
	<div class="flex justify-evenly text-xl mx-auto mt-10 font-semibold">
		<div>
			<div class="p-1 w-64 text-center rounded-md bg-red-700">Важные</div>

			<Card />
		</div>

		<div>
			<div class="p-1 w-64 text-center rounded-md bg-amber-500">
				Менее важные
			</div>

			<Card />
		</div>

		<div>
			<div class="p-1 w-64 text-center rounded-md bg-lime-600">Мало важные</div>

			<Card />
		</div>
	</div>
</template>
