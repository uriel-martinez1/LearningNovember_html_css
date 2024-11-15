<template>
  <main>
    <section class="hero section" data-padding="compact">
      <div class="wrapper hero__text">
        <h1 class="hero__title">
          November: A Month of Reflection, Remembrance, and Celebration
        </h1>
        <p class="hero__credit">
          Photo by <a
            href="https://unsplash.com/@patrickian4?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Patrick
            Fore</a> on <a
            href="https://unsplash.com/photos/photo-of-orange-squash-beside-potted-succulent-plants-hoxqcGUheeo?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Unsplash</a>
        </p>
      </div>
    </section>
    <section>
      <div>
        <h2>Origins of November</h2>
        <p>
          November, the eleventh month of the year in the Gregorian calendar, has a history steeped in ancient
          traditions, seasonal transitions, and cultural significance. The name "November" originates from the Latin
          word "novem," meaning "nine," as it was the ninth month in the Roman calendar before January and February
          were added. Known for its shifting weather and shorter days, November has long been a month marked by
          introspection and preparation, as civilizations throughout history readied themselves for winter’s arrival.
        </p>
      </div>

      <div>
        <h2>Ancient Celebrations and Samhain</h2>
        <p>
          Ancient societies across Europe and beyond recognized November as a time of gratitude and remembrance. The
          Celts celebrated Samhain at the beginning of November, a festival marking the end of the harvest season and
          the onset of winter. This event was significant for the ancient Celtic people, symbolizing a "thin" time
          when the boundaries between the living and the spirit worlds grew closer. Such festivals laid the foundation
          for modern observances like All Saints’ Day, a time to honor the departed, which later influenced Halloween
          traditions.
        </p>
      </div>

      <div>
        <h2>Honoring the Fallen</h2>
        <p>
          In more recent centuries, November has become a month of remembrance and national reflection for many
          countries. Remembrance Day, also known as Armistice Day or Veterans Day, is observed on November 11, marking
          the end of World War I and honoring the sacrifices of soldiers. The month invites a pause from the hustle of
          daily life, offering people worldwide a time to honor those who came before us, recognize the impact of war,
          and celebrate peace and resilience.
        </p>
      </div>

      <div>
        <h2>Modern Thanksgiving and Global Festivities</h2>
        <p>
          Today, November continues to carry a blend of historical reverence and modern celebration. It serves as a
          bridge between the busyness of autumn and the holiday festivities that close out the year. From Thanksgiving
          traditions in the United States, which emphasize gratitude and togetherness, to the many cultural festivals
          held around the world, November is a month that balances reflection with celebration. Embracing its roots,
          this month reminds us of the importance of gratitude, remembrance, and the cycle of seasons.
        </p>
      </div>
    </section>
  </main>
</template>

<script>

</script>

<style scoped>
/* this will go in the layer for layout */

.section {
  --padding: 9rem;
  padding: var(--padding);

  @media (width < 760px) {
    padding: 6rem;
  }
}

.hero {
  background-image: url(/src/assets/images/hero_bg_4.jpg);
  background-size: cover;
  background-position: center;
}

.hero__title {
  color: var(--text-high-contrast);
  text-align: left;
  padding: 1rem 0;

  @media (width < 760px) {
    font-size: var(--font-size-heading-sm);
  }
}

main h1 {
  font-family: var(--ff-heading);
}

main {
  background-color: #ffb84d;
}

.hero__credit {
  color: var(--text-high-contrast);
}
</style>