<template>
<div class="header">
	<div class="container">
	<!-- Login Logo -->
	<img src="@/assets/images/login-logo.png" alt="login-logo" class="txt" >
	<!-- Available Credit Text -->
	<div class="float-right pt-2">Available Credit:3,21,457
	 <button class="btn btn-secondary dropdown-toggle float-right" type="button" id="dropdownMenuButton" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
</button>
</div>
</div>
</div>
</template>

<script>
export default {};
</script>
<style lang="scss" scoped>
.header {
	background-color: white;
	text-decoration-color: black;
}
.txt {
	float: center;
	margin: center;
	max-width: 250px;
	padding-left: 125px;
	text-decoration-color: black;
}

.btn-secondary {
	color: black;
	background-color: transparent;
	border-color: transparent;
	padding-top: 2px;
}
</style>

