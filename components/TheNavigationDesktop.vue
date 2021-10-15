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
              <a href="https://demo.yootheme.com/joomla/themes/devstack/index.php" class="uk-navbar-item uk-logo">
                <img alt="DevStack" src="/demo/devstack/images/logo.svg"><img class="uk-logo-inverse" alt="DevStack" src="/demo/devstack/images/logo-inverted.svg"></a>
            </div>

            <div class="uk-navbar-center">
              <ul class="uk-navbar-nav">
                <li class="item-119 uk-active">
                  <a href="/joomla/themes/devstack/why-devstack"> Why DevStack?</a>
                </li>
                <li class="item-108">
                  <a href="/joomla/themes/devstack/enterprise"> Enterprise</a>
                </li>
                <li class="item-120">
                  <a href="/joomla/themes/devstack/pricing"> Pricing</a>
                </li>
                <li class="item-121 uk-parent">
                  <a tabindex="0" aria-expanded="false"> Developers</a>
                </li>
                <li class="item-130 uk-parent">
                  <a tabindex="0" aria-expanded="false"> Company</a>
                </li>
              </ul>
            </div>

            <div class="uk-navbar-right">
              <div id="module-90" class="uk-navbar-item">
                <div class="uk-margin-remove-last-child custom">
                  <div class="uk-grid-collapse uk-grid uk-grid-stack" uk-grid="">
                    <div class="uk-first-column">
                      <a class="uk-button uk-link-reset" href="#">Login</a>
                    </div>
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

      <div class="uk-navbar-dropdown uk-navbar-dropdown-bottom-left" uk-drop="{&quot;clsDrop&quot;:&quot;uk-navbar-dropdown&quot;,&quot;flip&quot;:&quot;x&quot;,&quot;pos&quot;:&quot;bottom-left&quot;,&quot;mode&quot;:&quot;hover&quot;,&quot;container&quot;:&quot;.tm-header > [uk-sticky]&quot;}" style="left: 955.417px; top: 90px;">
        <div class="uk-navbar-dropdown-grid uk-child-width-1-1 uk-grid uk-grid-stack" uk-grid="">
          <div class="uk-first-column">
            <ul class="uk-nav uk-navbar-dropdown-nav">
              <li class="item-131">
                <a href="/joomla/themes/devstack/company/about"> About</a>
              </li>
              <li class="item-124">
                <a href="/joomla/themes/devstack/company/our-story"> Our Story</a>
              </li>
              <li class="item-109">
                <a href="/joomla/themes/devstack/company/careers"> Careers</a>
              </li>
              <li class="item-123">
                <a href="/joomla/themes/devstack/company/job-description"> Job Description</a>
              </li>
              <li class="item-117">
                <a href="/joomla/themes/devstack/company/blog"> Blog</a>
              </li>
            </ul>
          </div>
        </div>
      </div><div class="uk-navbar-dropdown uk-navbar-dropdown-bottom-left" uk-drop="{&quot;clsDrop&quot;:&quot;uk-navbar-dropdown&quot;,&quot;flip&quot;:&quot;x&quot;,&quot;pos&quot;:&quot;bottom-left&quot;,&quot;mode&quot;:&quot;hover&quot;,&quot;container&quot;:&quot;.tm-header > [uk-sticky]&quot;}" style="left: 826.983px; top: 90px;">
        <div class="uk-navbar-dropdown-grid uk-child-width-1-1 uk-grid uk-grid-stack" uk-grid="">
          <div class="uk-first-column">
            <ul class="uk-nav uk-navbar-dropdown-nav">
              <li class="item-135">
                <a href="/joomla/themes/devstack/developers/support"> Support</a>
              </li>
              <li class="item-122">
                <a href="/joomla/themes/devstack/developers/feature-index"> Feature Index</a>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div><div class="uk-sticky-placeholder" style="height: 90px; margin: 0px;" hidden="" />
  </div>
</template>
<script>
export default {
  name: 'TheNavigationDesktop'
}
</script>
