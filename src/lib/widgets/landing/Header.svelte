

<script lang="ts">
    // import {  } from '$shared';
    // import {  } from '$widgets';
    // import {  } from '$entities'

  export let navigation;
</script>

<header class="navbar2_component w-nav" role="banner">
  <slot />

  <div class="navigation-wrap">
    <div class="padding-global">
      <div class="container-large">
        <div class="navbar2_container">
          <a href="/" aria-current="page" class="navbar2_logo-link w-nav-brand w--current">
            <img src="/images/logo.svg" loading="lazy" alt="" class="h-14 w-auto">
            <!-- 63638189ed0adf172d751756_sign-on-logo.png  navbar2_logo -->
          </a>
          <nav role="navigation" class="navbar2_menu w-nav-menu">
            {#each navigation as {title, link}}
            <div class="link-wrap">
              <a href="{link}" class="navbar2_link w-nav-link">{title}</a>
            </div>
            {/each}
            <div class="link-wrap hide-desktop">
              <a href="/" class="navbar2_link hide-desktop w-nav-link">Lorem Ipsum  <span class="font-awesome-solid padding-left padding-tiny"></span>
              </a>
            </div>
          </nav>
          <div id="w-node-_7bec46f6-3d09-80cd-f04f-258c6a409c7b-6a409c65" class="navbar2_button-wrapper">
            <a href="/" class="button with-icon hide-mobile-landscape w-inline-block">
              <div class="button-text">Appka</div>
              <div class="icon-xxsmall w-embed">
                <svg width="100%" height="100%" viewBox="0 0 18 15" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
                  <path d="M1 7.5H17M17 7.5L11 1.5M17 7.5L11 13.5" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"></path>
                </svg>
              </div>
            </a>
            <div class="navbar2_menu-button w-nav-button">
              <div class="menu-icon2">
                <div class="menu-icon2_line-top"></div>
                <div class="menu-icon2_line-middle">
                  <div class="menu-icon_line-middle-inner"></div>
                </div>
                <div class="menu-icon2_line-bottom"></div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

</header>

<style lang="postcss">

</style>
