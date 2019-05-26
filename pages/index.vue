<template>
  <div>
    <heading/>
    <product/>
    <about/>
    <contact/>
  </div>
</template>

<script>

import Navbar from '../pages/partials/navbar';
import Heading from '../pages/partials/header';
import About from '../pages/about';
import Service from '../pages/services';
import Product from '../pages/product/index';
import Contact from '../pages/contact';
import Foot from '../pages/partials/footer';

export default {

  head: {
    title: 'AKSi+'
  },
  components: {
    Navbar, Heading, About, Service, Product, Contact, Foot
  }
}
</script>
