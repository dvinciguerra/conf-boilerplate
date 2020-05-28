<script>
  import { SITE_TITLE } from '../constants.js'
</script>

<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <div class="container">
    <a class="navbar-brand" href="#home">{SITE_TITLE}</a>
    <button
      class="navbar-toggler"
      type="button"
      data-toggle="collapse"
      data-target="#navbarNav"
      aria-controls="navbarNav"
      aria-expanded="false"
      aria-label="Toggle navigation">
      <span class="navbar-toggler-icon" />
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item active">
          <a class="nav-link" href="#home">
            Home
            <span class="sr-only">(current)</span>
          </a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#about">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#location">Location</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#speakers">Speakers</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#schedule">Schedule</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#sponsors">Sponsors</a>
        </li>
      </ul>
    </div>
  </div>
</nav>
