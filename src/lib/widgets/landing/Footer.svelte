

<script lang="ts">
    // import {  } from '$shared';
    // import {  } from '$widgets';
    // import {  } from '$entities'
  export let otherBoardgames, navigation;
</script>

<footer class="footer_component">
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
              <a href="/" aria-current="page" class="footer_logo-link w-nav-brand w--current">
                <img src="/images/logo.svg" loading="lazy" alt="">
              </a>
            </div>
          </div>
          <div class="w-layout-grid footer_top-wrapper">
            <div  class="footer_left-wrapper">
              <div class="margin-bottom margin-medium hide-mobile-portrait">
                <a href="/" aria-current="page" class="footer_logo-link w-nav-brand w--current">
                  <img src="/images/logo.svg" loading="lazy" alt="">
                </a>
              </div>
              <div class="margin-bottom margin-medium">
                <div class="footer_details-wrapper">
                  <div class="footer_link-list">
                    <h3 class="footer-heading text-color-dark-orange">Contact:</h3>
                    <a href="mailto:coffe@puzzle-management.com" class="footer_link">coffe@puzzle-management.com</a>
                  </div>
                </div>
              </div>
              <div class="w-layout-grid footer_social-list">
                <a href="/" target="_blank" class="footer_social-link w-inline-block">
                  <div class="font-awesome-brands"></div>
                </a>
                <a href="/" target="_blank" class="footer_social-link w-inline-block">
                  <div class="font-awesome-brands"></div>
                </a>
              </div>
            </div>

            <div  class="footer_link-list">
              <h3 class="footer-heading text-color-dark-orange">Navigation</h3>
              {#each navigation as {title, link}}
                <a href="{link}" class="footer_link">{title}</a>
              {/each}
            </div>

            <div class="footer_link-list">
              <h3 class="footer-heading text-color-dark-orange">Other boardgames</h3>
              {#each otherBoardgames as {title, link}}
                <a href="{link}" class="footer_link">{title}</a>
              {/each}
            </div>

          </div>
        </div>
        <div class="padding-bottom padding-medium">
          <div class="footer_bottom-wrapper">
            <div class="w-layout-grid footer_legal-list">
              <div >
                <div class="footer_credit-text">© 44games. All rights reserved.</div>
              </div>
            </div>
            <div class="w-layout-grid footer_legal-list">
              <div>
                <div class="footer_credit-text">Development by</div>
              </div>
              <a href="https://oleg-darkdev.vercel.app/" target="_blank" class="footer_legal-link text-color-turquoise">Oleg_darkDev</a>
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
.footer_social-link {
  border: 1px solid var(--dark-brown);
  background-color: var(--white);
  box-shadow: -2px 2px 0 0 var(--dark-brown);
  color: var(--dark-brown);
  border-radius: 50%;
  justify-content: center;
  align-items: center;
  width: 2rem;
  height: 2rem;
  text-decoration: none;
  transition: box-shadow 0.2s, transform 0.2s;
  display: flex;
}
.footer_social-link:hover {
  transform: translate(-2px, 2px);
  box-shadow: -2px 2px #0000;
}
.footer_link-list {
  flex-direction: column;
  grid-template-rows: auto;
  grid-template-columns: 100%;
  grid-auto-columns: 100%;
  place-items: flex-start start;
  display: flex;
}
.footer_link {
  padding-top: 0.4rem;
  padding-bottom: 0.4rem;
  font-size: 1rem;
  font-weight: 400;
  color: var(--cornsilk);
  text-decoration: none;
  transition: color 0.3s;
}
.footer_link:hover {
  color: var(--turquoise);
}
.footer_bottom-wrapper {
  justify-content: space-between;
  align-items: center;
  display: flex;
}
.footer_logo-link {
  float: none;
  padding-left: 0;
}
.footer_social-list {
  grid-column-gap: 0.8rem;
  grid-row-gap: 0.8rem;
  white-space: normal;
  grid-template-rows: auto;
  grid-template-columns: max-content;
  grid-auto-columns: max-content;
  grid-auto-flow: column;
  place-items: start;
  display: grid;
}
.footer_top-wrapper {
  grid-column-gap: 5rem;
  grid-row-gap: 5rem;
  grid-template-rows: auto;
  grid-template-columns: 1fr auto auto auto;
  align-items: start;
}
.footer_credit-text {
  font-size: 0.9rem;
}
.footer_menu-wrapper {
  grid-column-gap: 2rem;
  grid-template-rows: auto;
  grid-template-columns: 1fr 1fr 1fr;
  align-items: start;
}
.footer_legal-list {
  grid-column-gap: 5px;
  grid-row-gap: 5px;
  white-space: normal;
  grid-template-rows: auto;
  grid-template-columns: max-content;
  grid-auto-columns: max-content;
  grid-auto-flow: column;
  justify-content: center;
  display: grid;
}
.footer_legal-link {
  font-size: 0.9rem;
  transition: color 0.3s;
}
.footer_legal-link:hover {
  color: var(--turquoise);
}

@media screen and (max-width: 991px) {
.footer_link {
    font-size: 0.9rem;
  }
  .footer_top-wrapper {
    grid-column-gap: 2rem;
    grid-row-gap: 2rem;
  }
}

@media screen and (max-width: 767px) {

.footer_bottom-wrapper {
    text-align: center;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }
  .footer_top-wrapper {
    grid-column-gap: 2rem;
    grid-row-gap: 2rem;
    grid-template-columns: 1fr 1fr;
  }
  .footer_menu-wrapper {
    grid-column-gap: 1.5rem;
  }
}

@media screen and (max-width: 479px) {
  .footer_menu-wrapper {
    grid-column-gap: 1rem;
    grid-row-gap: 1rem;
    grid-template-columns: 1fr;
  }
}
</style>
