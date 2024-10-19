

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
            {#each navigation as {title, link, textColor}}
            <div class="link-wrap">
              <a href="{link}" class="navbar2_link {textColor} w-nav-link">{title}</a>
            </div>
            {/each}
            <div class="link-wrap hide-desktop">
              <a href="/" class="navbar2_link hide-desktop w-nav-link">Lorem Ipsum  <span class="font-awesome-solid padding-left padding-tiny"></span>
              </a>
            </div>
          </nav>
          <div class="navbar2_button-wrapper">
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
.navbar2_logo-link {
  padding-left: 0;
}
.navbar2_menu {
  justify-content: center;
  align-items: flex-start;
  display: flex;
  position: static;
}
.navbar2_dropdwn-toggle {
  padding: 0.5rem 2.5rem 0.5rem 1rem;
}

.button-2.is-navbar2-button {
  padding-top: 0.5rem;
  padding-bottom: 0.5rem;
}
.navbar2_menu-button {
  padding: 0;
}
.navbar2_container {
  grid-column-gap: 0.5rem;
  grid-row-gap: 0.5rem;
  grid-template-rows: auto;
  grid-template-columns: auto 1fr auto;
  grid-auto-columns: 1fr;
  justify-content: space-between;
  align-items: center;
  width: 100%;
  height: 100%;
  margin-left: auto;
  margin-right: auto;
  display: grid;
}
.navbar2_button-wrapper {
  grid-column-gap: 1rem;
  margin-left: 1rem;
  display: flex;
}
.navbar2_dropdown-link {
  padding: 0.5rem 1rem;
}
.navbar2_dropdown-link.w--current {
  color: var(--black);
}
.dropdown-icon-2 {
  flex-direction: column;
  justify-content: center;
  align-items: center;
  width: 1rem;
  height: 1rem;
  margin-top: auto;
  margin-bottom: auto;
  margin-right: 1rem;
  display: flex;
  position: absolute;
  inset: 0% 0% 0% auto;
}
.navbar2_dropdown-list.w--open {
  border: 1px solid var(--black);
  background-color: var(--white);
  padding: 0.5rem;
  position: absolute;
}
.navbar2_component {
  background-color: #0000;
  flex-direction: column;
  align-items: stretch;
  width: 100%;
  display: flex;
  position: absolute;
  inset: 0% 0% auto;
}
.navbar2_link {
  /* color: var(--cornsilk); */
  text-align: center;
  margin-left: 1vw;
  margin-right: 1vw;
  padding: 0;
  font-size: 0.9rem;
  font-weight: 500;
}
.navbar2_link.w--current {
  color: var(--dark-brown);
}
.navbar2_link.hide-desktop {
  display: none;
}




@media screen and (max-width: 991px) {
  .navbar2_menu {
    background-color: var(--cornsilk);
    -webkit-text-fill-color: inherit;
    background-clip: border-box;
    border-bottom: 1px solid #000;
    width: 100%;
    padding: 1rem 5%;
    position: absolute;
    overflow: auto;
  }
  .navbar2_menu.is-page-height-tablet {
    height: 100vh;
    padding-bottom: 15rem;
  }
  .navbar2_dropdwn-toggle {
    align-items: center;
    margin-left: 0;
    margin-right: 0;
    padding: 1rem 2rem 1rem 0;
    display: flex;
  }
  .menu-icon2 {
    flex-direction: column;
    justify-content: center;
    align-items: center;
    width: 48px;
    height: 48px;
    margin-right: -0.5rem;
    padding-bottom: 0;
    padding-right: 0;
    display: flex;
  }
  .menu-icon2_line-middle {
    background-color: var(--dark-orange);
    justify-content: center;
    align-items: center;
    width: 24px;
    height: 2px;
    margin-top: 6px;
    margin-bottom: 6px;
    padding-bottom: 0;
    padding-right: 0;
    display: flex;
  }
  .navbar2_menu-dropdown {
    flex-direction: column;
    justify-content: center;
    align-items: center;
    font-size: 1.125rem;
    display: flex;
  }
  .navbar2_menu-button {
    padding: 0;
  }
  .navbar2_menu-button.w--open {
    background-color: #0000;
  }
  .navbar2_container {
    grid-template-columns: 0.25fr 1fr;
    display: flex;
  }
  .navbar2_button-wrapper {
    align-items: center;
  }
  .navbar2_dropdown-link {
    text-align: center;
    width: auto;
    padding: 0.75rem 0;
    font-size: 16px;
  }
  .dropdown-icon-2 {
    margin-top: 0;
    margin-bottom: 0;
    margin-right: 0;
    inset: auto 0% auto auto;
  }
  .navbar2_dropdown-list {
    position: static;
    overflow: hidden;
  }
  .navbar2_dropdown-list.w--open {
    border-style: none;
    padding: 0;
    position: static;
  }
  .navbar2_link {
    color: var(--dark-brown);
    text-align: left;
    padding-left: 0;
    padding-right: 0;
    display: inline-block;
  }
  .navbar2_link.hide-desktop {
    display: none;
  }
}
@media screen and (max-width: 767px) {
 .navbar2_menu {
    background-image: url(/images/topo-Lines-v2.png);
    background-position: 50% 0;
    background-repeat: no-repeat;
    background-size: cover;
  }
  .button-2.is-navbar2-button {
    padding: 0.25rem 1rem;
  }
  .navbar2_link.hide-desktop {
    display: inline-block;
  }
}
</style>
