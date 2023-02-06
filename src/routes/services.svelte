<script>
  import Header from "../components/Header.svelte";
  import Services from "../components/Services.svelte";
  import BreadCrumb from "../components/BreadCrumb.svelte";
  const params = { image: "/img/hero-2.png"}
  const breadProps = [{ link: '/', text: 'Home'}, {link: '/services', text: 'Our Services'},{ link: 'page', text: 'Page'}]
</script>

<div>
  <Header {params}>
    <div class="col-lg-6">
      <h1 class="display-4 mb-3 animated slideInDown">
        Services
      </h1>
      <BreadCrumb {breadProps} />
    </div>
  </Header>
  <Services />
</div>