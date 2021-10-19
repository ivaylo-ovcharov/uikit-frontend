<template>
  <div>
    <TheNavigationMobile :items="items" />
    <TheNavigationDesktop :items="items" />
  </div>
</template>
<script>
export default {
  name: 'TheNavigation',
  data () {
    return {
      items: [
        {
          name: 'Sales Funnel',
          link: 'why'
        },
        {
          name: 'Sass Products',
          link: 'enterprise'
        },
        {
          name: 'Pricing',
          link: 'pricing'
        },
        {
          name: 'Company',
          link: '',
          childs: [
            {
              name: 'About',
              link: 'about'
            },
            {
              name: 'Story',
              link: 'story'
            },
            {
              name: 'Careers',
              link: 'careers'
            },
            {
              name: 'Blog',
              link: 'blog'
            }
          ]
        }
      ]
    }
  }
}
</script>
