<script>
  import { sponsors } from '../data'
</script>

<style>
  .section-title {
    font-size: 32pt;
    font-weight: normal;
    color: #393939;
    padding: 30px 0;
  }

  .sponsor-image {
    padding: 20px 0;
  }
</style>

<section id="sponsors" class="container">
  <div class="row">
    <div class="col-md-12">
      <h2 class="section-title">Sponsors</h2>
    </div>

    {#each sponsors as sponsor}
      <div class="col-md-3 text-center sponsor-image">
        <svg
          class="bd-placeholder-img"
          width="150"
          height="150"
          xmlns="http://www.w3.org/2000/svg"
          preserveAspectRatio="xMidYMid slice"
          focusable="false"
          role="img"
          aria-label="Placeholder: 140x140">
          <title>{sponsor.name}</title>
          <rect width="150" height="150" fill="#52f" />
          <text x="30%" y="50%" fill="#fff" dy=".3em">150x150</text>
        </svg>
      </div>
    {/each}
  </div>
</section>
