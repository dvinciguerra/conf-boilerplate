<script>
	import About from '../components/About.svelte';
	import Header from '../components/Header.svelte';
	import Speakers from '../components/Speakers.svelte';
	import Location from '../components/Location.svelte';
	import Schedule from '../components/Schedule.svelte';
	import Sponsors from '../components/Sponsors.svelte';
	import Footer from '../components/Footer.svelte';

  import { SITE_TITLE } from '../constants.js';
</script>

<svelte:head>
  <title>{ SITE_TITLE }</title>
</svelte:head>

<Header />

<About />
<Location />
<Speakers />
<Schedule />
<Sponsors />

<Footer />
