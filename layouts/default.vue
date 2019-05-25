<template>
  <div>
    <navbar/>
    <nuxt/>
  </div>
</template>

<script>
import Navbar from '../pages/partials/navbar';
import Heading from '../pages/partials/header';

export default {
  components: {
    Navbar, Heading
  }
}
</script>
