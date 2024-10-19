

<script lang="ts">
    import { team } from '$shared';
    // import {  } from '$widgets';
    import { TeamMemberCard } from '$entities'

</script>

<section class="section_team2">
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

</style>
