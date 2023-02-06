<script>
  import Header from "../components/Header.svelte";
  import Feature from "../components/Features.svelte";
  import BreadCrumb from "../components/BreadCrumb.svelte";
  const params = { image: "/img/hero-2.png"}
  const breadProps = [{ link: '/', text: 'Home'}, {link: '/feature', text: 'Feature'},{ link: 'page', text: 'Page'}]
</script>

<div>
  <Header {params}>
    <div class="col-lg-6">
      <h1 class="display-4 mb-3 animated slideInDown">
        Features
      </h1>
      <BreadCrumb {breadProps} />
    </div>
  </Header>
  <Feature />
</div>