<template>
  <div class="container">
      <section>
          <div class="desktop--1 background"></div>
      </section>
      <section>
          <div class="desktop--2 background center-end pb-4">
              <!-- insert embed link here -->
              <iframe width="275" height="170" src="https://www.youtube.com/embed/TaHmAZNUwLo" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
          </div>
      </section>
      <section>
          <div class="desktop--3 background center-end pb-4">
              <!-- insert embed link here -->
              <iframe width="275" height="170" src="https://www.youtube.com/embed/TaHmAZNUwLo" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
          </div>
      </section>
  </div>
</template>

<script>
export default {
    data() {
        return {
            
        }
    }
}
</script>

<style lang="scss" scoped>
.desktop {
    &--1 {
        background-image: url('../assets/EP1/DESKTOP01.png');

        @media screen and (max-width: 991px) {
            background-image: url('../assets/EP1/TABLET01.png');
        }

        @media screen and (max-width: 720px) {
            background-image: url('../assets/EP1/MOBILE01.png')
        }
    }

    &--2 {
        background-image: url('../assets/EP1/DESKTOP02.png');

        @media screen and (max-width: 991px) {
            background-image: url('../assets/EP1/TABLET02.png');
        }

        @media screen and (max-width: 720px) {
            background-image: url('../assets/EP1/MOBILE02.png')
        }
    }

    &--3 {
        background-image: url('../assets/EP1/DESKTOP03.png');
        @media screen and (max-width: 991px) {
            background-image: url('../assets/EP1/TABLET03.png');
        }

        @media screen and (max-width: 720px) {
            background-image: url('../assets/EP1/MOBILE03.png')
        }
    }
}
</style>