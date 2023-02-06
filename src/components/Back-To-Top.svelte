<script>
  function scrollToTop(e) {
    e.preventDefault();
    document.body.scrollTo({ behavior: "smooth"})
  }
</script>

<a
  href="!#"
  on:click={(e) => scrollToTop(e)}
  class="btn btn-lg btn-primary btn-lg-square rounded-circle back-to-top"
  ><i class="bi bi-arrow-up" /></a
>
