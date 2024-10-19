

<script lang="ts">
    import { team } from '$shared';
    // import {  } from '$widgets';
    import { TeamMemberCard } from '$entities'

</script>

<section class="">
  <div class="padding-global">
    <div class="container-large">
      <div class="padding-section-medium">
        <div class="margin-bottom margin-xlarge">
          <div class="text-align-center">
            <div class="max-width-large align-center">
              <div class="margin-bottom">
                <h2 class="heading-medium">Team Members</h2>
              </div>
            </div>
          </div>
        </div>
        <div class="team2_component">
          <div class="team2_list-wrapper w-dyn-list">
            <div role="list" class="team2_list w-dyn-items">
              {#each team as teamMember}
                <TeamMemberCard {teamMember}/>
              {/each}
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<style lang="postcss">
.team2_social {
  grid-column-gap: 0.875rem;
  grid-row-gap: 0.875rem;
  grid-template-rows: auto;
  grid-template-columns: max-content;
  grid-auto-columns: 1fr;
  grid-auto-flow: column;
  align-self: center;
  margin-top: 1.5rem;
  display: grid;
}
.team2_list {
  grid-column-gap: 5rem;
  grid-row-gap: 5rem;
  grid-template-rows: auto;
  grid-template-columns: 1fr 1fr 1fr;
  grid-auto-columns: 1fr;
  place-items: start center;
  display: grid;
}

@media screen and (max-width: 991px) {
  .team2_list {
    grid-column-gap: 3rem;
    grid-row-gap: 3rem;
    grid-template-columns: 1fr 1fr;
  }
}
@media screen and (max-width: 767px) {
  .team2_list {
    grid-row-gap: 3rem;
    grid-template-columns: 1fr;
  }
}
@media screen and (max-width: 479px) {
  .team2_list {
    grid-template-columns: 1fr;
  }
}
</style>
