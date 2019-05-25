<template>
  <div>
    <h1>Article Pages {{ test }} </h1>
    <section id="portfolio">
      <div class="container-fluid p-0">
        <div class="row">

          <!-- Articles -->

          <div class="col-md-6" v-for="post in posts" :key="post.id">
            <div class="card mb-4 box-shadow">
              <img class="card-img-top" data-src="https://blackrockdigital.github.io/startbootstrap-creative/img/portfolio/thumbnails/1.jpg" alt="Thumbnail [100%x225]" style="height: 225px; width: 100%; display: block;" src="https://blackrockdigital.github.io/startbootstrap-creative/img/portfolio/thumbnails/1.jpg" data-holder-rendered="true">
              <div class="card-body">
                <h3 class="card-text">{{ post.title }}</h3>
                <div class="d-flex justify-content-between align-items-center">
                  <div class="btn-group">
                    <button type="button" class="btn btn-sm btn-outline-secondary">View</button>
                    <button type="button" class="btn btn-sm btn-outline-secondary">Edit</button>
                  </div>
                  <small class="text-muted">9 mins</small>
                </div>
              </div>
            </div>
          </div>
          <!-- /Articles -->

        </div>
      </div>
    </section>
  </div>
</template>

<script>

import axios from 'axios'

export default {

  head: {
    title: 'Article'
  },

  data: function () {
    return {
      count: 0,
      test: 'bahlulu',
      posts: []
    }
  },

  methods: {
    fetchData: function () {
      axios.get('https://jsonplaceholder.typicode.com/posts')
      .then((res) => {
        this.posts = res.data
      })
    }
  },

  mounted() {
    var vm = this
    vm.fetchData()
  }

}
</script>
