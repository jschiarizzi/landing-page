<template>
  <div class="flex flex-col bg-herodao-red mt-4 pt-4 pb-8 overflow-hidden">
    <div
      class="absolute right-0 overflow-hidden object-contain pointer-events-none"
    >
      <img class="opacity-40 pointer-events-none" src="@/assets/dots.svg" />
    </div>
    <div
      class="absolute left-0 overflow-hidden object-contain pointer-events-none"
    >
      <img class="opacity-40 pointer-events-none" src="@/assets/dotsleft.svg" />
    </div>
    <div
      class="flex flex-col space-y-2 space-x-2 mx-auto"
      style="max-width: 80%"
    >
      <div
        class="flex font-aAhaWow sm:text-4xl sm:pt-2 pt-2 text-lg justify-center text-white"
      >
        FAQ
      </div>
      <div
        class="flex text-white font-architects-daughter font-bold sm:text-3xl text-sm justify-center sm:pt-8"
      >
        What is Hero DAO?
      </div>
      <div
        class="flex text-white font-avenir sm:text-xl sm:pt-4 text-xs justify-center"
      >
        Hero DAO is an organization focused on rebooting comic book heroes who
        have fallen into the public domain, and building a community owned
        franchise.
      </div>
      <div
        class="flex text-white font-architects-daughter font-bold sm:text-3xl justify-center text-sm sm:pt-8"
      >
        Where is Hero DAO going?
      </div>
      <div
        class="flex text-white font-avenir sm:text-xl sm:pt-4 text-xs justify-center"
      >
        We're launching a real physical comic book, and an entire superhero
        franchise where the IP is owned by the community. Expect an ecosystem of
        several heroes, and the first physical comics shipping in early 2022.
        Next up is more heroes, several kinds of media, a cinematic universe,
        and create asset licensing.
      </div>
      <div
        class="flex text-white font-architects-daughter font-bold sm:text-3xl justify-center text-sm sm:pt-8"
      >
        What is a DAO
      </div>
      <div
        class="flex text-white font-avenir sm:text-xl sm:pt-4 text-xs justify-center"
      >
        A Decentralized Autonomous Organization is a community of people making
        decisions together in a decentralized manner. A DAO is better at making
        decisions than other communities because software automates executing
        the results of votes. Our DAO can own IP collectively, like a co-op.
        There are also protection mechanisms built into the organization. For
        example, at any time members can “rage-quit” their shares in the
        organization, and take a prorated amount of the treasury with them.
      </div>
      <div
        class="flex text-white font-architects-daughter font-bold sm:text-3xl justify-center text-sm sm:pt-8"
      >
        What network is Hero DAO built on?
      </div>
      <div
        class="flex text-white font-avenir sm:text-xl sm:pt-4 text-xs justify-center"
      >
        <p>
          <a
            class="underline"
            href="https://app.daohaus.club/dao/0x64/0x82b09c514d5427c8184b2fe7dc9fa632a6c05c26"
          >
            DAOhaus
          </a>
          -- a no code platform for Moloch DAOs. We use
          <a class="underline" href="https://www.xdaichain.com/">
            Gnosis Chain</a
          >
          to secure shares and automate voting actions. Gnosis Chain uses Proof
          of Stake which requires a similar amount of energy as sending emails.
        </p>
      </div>
      <div
        class="flex text-white font-architects-daughter font-bold sm:text-3xl justify-center text-sm sm:pt-8"
      >
        How is Hero DAO controlled?
      </div>
      <div
        class="flex text-white font-avenir sm:text-xl sm:pt-4 text-xs justify-center"
      >
        Hero DAO does not currently have a governance token you can buy . To
        join the DAO you must contribute to the vault. In return, you will
        receive non-transferable shares. 100% of the money in our vault is
        controlled entirely by the DAO’s members through 1-share-1-vote voting.
        We can vote to pay an artist or launch a token, and if the votes decide
        something happens, then it is automatically executed. There are no
        delegates or funds controlled by insiders, and the founders are no
        longer the largest shareholders.

        <br /><br />Hero DAO is DAO first. We started with a DAO in February
        2021 with the explicit goal of creating a superhero franchise that is
        owned by the artists, creators, and fans that love it. Instead of
        launching a token sale, we launched a community first, with everyone
        that wants to participate leading the vision.
      </div>
      <div
        class="flex text-white font-architects-daughter font-bold sm:text-3xl justify-center text-sm sm:pt-8"
      >
        How can I join?
      </div>
      <div
        class="flex text-white font-avenir sm:text-xl sm:pt-4 text-xs justify-center"
      >
        <p>
          You can join Hero Dao by contributing work or purchasing shares from
          the Dao through the Gnosis Chain. Hero Dao is focused on ensuring
          shares are given to content creators, and we welcome anyone looking to
          contribute their time or ideas.<br />
          <a class="underline" href="https://blog.herodao.org/Joining"
            >Learn more</a
          >
        </p>
      </div>
      <div
        class="flex text-white font-architects-daughter font-bold sm:text-3xl justify-center text-sm sm:pt-8"
      >
        How can I contribute?
      </div>
      <div
        class="flex text-white font-avenir sm:text-xl sm:pt-4 text-xs justify-center"
      >
        Attend Town Halls or other meetings, voice your opinions. Help create
        digital artwork or writing for our comic or other media. Help do
        proofreading for scripts. If you want something to do... just ask.
        Onboard any of your interested friends and find interesting public
        domain IP for us to reboot.
      </div>
      <div
        class="flex text-white font-architects-daughter font-bold sm:text-3xl justify-center text-sm sm:pt-8"
      >
        What is hero dao building?
      </div>
      <div
        class="flex text-white font-avenir sm:text-xl sm:pt-4 text-xs justify-center"
      >
        HeroDao is building a media movement based on the premise of fan owned
        and fan directed works. We want to bring ownership of our IP to the
        creators who help make it possible, and guarantee everyone in the
        creation process is compensated for their work.
      </div>
      <div
        class="flex text-white font-architects-daughter font-bold sm:text-3xl justify-center text-sm sm:pt-8"
      >
        Have another question?
      </div>
      <div
        class="flex text-white font-avenir sm:text-xl sm:pt-4 text-xs justify-center"
      >
        Feel free to ask in our discord channel, someone will answer it as soon
        as possible.
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "FaqContainer",
};
</script>
