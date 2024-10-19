

<script lang="ts">
    // import {  } from '$shared';
    // import {  } from '$widgets';
    // import {  } from '$entities'
  export let otherBoardgames, navigation;
</script>

<footer class="footer3_component">
  <div class="section_instafeed">
    <div>
      <div class="padding-section-medium padding-bottom-0">
        <div class="max-width-small align-center">
          <div class="text-align-center ">
            <div class="margin-bottom margin-small">
              <h2 class="heading-medium">Czas rozpocząć <span class="text-style-underline-v5">dialog!</span>
              </h2>
            </div>
          </div>
        </div>

      </div>
    </div>
  </div>
  <div class="page-padding">
    <div class="container-large">
      <div class="padding-top padding-huge">
        <div class="padding-bottom padding-xxlarge footer-padding">
          <div class="footer-logo-mobile">
            <div class="margin-bottom margin-medium show-mobile-portrait">
              <a href="/" aria-current="page" class="footer3_logo-link w-nav-brand w--current">
                <img src="/images/logo.svg" loading="lazy" alt="">
              </a>
            </div>
          </div>
          <div class="w-layout-grid footer3_top-wrapper">
            <div  class="footer3_left-wrapper">
              <div class="margin-bottom margin-medium hide-mobile-portrait">
                <a href="/" aria-current="page" class="footer3_logo-link w-nav-brand w--current">
                  <img src="/images/logo.svg" loading="lazy" alt="">
                </a>
              </div>
              <div class="margin-bottom margin-medium">
                <div class="footer3_details-wrapper">
                  <div class="footer3_link-list">
                    <h3 class="footer-heading">Contact:</h3>
                    <a href="mailto:coffe@puzzle-management.com" class="footer3_link">coffe@puzzle-management.com</a>
                  </div>
                </div>
              </div>
              <div class="w-layout-grid footer3_social-list">
                <a href="/" target="_blank" class="footer3_social-link w-inline-block">
                  <div class="font-awesome-brands"></div>
                </a>
                <a href="/" target="_blank" class="footer3_social-link w-inline-block">
                  <div class="font-awesome-brands"></div>
                </a>
              </div>
            </div>

            <div class="footer3_link-list">
              <h3 class="footer-heading">Other boardgames</h3>
              {#each otherBoardgames as {title, link}}
                <a href="{link}" class="footer3_link">{title}</a>
              {/each}
            </div>
            <div  class="footer3_link-list">
              <h3 class="footer-heading">Navigation</h3>
              {#each navigation as {title, link}}
                <a href="{link}" class="footer3_link">{title}</a>
              {/each}

            </div>
          </div>
        </div>
        <div class="padding-bottom padding-medium">
          <div class="footer3_bottom-wrapper">
            <div class="w-layout-grid footer3_legal-list">
              <div >
                <div class="footer3_credit-text">© 44games. All rights reserved.</div>
              </div>
            </div>
            <div class="w-layout-grid footer3_legal-list">
              <div>
                <div class="footer3_credit-text">Development by</div>
              </div>
              <a href="/" target="_blank" class="footer3_legal-link">Oleg_darkDev</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- <div class="striplines-footer">
    <div class="strip-default small"></div>
    <div class="strip-default small background-color-orange"></div>
    <div class="strip-default small background-color-orange"></div>
  </div> -->
</footer>


<style lang="postcss">

</style>
