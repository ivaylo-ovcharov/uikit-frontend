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
          name: 'Why Entropy',
          link: 'why-entropy'
        },
        {
          name: 'Enterprise',
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
              link: 'ourstory'
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
