<script>
	let cats = [
		{ id: 'DYzT-Pk6Ogw&ab_channel=RaShaunGrey', name: 'Robert, it goes down' },
		{ id: 'q6EoRBvdVPQ&ab_channel=revergo', name: 'Yee' },
		{ id: 'D-UmfqFjpl0&ab_channel=Joe', name: 'Dog of wisdom' },
		{ id: 'oHg5SJYRHA0&ab_channel=cotter548', name: 'PLAYSTATION 5 LEAK!!?!' },
		{ id: 'DcrrUuRoWT4&ab_channel=socdoneleft', name: 'Life gud' }
		
	];
</script>

<body>
	<main>
		
			<h1>Videos mas infames de youtube</h1>
		<h2>No te los pudes perdes</h2>
	
		<ul>
			{#each cats as { id, name }, i}
				<li><a target="_blank" href="https://www.youtube.com/watch?v={id}" rel="noreferrer">
					{i + 1}: {name}
				</a></li>
			{/each}
		</ul>
		 
		<h3>Miralos bajo tu propia discrecion</h3>
		<img src="https://media.giphy.com/media/eaECZB7V6GACc/giphy.gif" alt="omero loco">
	</main>
</body>


  
  <style>
	main {
	  text-align: center;
	  padding: 1em;
	  max-width: 240px;
	  margin: 0 auto;
	}
  
	h1 {
	  color: #ff0000;
	  text-transform: uppercase;
	  font-size: 5em;
	  font-weight: 100;
	}

	body {
    background-image: url('https://images.unsplash.com/photo-1553152531-b98a2fc8d3bf?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1631&q=80');
    background-size: cover;
    background-position: center;
  }
  
	@media (min-width: 640px) {
	  main {
		max-width: none;
	  }
	}
  </style>