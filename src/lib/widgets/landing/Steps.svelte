

<script lang="ts">
    // import {  } from '$shared';
    // import {  } from '$widgets';
    // import {  } from '$entities'

  const steps = [
    {
      title: 'Lorem Ipsum',
      shortDesc: '',
      id: 0,
      icon: 'step_1.svg',
    },
    {
      title: 'Lorem Ipsum',
      shortDesc: '',
      id: 0,
      icon: 'step_2.svg',
    },
    {
      title: 'Lorem Ipsum',
      shortDesc: '',
      id: 0,
      icon: 'step_3.svg',
    },
    {
      title: 'Lorem Ipsum',
      shortDesc: '',
      id: 0,
      icon: 'step_4.svg',
    },
    {
      title: 'Lorem Ipsum',
      shortDesc: '',
      id: 0,
      icon: 'step_5.svg',
    },
    {
      title: 'Lorem Ipsum',
      shortDesc: '',
      id: 0,
      icon: 'step_6.svg',
    },
    {
      title: 'Lorem Ipsum',
      shortDesc: '',
      id: 0,
      icon: 'step_7.svg',
    }
  ]
</script>

<section class="">
    <div class="padding-global">
      <div class="container-large-2">
        <div class="padding-section-medium w-full">
          <a name="steps"></a>

          <div class="text-align-center">
            <div class="margin-bottom margin-large">
              <h2 class="heading-medium ">
                <span class="text-style-underline-v2">Lorem Ipsum is simply </span> dummy text of the
              </h2>
            </div>
          </div>
          <div class="w-layout-grid steps-list w-full">
            {#each steps as {title, icon}}
              <div class="logo6_wrapper  w-inline-block">
                <img src="/images/{icon}" loading="lazy" alt="{title} icon" class="logo6_logo">
                <div class="button-link with-icon">
                  <div>{title}</div>
                  <div class="icon-xxsmall w-embed">
                    <svg width="100%" height="100%" viewBox="0 0 21 17" fill="none" xmlns="http://www.w3.org/2000/svg">
                      <path d="M2 8.65421H19.2973M19.2973 8.65421L12.8108 2.16772M19.2973 8.65421L12.8108 15.1407" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"></path>
                    </svg>
                  </div>
                </div>
              </div>
            {/each}
          </div>
        </div>
      </div>
    </div>
  </section>

<style lang="postcss">
.steps-list {
  grid-column-gap: 0.5rem;
  grid-row-gap: 0.5rem;
  grid-template-rows: auto;
  grid-template-columns: 1fr 1fr 1fr 1fr 1fr 1fr 1fr;
}
.logo6_logo {
  transition: transform 0.4s;
}
.logo6_logo.white {
  display: none;
}
.logo6_wrapper {
  flex-direction: column;
  justify-content: center;
  align-items: center;
  width: 100%;
  padding-left: 0.675rem;
  padding-right: 0.675rem;
  display: flex;
}
@media screen and (max-width: 991px) {
  .steps-list {
    grid-template-columns: 1fr 1fr 1fr;
  }
}
@media screen and (max-width: 767px) {
 .steps-list {
    grid-column-gap: 0rem;
    grid-row-gap: 0rem;
    grid-template-columns: 1fr 1fr;
  }
  .logo6_wrapper {
    padding-bottom: 1rem;
    padding-left: 1rem;
    padding-right: 1rem;
  }
}
</style>
