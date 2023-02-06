<script>
  import About from "../components/About.svelte";
  import Header from "../components/Header.svelte";
	import BreadCrumb from "../components/BreadCrumb.svelte";
	const breadProps = [{ link: '/', text: 'Home'}, { link: 'about', text: 'About Us'}, { link: '/page', text: 'Page'}]
</script>

<div>
  <Header params={{image: '/img/hero-2.png'}}>
		<div class="col-lg-6">
			<h1 class="display-4 mb-3 animated slideInDown">About Us</h1>
			<BreadCrumb props={breadProps} />
		</div>
  </Header>
  <About />
</div>