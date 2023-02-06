<script>
  export let params
</script>

<div class="container-fluid hero-header bg-light py-5 mb-5">
  <div class="container py-5">
    <div class="row g-5 align-items-center">
      <slot />
      <div class="col-lg-6 animated fadeIn">
        <img
          class="img-fluid animated pulse infinite"
          style="animation-duration: 3s;"
          src={params.image}
          alt=""
        />
      </div>
    </div>
  </div>
</div>
