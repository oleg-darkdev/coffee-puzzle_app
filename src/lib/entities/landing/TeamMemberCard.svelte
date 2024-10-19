

<script lang="ts">
    // import {  } from '$shared';
    // import {  } from '$widgets';
    // import {  } from '$entities'
  export let teamMember;
</script>

<div role="listitem" class="collection-item w-dyn-item">
  <div class="team2_item">
    <div class="margin-bottom margin-small">
      <div
        class="team2_image-wrapper"
      >
        <img src="/images/{teamMember.icon}" class='h-20 w-20 z-10 absolute -left-1 -top-10' alt="">
        <img
          alt="{teamMember.fullName} photo"
          loading="lazy"
          src="images/{teamMember.img}"
          class="team2_image z-0"
        />
      </div>
    </div>
    <div class="margin-bottom margin-xxsmall">
      <h3 class="heading-small">{teamMember.fullName}</h3>
    </div>
    <h3 class="text-weight-bold text-size-regular text-color-turquoise">
      {teamMember.role}
    </h3>
  </div>
</div>

<style lang="postcss">
.team2_item {
  text-align: center;
  flex-direction: column;
  align-items: stretch;
  width: 100%;
  display: flex;
}

.team2_image {
  border: 10px solid var(--floral-white);
  object-fit: cover;
  border-radius: 20px;
  width: 100%;
  height: 100%;
  position: absolute;
  inset: 0%;
}
.team2_image-wrapper {
  height: 20rem;
  margin-left: auto;
  margin-right: auto;
  position: relative;
  /* overflow: hidden; */
  transform: rotate(4deg);
}

@media screen and (max-width: 767px) {
  .team2_image-wrapper {
    width: 280px;
    margin-left: auto;
    margin-right: auto;
  }
}

@media screen and (max-width: 479px) {
  .team2_image-wrapper {
    padding-top: 66%;
  }
}
</style>
