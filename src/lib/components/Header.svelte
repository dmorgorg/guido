<script>
	export let topMatter;
	$: tm = topMatter;
</script>

<header>
	<!-- {#if tm.course === 'home'} -->
		<div class="left">
			<h3>{tm.description} :: </h3>
			<h3>{tm.courseModule} </h3>
		</div>
	<!-- {:else} -->
		<!-- <h3><a href="/">{tm.description}</a></h3>
		<h3><a href="/{tm.course}">{tm.course}</a></h3> -->
	<!-- {/if} -->
	<!-- <div class="left">
		<h3><a href="/">{topMatter.description} :: </a></h3>
		{#if topMatter.course == 'home'}
			<h3>{topMatter.courseModule}</h3>
		{:else}
			<h3><a href="/{topMatter.course}">{topMatter.course}</a></h3>
		{/if}
	</div>
	{#if topMatter.course == 'home'}
		<h3 class="classModule">Contents</h3>
	{:else}
		<h3 class="classModule">{topMatter.courseModule}</h3>
	{/if} -->
</header>


<style>
	header {
		background: var(--primary-grey);
		box-shadow: -0.25px 5px 15px 0px rgba(0, 0, 0, 0.5);
		display: flex;
		font-size: 150%;
		justify-content: space-between;
		margin-bottom: 1em;
		padding: 1rem 2rem;
		text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.75);
		color: var(--dark-grey);
	}
	h3 {
		display: inline-block;
		text-transform: capitalize;
		letter-spacing: 0.05rem;
		margin: 0;
	}
	/* a {
		color: inherit;
		text-decoration: none;
	} */
	.left {
		margin-right: 2em;
	}
	.classModule {
		text-align: right;
	}
</style>