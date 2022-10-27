<script>
	function validate() {
		console.log("I'm the validate() function")
	}
</script>

<form on:submit|preventDefault={validate}>
	<input>
	<button type="submit">
		Please save me
	</button>
</form>