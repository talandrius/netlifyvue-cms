<template>
  <Layout :show-logo="false">
    <!-- Author intro -->
    <Author :show-title="true" />

    <!-- List posts -->
    <div class="posts">
      <p>About my page to JS</p>
    </div>

  </Layout>
</template>
<script>
export default {
  metaInfo: {
    title: 'About me ',
    meta: [
      { name: 'talandria', content: 'pourquoi le javascript' }
    ]
  }
}
</script>
