<ul>
    
	<li class='fluids'>
		<a href="/fluids">Fluids</a>
		<div>
			<a href="/fluids/01PressureMeasurement">01 Pressure Measurement</a>
			<a href="/fluids/03StaticFluids">03 Forces Due to Static Fluids</a>
			<a href="/fluids/12OpenChannel">12 Open Channel Flow</a>
			<!-- <a href="/fluids/12OpenChannel-I">12 Open Channel Flow I</a>
			<a href="/fluids/12OpenChannel-II">12 Open Channel Flow II</a> -->
		</div>
	</li>
	<li class="statics">
		<a href="/statics">Statics</a>
		<div>
			<a href="/statics/01MathReview">01 Math Review</a>
			<a href="/statics/09ComplexFrames">09 Complex Frames</a>
		</div>
	</li>
	<li class="strength">
		<a href="/strength">Strength</a>
		<div>
			<a href="/strength/01Stress">01 Stress</a>
			<a href="/strength/02Strain">02 Strain</a>
			<a href="/strength/04AxialDeformation-I">04 Axial Deformation I</a>
			<a href="/strength/04AxialDeformation-II">04 Axial Deformation II</a>
		</div>
	</li>
    <li class = "howTo"><a href="/howTo/01">How this site was built...</a></li>
</ul>

<style>
	ul {
		list-style: none;
	}
	li {
		display: block;
		padding: 1em;
		font-size: 1.5rem;
		text-decoration: none;
		font-weight: bold;
	}
	li a {
		text-decoration: none;
		color: inherit;
	}
	li div {
		margin-left: 2em;
		font-size: 1.125rem;
		display: flex;
		flex-wrap: wrap;
	}
	li div a {
		/* text-decoration: underline; */
		margin: 0.25rem 2rem 0.25rem 0;
		font-weight: normal;
		color: inherit;
	}
	li.fluids {
		color: var(--fluids-primary);
	}
	li.statics {
		color: var(--statics-primary);
	}
	li.strength {
		color: var(--strength-primary);
	}
    li.howTo {
        color: var(--dark-grey);
    }
	
</style>