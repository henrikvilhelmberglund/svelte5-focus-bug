<script>
	$effect(() => {
		document.querySelector("#myDiv button").focus();
	});

	// also works when using timeout
	// $effect(() => {
	// 	setTimeout(() => {
	// 		document.querySelector("#myDiv button").focus();
	// 	}, 0);
	// });
</script>

<button> A button </button>
