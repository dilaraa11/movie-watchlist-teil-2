<script>
    let {data} = $props()
    
</script>

<div class="row mt-4">
  <!-- LINKS: Poster -->
  <div class="col-md-4">
    <img 
      src={data.movie.poster} 
      alt={data.movie.title} 
      class="img-fluid rounded"
    />
  </div>

  <!-- RECHTS: Text -->
  <div class="col-md-8">
    <h1>{data.movie.title}</h1>

    <p><strong>Jahr:</strong> {data.movie.year}</p>
    <p><strong>Dauer:</strong> {data.movie.length}</p>

    <a href="/movies" class="btn btn-secondary mt-3">
      Zurück zur Übersicht
      
    </a>
  </div>
</div>