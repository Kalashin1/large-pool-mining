<script>
  export let props = [
    {
      link: '/about',
      text: "About Us",
    },
    {
      link: '/pages',
      text: 'Pages',
    },
    {
      link: '/',
      text: 'Home'
    }
  ]
</script>


<nav aria-label="breadcrumb animated slideInDown">
  <ol class="breadcrumb mb-0">
    {#each props as prop}
      <li class="breadcrumb-item"><a href={`/${prop.link}`}>{prop.text}</a></li>
    {/each}
  </ol>
</nav>
