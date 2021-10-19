<template>
  <div class="uk-section-default uk-section uk-section-xlarge" uk-scrollspy="target: [uk-scrollspy-class]; cls: uk-animation-fade; delay: 200;">
    <div class="uk-container">
      <div class="tm-grid-expand uk-child-width-1-1 uk-grid-margin uk-grid uk-grid-stack" uk-grid="">
        <div class="uk-grid-item-match uk-first-column">
          <div class="uk-panel uk-width-1-1">
            <h2 class="uk-h1 uk-text-center">
              Compare Plans
            </h2><div class="uk-panel uk-text-lead uk-margin-medium uk-margin-remove-top uk-width-xlarge uk-margin-auto uk-text-center">
              Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
            </div><div uk-scrollspy-class="" style="" class="uk-scrollspy-inview ">
              <div class="uk-overflow-auto">
                <table class="uk-table uk-table-divider uk-table-middle uk-table-justify">
                  <thead>
                    <tr>
                      <th class="uk-width-large">
                        Features
                      </th>
                      <th>Free</th>
                      <th>Professional</th>
                      <th>Enterprise</th>
                    </tr>
                  </thead>
                  <tbody>
                    <tr>
                      <td>Concurrency</td>
                      <td>1</td>
                      <td>100</td>
                      <td>Custom</td>
                    </tr>
                    <tr>
                      <td>Self-hosted Runners</td>
                      <td>-</td>
                      <td>-</td>
                      <td>
                        <img class="uk-text-success" src="/demo/devstack/images/check.svg" uk-svg="" hidden=""><svg xmlns="http://www.w3.org/2000/svg" width="12" height="9" viewBox="0 0 12 9" class="uk-text-success uk-svg">
                          <path d="M4.35,9a.74.74,0,0,1-.52-.22L.45,5.43a.79.79,0,0,1,0-1.09.74.74,0,0,1,1.05,0h0L4.32,7.13,10.42.25a.73.73,0,0,1,1,0l0,0a.77.77,0,0,1,0,1.08L4.91,8.75A.78.78,0,0,1,4.38,9Z" />
                        </svg>
                      </td>
                    </tr>
                    <tr>
                      <td>Build Machines</td>
                      <td>Standard</td>
                      <td>Standard</td>
                      <td>Elite</td>
                    </tr>
                    <tr>
                      <td>Build on</td>
                      <td>Linux, Windows and Arm</td>
                      <td>Linux, Windows, Arm and MacOS</td>
                      <td>GPU and largest compute</td>
                    </tr>
                    <tr>
                      <td>User Limit </td>
                      <td>Up to 3 Users</td>
                      <td>Up to 10 Users</td>
                      <td>Unlimited</td>
                    </tr>
                    <tr>
                      <td>Group Management</td>
                      <td>-</td>
                      <td>
                        <img class="uk-text-success" src="/demo/devstack/images/check.svg" uk-svg="" hidden=""><svg xmlns="http://www.w3.org/2000/svg" width="12" height="9" viewBox="0 0 12 9" class="uk-text-success uk-svg">
                          <path d="M4.35,9a.74.74,0,0,1-.52-.22L.45,5.43a.79.79,0,0,1,0-1.09.74.74,0,0,1,1.05,0h0L4.32,7.13,10.42.25a.73.73,0,0,1,1,0l0,0a.77.77,0,0,1,0,1.08L4.91,8.75A.78.78,0,0,1,4.38,9Z" />
                        </svg>
                      </td>
                      <td>
                        <img class="uk-text-success" src="/demo/devstack/images/check.svg" uk-svg="" hidden=""><svg xmlns="http://www.w3.org/2000/svg" width="12" height="9" viewBox="0 0 12 9" class="uk-text-success uk-svg">
                          <path d="M4.35,9a.74.74,0,0,1-.52-.22L.45,5.43a.79.79,0,0,1,0-1.09.74.74,0,0,1,1.05,0h0L4.32,7.13,10.42.25a.73.73,0,0,1,1,0l0,0a.77.77,0,0,1,0,1.08L4.91,8.75A.78.78,0,0,1,4.38,9Z" />
                        </svg>
                      </td>
                    </tr>
                    <tr>
                      <td>Single Sign-on (SAML SSO)</td>
                      <td>-</td>
                      <td>-</td>
                      <td>
                        <img class="uk-text-success" src="/demo/devstack/images/check.svg" uk-svg="" hidden=""><svg xmlns="http://www.w3.org/2000/svg" width="12" height="9" viewBox="0 0 12 9" class="uk-text-success uk-svg">
                          <path d="M4.35,9a.74.74,0,0,1-.52-.22L.45,5.43a.79.79,0,0,1,0-1.09.74.74,0,0,1,1.05,0h0L4.32,7.13,10.42.25a.73.73,0,0,1,1,0l0,0a.77.77,0,0,1,0,1.08L4.91,8.75A.78.78,0,0,1,4.38,9Z" />
                        </svg>
                      </td>
                    </tr>
                    <tr>
                      <td>Audit logs</td>
                      <td>Up to 200/Month</td>
                      <td>Up to 1000/Month</td>
                      <td>Unlimited</td>
                    </tr>
                    <tr>
                      <td>API Management</td>
                      <td>-</td>
                      <td>5000 Tokens</td>
                      <td>Unlimited</td>
                    </tr>
                    <tr>
                      <td>Premium Integrations</td>
                      <td>-</td>
                      <td>
                        <img class="uk-text-success" src="/demo/devstack/images/check.svg" uk-svg="" hidden=""><svg xmlns="http://www.w3.org/2000/svg" width="12" height="9" viewBox="0 0 12 9" class="uk-text-success uk-svg">
                          <path d="M4.35,9a.74.74,0,0,1-.52-.22L.45,5.43a.79.79,0,0,1,0-1.09.74.74,0,0,1,1.05,0h0L4.32,7.13,10.42.25a.73.73,0,0,1,1,0l0,0a.77.77,0,0,1,0,1.08L4.91,8.75A.78.78,0,0,1,4.38,9Z" />
                        </svg>
                      </td>
                      <td>
                        <img class="uk-text-success" src="/demo/devstack/images/check.svg" uk-svg="" hidden=""><svg xmlns="http://www.w3.org/2000/svg" width="12" height="9" viewBox="0 0 12 9" class="uk-text-success uk-svg">
                          <path d="M4.35,9a.74.74,0,0,1-.52-.22L.45,5.43a.79.79,0,0,1,0-1.09.74.74,0,0,1,1.05,0h0L4.32,7.13,10.42.25a.73.73,0,0,1,1,0l0,0a.77.77,0,0,1,0,1.08L4.91,8.75A.78.78,0,0,1,4.38,9Z" />
                        </svg>
                      </td>
                    </tr>
                    <tr>
                      <td>Support </td>
                      <td>Community Support</td>
                      <td>Web-based Support</td>
                      <td>24/7 Premium Support</td>
                    </tr>
                  </tbody>
                </table>
              </div>
            </div>
            <div class="uk-visible@m uk-position-absolute uk-width-1-1 uk-text-right uk-scrollspy-inview " style="left: -1150px; bottom: -800px;" uk-scrollspy-class="">
              <img
                class="el-image"
                alt=""
                target="!*"
                data-src="/joomla/templates/yootheme/cache/background-square-03-4cf4eb7a.webp"
                data-srcset="/joomla/templates/yootheme/cache/background-square-03-fb5448fa.webp 768w, /joomla/templates/yootheme/cache/background-square-03-4cf4eb7a.webp 800w, /joomla/templates/yootheme/cache/background-square-03-97298b74.webp 1024w, /joomla/templates/yootheme/cache/background-square-03-cc7c1183.webp 1366w, /joomla/templates/yootheme/cache/background-square-03-6750e569.webp 1600w"
                data-sizes="(min-width: 800px) 800px"
                data-width="800"
                data-height="800"
                uk-img=""
                sizes="(min-width: 800px) 800px"
                srcset="/joomla/templates/yootheme/cache/background-square-03-fb5448fa.webp 768w, /joomla/templates/yootheme/cache/background-square-03-4cf4eb7a.webp 800w, /joomla/templates/yootheme/cache/background-square-03-97298b74.webp 1024w, /joomla/templates/yootheme/cache/background-square-03-cc7c1183.webp 1366w, /joomla/templates/yootheme/cache/background-square-03-6750e569.webp 1600w"
                src="https://demo.yootheme.com/joomla/templates/yootheme/cache/background-square-03-4cf4eb7a.webp"
              >
            </div>

            <div class="uk-visible@m uk-position-absolute uk-width-1-1 uk-text-left uk-scrollspy-inview " style="left: 1200px; bottom: 150px;" uk-scrollspy-class="">
              <img
                class="el-image"
                alt=""
                target="!*"
                data-src="/joomla/templates/yootheme/cache/background-square-02-421e29a6.webp"
                data-srcset="/joomla/templates/yootheme/cache/background-square-02-421e29a6.webp 450w, /joomla/templates/yootheme/cache/background-square-02-9f682572.webp 768w, /joomla/templates/yootheme/cache/background-square-02-d7e03bf5.webp 900w"
                data-sizes="(min-width: 450px) 450px"
                data-width="450"
                data-height="450"
                uk-img=""
                sizes="(min-width: 450px) 450px"
                srcset="/joomla/templates/yootheme/cache/background-square-02-421e29a6.webp 450w, /joomla/templates/yootheme/cache/background-square-02-9f682572.webp 768w, /joomla/templates/yootheme/cache/background-square-02-d7e03bf5.webp 900w"
                src="https://demo.yootheme.com/joomla/templates/yootheme/cache/background-square-02-421e29a6.webp"
              >
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: 'PricingCompare'
}
</script>
