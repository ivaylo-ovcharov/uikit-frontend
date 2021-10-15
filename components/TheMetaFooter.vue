<template>
  <div class="uk-section-default uk-section uk-section-small uk-padding-remove-top">
    <div class="uk-container uk-container-large">
      <div class="uk-margin-remove-bottom tm-grid-expand uk-grid-row-small uk-margin-xlarge uk-grid" uk-grid="">
        <div class="uk-width-1-4@m uk-first-column">
          <div class="uk-position-relative uk-margin uk-text-left@m uk-text-center" style="z-index: 1;">
            <a class="el-link" href="/joomla/themes/devstack/index.php"><img class="el-image" alt="" data-src="/demo/devstack/images/logo.svg" uk-img="" src="https://demo.yootheme.com/demo/devstack/images/logo.svg"></a>
          </div>
        </div>

        <div class="uk-grid-item-match uk-flex-middle uk-width-3-4@m">
          <div class="uk-panel uk-width-1-1">
            <div class="uk-panel uk-text-small uk-text-muted uk-position-relative uk-margin uk-text-right@m uk-text-center" style="z-index: 1;">
              © <script> document.currentScript.insertAdjacentHTML('afterend', '<time datetime="' + new Date().toJSON() + '">' + new Intl.DateTimeFormat(document.documentElement.lang, {year: 'numeric'}).format() + '</time>'); </script><time datetime="2021-10-15T17:44:15.807Z">2021</time> DevStack. All rights reserved. Powered by <a class="uk-link-text" href="https://yootheme.com/">YOOtheme</a>.
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: 'TheMetaFooter'
}
</script>
