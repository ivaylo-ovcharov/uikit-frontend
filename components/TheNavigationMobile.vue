<template>
  <div class="tm-header-mobile uk-hidden@l">
    <div uk-sticky="" cls-active="uk-navbar-sticky" sel-target=".uk-navbar-container" class="uk-sticky uk-sticky-fixed" style="position: fixed; top: 0px; width: 1127.2px;">
      <div class="uk-navbar-container">
        <nav uk-navbar="container: .tm-header-mobile" class="uk-navbar">
          <div class="uk-navbar-left">
            <a class="uk-navbar-toggle" href="#tm-mobile" uk-toggle="animation: true" aria-expanded="false">
              <div uk-navbar-toggle-icon="" class="uk-icon uk-navbar-toggle-icon"><svg width="20" height="20" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><rect y="9" width="20" height="2" /><rect y="3" width="20" height="2" /><rect y="15" width="20" height="2" /></svg></div>
            </a>
          </div>

          <div class="uk-navbar-center">
            <a href="https://demo.yootheme.com/joomla/themes/devstack/index.php" class="uk-navbar-item uk-logo">
              <img alt="DevStack" src="/demo/devstack/images/logo-mobile.svg"></a>
          </div>
        </nav>
      </div>

      <div class="uk-position-relative tm-header-mobile-slide">
        <div id="tm-mobile" class="uk-position-top" hidden="">
          <div class="uk-background-default uk-padding">
            <div class="uk-child-width-1-1 uk-grid uk-grid-stack" uk-grid="">
              <div>
                <div id="module-menu-mobile" class="uk-panel">
                  <ul class="uk-nav uk-nav-default uk-nav-divider uk-nav-parent-icon uk-nav-accordion" uk-nav="targets: > .js-accordion">
                    <li class="item-136 uk-active">
                      <a href="/joomla/themes/devstack/why-devstack"> Why DevStack?</a>
                    </li>
                    <li class="item-137">
                      <a href="/joomla/themes/devstack/enterprise"> Enterprise</a>
                    </li>
                    <li class="item-138">
                      <a href="/joomla/themes/devstack/pricing"> Pricing</a>
                    </li>
                    <li class="item-139 js-accordion uk-parent">
                      <a href=""> Developers</a>
                      <ul class="uk-nav-sub" hidden="">
                        <li class="item-140">
                          <a href="/joomla/themes/devstack/developers/support"> Support</a>
                        </li>
                        <li class="item-141">
                          <a href="/joomla/themes/devstack/developers/feature-index"> Feature Index</a>
                        </li>
                      </ul>
                    </li>
                    <li class="item-142 js-accordion uk-parent">
                      <a href=""> Company</a>
                      <ul class="uk-nav-sub" hidden="">
                        <li class="item-143">
                          <a href="/joomla/themes/devstack/company/about"> About</a>
                        </li>
                        <li class="item-144">
                          <a href="/joomla/themes/devstack/company/our-story"> Our Story</a>
                        </li>
                        <li class="item-145">
                          <a href="/joomla/themes/devstack/company/careers"> Careers</a>
                        </li>
                        <li class="item-146">
                          <a href="/joomla/themes/devstack/company/job-description"> Job Description</a>
                        </li>
                        <li class="item-147">
                          <a href="/joomla/themes/devstack/company/blog"> Blog</a>
                        </li>
                      </ul>
                    </li>
                    <li class="item-148">
                      <a href="#"> Login</a>
                    </li>
                  </ul>
                </div>
              </div>    <div>
                <div id="module-93" class="uk-panel">
                  <div class="uk-margin-remove-last-child custom">
                    <div><a class="uk-button uk-button-primary uk-button-large uk-width-1-1" href="#">Register</a></div>
                    <hr>
                    <p class="uk-text-meta uk-text-center">
                      © <script>document.currentScript.insertAdjacentHTML('afterend', '<time datetime="' + new Date().toJSON() + '">' + new Intl.DateTimeFormat(document.documentElement.lang, {year: 'numeric'}).format() + '</time>');</script><time datetime="2021-10-14T08:26:18.136Z">2021</time> DevStack. All rights reserved.
                    </p>

                    <div class="uk-child-width-auto uk-grid-small uk-flex uk-flex-center uk-grid uk-grid-stack" uk-grid="">
                      <div>
                        <a class="uk-icon-link uk-icon" href="https://www.facebook.com/yootheme" uk-icon="icon: facebook;"><svg width="20" height="20" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path d="M11,10h2.6l0.4-3H11V5.3c0-0.9,0.2-1.5,1.5-1.5H14V1.1c-0.3,0-1-0.1-2.1-0.1C9.6,1,8,2.4,8,5v2H5.5v3H8v8h3V10z" /></svg></a>
                      </div>
                      <div>
                        <a class="uk-icon-link uk-icon" href="https://www.twitter.com/yootheme" uk-icon="icon: twitter;"><svg width="20" height="20" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path d="M19,4.74 C18.339,5.029 17.626,5.229 16.881,5.32 C17.644,4.86 18.227,4.139 18.503,3.28 C17.79,3.7 17.001,4.009 16.159,4.17 C15.485,3.45 14.526,3 13.464,3 C11.423,3 9.771,4.66 9.771,6.7 C9.771,6.99 9.804,7.269 9.868,7.539 C6.795,7.38 4.076,5.919 2.254,3.679 C1.936,4.219 1.754,4.86 1.754,5.539 C1.754,6.82 2.405,7.95 3.397,8.61 C2.79,8.589 2.22,8.429 1.723,8.149 L1.723,8.189 C1.723,9.978 2.997,11.478 4.686,11.82 C4.376,11.899 4.049,11.939 3.713,11.939 C3.475,11.939 3.245,11.919 3.018,11.88 C3.49,13.349 4.852,14.419 6.469,14.449 C5.205,15.429 3.612,16.019 1.882,16.019 C1.583,16.019 1.29,16.009 1,15.969 C2.635,17.019 4.576,17.629 6.662,17.629 C13.454,17.629 17.17,12 17.17,7.129 C17.17,6.969 17.166,6.809 17.157,6.649 C17.879,6.129 18.504,5.478 19,4.74" /></svg></a>
                      </div>
                      <div>
                        <a class="uk-icon-link uk-icon" href="https://github.com/" uk-icon="icon: github;"><svg width="20" height="20" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path d="M10,1 C5.03,1 1,5.03 1,10 C1,13.98 3.58,17.35 7.16,18.54 C7.61,18.62 7.77,18.34 7.77,18.11 C7.77,17.9 7.76,17.33 7.76,16.58 C5.26,17.12 4.73,15.37 4.73,15.37 C4.32,14.33 3.73,14.05 3.73,14.05 C2.91,13.5 3.79,13.5 3.79,13.5 C4.69,13.56 5.17,14.43 5.17,14.43 C5.97,15.8 7.28,15.41 7.79,15.18 C7.87,14.6 8.1,14.2 8.36,13.98 C6.36,13.75 4.26,12.98 4.26,9.53 C4.26,8.55 4.61,7.74 5.19,7.11 C5.1,6.88 4.79,5.97 5.28,4.73 C5.28,4.73 6.04,4.49 7.75,5.65 C8.47,5.45 9.24,5.35 10,5.35 C10.76,5.35 11.53,5.45 12.25,5.65 C13.97,4.48 14.72,4.73 14.72,4.73 C15.21,5.97 14.9,6.88 14.81,7.11 C15.39,7.74 15.73,8.54 15.73,9.53 C15.73,12.99 13.63,13.75 11.62,13.97 C11.94,14.25 12.23,14.8 12.23,15.64 C12.23,16.84 12.22,17.81 12.22,18.11 C12.22,18.35 12.38,18.63 12.84,18.54 C16.42,17.35 19,13.98 19,10 C19,5.03 14.97,1 10,1 L10,1 Z" /></svg></a>
                      </div>
                      <div>
                        <a class="uk-icon-link uk-icon" href="https://discord.com/" uk-icon="icon: discord;"><svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 20 20"><path d="M16.074,4.361a14.243,14.243,0,0,0-3.61-1.134,10.61,10.61,0,0,0-.463.96,13.219,13.219,0,0,0-4,0,10.138,10.138,0,0,0-.468-.96A14.206,14.206,0,0,0,3.919,4.364,15.146,15.146,0,0,0,1.324,14.5a14.435,14.435,0,0,0,4.428,2.269A10.982,10.982,0,0,0,6.7,15.21a9.294,9.294,0,0,1-1.494-.727c.125-.093.248-.19.366-.289a10.212,10.212,0,0,0,8.854,0c.119.1.242.2.366.289a9.274,9.274,0,0,1-1.5.728,10.8,10.8,0,0,0,.948,1.562,14.419,14.419,0,0,0,4.431-2.27A15.128,15.128,0,0,0,16.074,4.361Zm-8.981,8.1a1.7,1.7,0,0,1-1.573-1.79A1.689,1.689,0,0,1,7.093,8.881a1.679,1.679,0,0,1,1.573,1.791A1.687,1.687,0,0,1,7.093,12.462Zm5.814,0a1.7,1.7,0,0,1-1.573-1.79,1.689,1.689,0,0,1,1.573-1.791,1.679,1.679,0,0,1,1.573,1.791A1.688,1.688,0,0,1,12.907,12.462Z" /></svg></a>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div><div class="uk-sticky-placeholder" style="height: 91px; margin: 0px;" />
  </div>
</template>
<script>
export default {
  name: 'TheNavigationMobile'
}
</script>
