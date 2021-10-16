<template>
  <div class="tm-header uk-visible@l tm-header-overlay" uk-header="">
    <div
      uk-sticky=""
      media="@l"
      cls-active="uk-navbar-sticky"
      sel-target=".uk-navbar-container"
      class="uk-sticky"
      style=""
    >
      <div class="uk-navbar-container uk-navbar-transparent uk-dark">
        <div class="uk-container uk-container-expand">
          <nav class="uk-navbar" uk-navbar="{&quot;align&quot;:&quot;left&quot;,&quot;boundary&quot;:&quot;.tm-header .uk-navbar-container&quot;,&quot;container&quot;:&quot;.tm-header > [uk-sticky]&quot;}">
            <div class="uk-navbar-left">
              <nuxt-link to="/" class="uk-navbar-item uk-logo">
                <img alt="DevStack" src="https://demo.yootheme.com/demo/devstack/images/logo.svg">
                <img class="uk-logo-inverse" alt="DevStack" src="https://demo.yootheme.com/demo/devstack/images/logo-inverted.svg">
              </nuxt-link>
            </div>

            <div class="uk-navbar-center">
              <ul class="uk-navbar-nav">
                <li v-for="item in items" :key="item.link" class="item-130 uk-parent">
                  <NuxtLink :to="item.link">
                    {{ item.name }}
                  </NuxtLink>
                  <div v-if="item.childs" uk-dropdown>
                    <ul class="uk-nav uk-navbar-dropdown-nav">
                      <li v-for="child in item.childs" :key="child.link" class="item-131">
                        <NuxtLink :to="child.link">
                          {{ child.name }}
                        </NuxtLink>
                      </li>
                    </ul>
                  </div>
                </li>
              </ul>
            </div>

            <div class="uk-navbar-right">
              <div id="module-90" class="uk-navbar-item">
                <div class="uk-margin-remove-last-child custom">
                  <div class="uk-grid-collapse uk-grid uk-grid-stack" uk-grid="">
                    <div>
                      <a class="uk-button uk-button-primary" href="#">Register</a>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </nav>
        </div>
      </div>
    </div><div class="uk-sticky-placeholder" style="height: 90px; margin: 0px;" hidden="" />
  </div>
</template>
<script>
export default {
  name: 'TheNavigationDesktop',
  props: {
    items: {
      type: Array,
      required: false,
      default: () => []
    }
  }
}
</script>
