<template>
  <div class="user">
    <h3>{{ title }}</h3>
    <h4>@{{ body }}</h4>
    <p>Email : {{ email }}</p>
    <p>
      <NuxtLink to="/">
        List of users
      </NuxtLink>
    </p>
  </div>
</template>

<script>
import axios from 'axios'

export default {
  validate({ params }) {
    return !isNaN(+params.id)
  },
  async asyncData({ params, error }) {
    try {
      const { data } = await axios.get(`https://jsonplaceholder.typicode.com/posts/${+params.id}`)
      return data
    } catch (e) {
      error({ message: 'User not found', statusCode: 404 })
    }
  }
}
</script>
