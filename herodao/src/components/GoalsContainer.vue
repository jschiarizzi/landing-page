<template>
  <div class="sm:h-112 md:h-112 h-72">
    <div class="flex flex-row justify-evenly">
      <div class="flex flex-col sm:pt-24 pt-8 sm:space-y-4 space-y-2">
        <div class="flex justify-center">
          <img class="flex sm:h-28 h-12" src="@/assets/poolfunds.svg" />
        </div>
        <div
          class="flex font-architects-daughter justify-center font-extrabold sm:text-2xl"
        >
          Pool funds
        </div>
        <div class="flex font-avenir justify-center sm:text-2xl text-xs">
          Work together to raise<br />
          money as a community
        </div>
        <div class="flex flex-col sm:space-y-4 space-y-2 sm:pt-8">
          <img class="flex sm:h-28 h-12" src="@/assets/create.svg" />
          <div
            class="flex font-architects-daughter justify-center font-extrabold sm:text-2xl"
          >
            Create
          </div>
          <div class="flex font-avenir justify-center sm:text-2xl text-xs">
            Use pooled funds to illustrate<br />
            and write an original work
          </div>
        </div>
      </div>
      <div class="flex flex-col sm:space-y-4 space-y-2 justify-center">
        <div
          class="flex font-aAhaWow sm:text-4xl sm:pt-8 md:pt-4 text-lg justify-center"
        >
          Goals
        </div>
        <div class="flex justify-center">
          <img class="flex sm:h-28 h-12" src="@/assets/pickhero.svg" />
        </div>
        <div
          class="flex font-architects-daughter justify-center font-extrabold sm:text-2xl"
        >
          Pick Heroes
        </div>
        <div class="flex font-avenir justify-center sm:text-2xl text-xs">
          Members vote on which<br />
          hero gets a new story
        </div>
        <div class="flex flex-col sm:space-y-4 space-y-2 sm:pt-8">
          <img class="flex sm:h-28 h-12" src="@/assets/print.svg" />
          <div
            class="flex font-architects-daughter justify-center font-extrabold sm:text-2xl"
          >
            Produce
          </div>
          <div class="flex font-avenir justify-center sm:text-2xl text-xs">
            Print physical copies<br />
            for DAO members
          </div>
        </div>
      </div>
      <div class="flex flex-col sm:pt-24 pt-8 sm:space-y-4 space-y-2">
        <div class="flex justify-center">
          <img class="flex sm:h-28 h-12" src="@/assets/reboot.svg" />
        </div>
        <div
          class="flex font-architects-daughter justify-center font-extrabold sm:text-2xl"
        >
          Reboot
        </div>
        <div class="flex font-avenir justify-center sm:text-2xl text-xs">
          Vote on how to give<br />
          new life to a hero
        </div>
        <div class="flex flex-col sm:space-y-4 space-y-2 sm:pt-8">
          <img class="flex sm:h-28 h-12" src="@/assets/distribute.svg" />
          <div
            class="flex font-architects-daughter justify-center font-extrabold sm:text-2xl"
          >
            Grow
          </div>
          <div class="flex font-avenir justify-center sm:text-2xl text-xs">
            The first fan and creator<br />
            owned super hero franchise.
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "GoalsContainer",
};
</script>
