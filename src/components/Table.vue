<template>
	<div class="panel inset">
		<table>
			<tr>
				<th>id</th>
				<th>姓名</th>
				<th>年龄</th>
			</tr>
		</table>
	</div>
</template>

<script>
	export default {
	  name: 'table'
	}
</script>

<style scoped>
	.panel{
		background-color:#fff;
		box-shadow:0 0 5px rgba(0,0,0,.6);
		padding:10px 20px;
		padding-top:0px;
	}
	.panel.inset{
		margin:10px 20px;
	}
</style>