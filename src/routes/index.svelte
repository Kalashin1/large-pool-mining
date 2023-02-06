<script>
  import About from "../components/About.svelte";
  import Facts from "../components/Facts.svelte";
  import Header from "../components/Header.svelte";
  import Features from "../components/Features.svelte";
  import Services from "../components/Services.svelte";
  import Faq from "../components/FAQ.svelte";

	const params = {
		image: 'img/hero-1.png'
	}
</script>

<div>
  <Header {params}>
    <div class="col-lg-6">
      <h1 class="display-4 mb-3 animated slideInDown">
        Secure and easy way to buy and sell bitcoin
      </h1>
      <p class="animated slideInDown">
        Large pool minining provides a safe and secure investment portfolio to help grow your assets, we have multiple digital assets in the form of bitcoins and would live to help you gain and grow yours.
      </p>
      <a href="/about" class="btn btn-primary py-3 px-4 animated slideInDown"
        >Explore More</a
      >
    </div>
  </Header>
  <About />
  <Facts />
  <Features />
  <Services />
  <Faq />
</div>
