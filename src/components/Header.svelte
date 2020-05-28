<script>
  import { SITE_TITLE } from '../constants.js'
</script>

<style>
  .heading {
    padding-top: 3rem;
    padding-bottom: 3rem;
    margin-bottom: 40px;
    background-color: #fff;
    min-height: 500px;
    background: #eaeaea;
  }

  @media (min-width: 768px) {
    .heading {
      padding-top: 6rem;
      padding-bottom: 6rem;
    }
  }

  .heading p:last-child {
    margin-bottom: 0;
  }

  .heading h1 {
    font-size: 62pt;
    font-weight: 300;
    color: #343434;
  }

  .heading .container {
    max-width: 40rem;
  }
</style>

<section id="home" class="heading text-center">
  <div class="container">
    <h1>{SITE_TITLE}</h1>
    <p class="lead text-muted">March 30, Florianópolis, Brazil</p>
    <p>
      <a href="#call-to-action" class="btn btn-primary my-2">Comming soon</a>
    </p>
  </div>
</section>
