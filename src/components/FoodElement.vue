<template>
    <div class="card shadow-1">
  	  	<img :src="foodElement.imageUrl"
  	  	 width="198" height="180">
  	  	<div class="card-content">
  	  		<h1 class="text-primary">{{ foodElement.name }}</h1>
  	  		<p>{{ foodElement.description }}</p>
  	  		<p>
	  	  		<small>
	  	  			<b>Delicousness:</b>
	  	  		</small>
	  	  		<b class="text-primary">
		  	  		{{ foodElement.deliciousness }}
	  	  		</b>
  	  		</p>
  	  	</div>
    </div>
</template>

<script>
export default {
    props: ['foodElement']
}
</script>

<style scoped>

</style>