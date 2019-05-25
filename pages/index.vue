<template>
  <div>
    <h1>Test</h1>
  </div>
</template>

<script>

import Navbar from '../pages/partials/navbar';
import Heading from '../pages/partials/header';
import About from '../pages/about';
import Service from '../pages/services';
import Portofolio from '../pages/portofolio';
import Contact from '../pages/contact';
import Foot from '../pages/partials/footer';

export default {

  head: {
    title: 'AKSi+'
  },
  components: {
    Navbar, Heading, About, Service, Portofolio, Contact, Foot
  }
}
</script>
