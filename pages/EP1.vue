<template>
  <div class="container">
      <section>
          <div class="desktop--1 background">
              <a href="http://tanghalangateneo.com/lamonbabae">
                  <img src="../assets/LB Button04 1.png" alt="back">
              </a>
          </div>
      </section>
      <section>
          <div class="desktop--2 background center-end pb-4">
              <!-- insert embed link here -->
              <iframe src="https://www.youtube.com/embed/5YFi3Uxbf0o" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
          </div>
      </section>
      <section>
          <div class="desktop--3 background center-end pb-4">
              <!-- insert embed link here -->
              <iframe src="https://www.youtube.com/embed/k4WvnK-qbOw" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
          </div>
      </section>
  </div>
</template>

<script>
export default {
    data() {
        return {
         title: 'Lamon Babae | EP 1'  
        }
    },
    head() {
        return {
            title: this.title,
        }
    }
}
</script>

<style lang="scss" scoped>
.desktop {
    &--1 {
        background-image: url('../assets/EP1/HDDESKTOP01.png');

        @media screen and (max-width: 1100px) {
            background-image: url('../assets/EP1/DESKTOP01.png');
        }

        @media screen and (max-width: 880px) {
            background-image: url('../assets/EP1/TABLET01.png');
        }

        @media screen and (max-width: 660px) {
            background-image: url('../assets/EP1/MOBILE01.png')
        }
    }

    &--2 {
        background-image: url('../assets/EP1/HDDESKTOP02.png');

        @media screen and (max-width: 1100px) {
            background-image: url('../assets/EP1/DESKTOP02.png');
        }

        @media screen and (max-width: 880px) {
            background-image: url('../assets/EP1/TABLET02.png');
        }

        @media screen and (max-width: 660px) {
            background-image: url('../assets/EP1/MOBILE02.png')
        }
    }

    &--3 {
        background-image: url('../assets/EP1/HDDESKTOP03.png');
        @media screen and (max-width: 1100px) {
            background-image: url('../assets/EP1/DESKTOP03.png');
        }

        @media screen and (max-width: 880px) {
            background-image: url('../assets/EP1/TABLET03.png');
        }

        @media screen and (max-width: 660px) {
            background-image: url('../assets/EP1/MOBILE03.png')
        }
    }
}

iframe {
        width: 250px;
        height: 150px;
        margin-bottom: 2.5%;

        @media screen and (max-width: 1100px) {
            margin-bottom: 5%;
        }

        @media screen and (max-width: 720px) {
            height: 120px;
            width: 180px;
            margin-bottom: 7.5%;
        }
    }
</style>