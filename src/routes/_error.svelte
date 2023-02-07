<script>
	// export let status;
	// export let error;

  import Header from "../components/Header.svelte";
  import Error from "../components/404.svelte";
  import BreadCrumb from "../components/BreadCrumb.svelte";
  const params = { image: "/img/hero-2.png"}
  const breadProps = [{ link: '/', text: 'Home'}, {link: '/page', text: 'Error'},{ link: 'page', text: 'Page'}]
	const dev = process.env.NODE_ENV === 'development';
</script>

<div>
  <Header {params}>
    <div class="col-lg-6">
      <h1 class="display-4 mb-3 animated slideInDown">
        404
      </h1>
      <BreadCrumb {breadProps} />
    </div>
  </Header>
  <Error />
</div>