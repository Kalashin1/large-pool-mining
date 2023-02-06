<script>
  const faqs = [
    {
      title: "How To Buy & Sell Bitcoin?",
      text: "On large pool mining you can easily buy and sell your bitcoin. We are ready to purchase from you or link you up to other investors looking to buy from you. Or those willing to buy from you.",
      delaySecs: 0.1,
    },
    {
      title: "How Can I Transfer Bitcoin?",
      text: "You come with your own wallet so you can easily transfer your funds at any time you see fit.",
      delaySecs: 0.2,
    },
    {
      title: "What About The Investment With Large Pool Mining?",
      text: "Large pool mining has different investment schemes for different individuals, whether it be a starter with just some few bitcoins or you want to go all out with the investment.",
      delaySecs: 0.3,
    },
    {
      title: "How Can I Get The Price Idea?",
      text: "To get an idea of the pricing please check the pricing page",
      delaySecs: 0.4,
    },
    {
      title: "How Can I Contact With You?",
      text: "You can leave a message for us on through the Contact page",
      delaySecs: 0.5,
    },
  ];
</script>

<div class="container-xxl py-5">
  <div class="container">
    <div
      class="text-center mx-auto wow fadeInUp"
      data-wow-delay="0.1s"
      style="max-width: 500px;"
    >
      <h1 class="display-6">FAQs</h1>
      <p class="text-primary fs-5 mb-5">Frequently Asked Questions</p>
    </div>
    <div class="row justify-content-center">
      <div class="col-lg-10">
        <div class="accordion" id="accordionExample">
          {#each faqs as faq}
            <div class="accordion-item wow fadeInUp" data-wow-delay={`${faq.delaySecs}s`}>
              <h2 class="accordion-header" id="headingOne">
                <button
                  class="accordion-button"
                  type="button"
                  data-bs-toggle="collapse"
                  data-bs-target="#collapseOne"
                  aria-expanded="true"
                  aria-controls="collapseOne"
                >
                  {faq.title}
                </button>
              </h2>
              <div
                id="collapseOne"
                class="accordion-collapse collapse show"
                aria-labelledby="headingOne"
                data-bs-parent="#accordionExample"
              >
                <div class="accordion-body">
                  {faq.text}
                </div>
              </div>
            </div>
          {/each}
        </div>
      </div>
    </div>
  </div>
</div>
