

<script lang="ts">
    // import {  } from '$shared';
    // import {  } from '$widgets';
    // import {  } from '$entities'
  export let anchor, img, bgColor;
</script>

<section class="">
  <div class="padding-global">
    <div class="container-large">
      <a name="{anchor}" />

      <div class="padding-section-medium">
        <div class="w-layout-grid layout1_component">
          <div class="layout1_content">
            <slot name='content' />
          </div>

          <div class="layout1_image-wrapper text-align-right">
            <img src="/images/{img}" loading="lazy" alt="" class="image-border-orange">
            <div class="card-wrap {bgColor} ">
              <slot name="card-content" />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<style lang="postcss">
.card-wrap {
  z-index: 2;
  box-shadow: 4px 4px 0 0 var(--dark-brown);
  color: var(--dark-brown);
  text-align: left;
  /* background-color: #fffbf0; */
  border: 2px solid #000;
  border-radius: 12px;
  width: 34vw;
  max-width: 23rem;
  padding: 1rem 2rem;
  position: absolute;
  inset: auto auto -10.5rem -8%;
}
</style>
