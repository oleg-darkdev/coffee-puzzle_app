

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
        <img
          alt="{teamMember.fullName} photo"
          loading="lazy"
          src="images/{teamMember.img}"
          class="team2_image"
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

</style>
