<script>
	import Header from "$lib/components/Header.svelte";
	import Navigation from "$lib/components/Navigation.svelte";
	import "$lib/styles/styles.css";

	const topMatter = {
		description: "worked examples",
		courseModule: "A selection", // statics, strength, fluids
		course: "home",
	};
</script>

<Header {topMatter} />
<Navigation />
