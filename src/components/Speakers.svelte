<script>
  import { speakers } from '../data'
</script>

<style>
  .section-title {
    font-size: 32pt;
    font-weight: normal;
    color: #393939;
    padding: 30px 0;
  }
</style>

<section id="speakers" class="container">
  <div class="row">
    <div class="col-md-12">
      <h2 class="section-title">Speakers</h2>
    </div>

    {#each speakers as speaker}
      <div class="col-md-4">
        <div class="card mb-4 shadow-sm">
          <svg
            class="bd-placeholder-img card-img-top"
            width="100%"
            height="225"
            xmlns="http://www.w3.org/2000/svg"
            preserveAspectRatio="xMidYMid slice"
            focusable="false"
            role="img"
            aria-label="Placeholder: Thumbnail">
            <title>Placeholder</title>
            <rect width="100%" height="100%" fill="#f76" />
            <text x="38%" y="50%" fill="#eceeef" dy=".3em">Thumbnail</text>
          </svg>
          <div class="card-body">
            <h4>{speaker.name}</h4>
            <p class="card-text">
              This is a wider card with supporting text below as a natural
              lead-in to additional content. This content is a little bit
              longer.
            </p>
            <div class="d-flex justify-content-between align-items-center">
              <div class="btn-group">
                <a href="#linkedin-profile" class="btn btn-sm btn-link">LinkedIn</a>
                <a href="#github-profile" class="btn btn-sm btn-link">GitHub</a>
              </div>
            </div>
          </div>
        </div>
      </div>
    {/each}
  </div>
</section>
