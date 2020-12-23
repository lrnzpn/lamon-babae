<template>
  <div class="container">
      <section>
          <div class="desktop--1 background">
              <a href="http://tanghalangateneo.com/lamonbabae">
                  <img src="../assets/LB Button04 1.png" alt="back">
              </a>
              <!-- insert embed link here -->
              <div class="center-end">
                  <iframe src="https://www.youtube.com/embed/y7klPHPyX1w" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
              </div>
          </div>
      </section>
      <section>
          <div class="desktop--2 background center-start">
              <!-- insert embed link here -->
              <iframe src="https://www.youtube.com/embed/s1ReOS4rhoU" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
          </div>
      </section>
      <section>
          <div class="desktop--3 background">
          </div>
      </section>

  </div>
</template>

<script>
export default {
    data() {
        return {
         title: 'Lamon Babae | EP 3'  
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
        background-image: url('../assets/EP3/EP3DESKTOP01.png');

        @media screen and (max-width: 990px) {
            background-image: url('../assets/EP3/EP3TABLET01.png');
        }

        @media screen and (max-width: 660px) {
            background-image: url('../assets/EP3/EP3MOBILE01.png')
        }

        .center-end {
            height: 100%;
        }

        iframe {
            height: 120px;
            width: 225px;
            margin-bottom: 150px;

            @media only screen 
            and (min-device-width: 768px) 
            and (max-device-width: 1024px) 
            and (-webkit-min-device-pixel-ratio: 1) {
                margin-bottom: 250px;
            }
        }
    }

    &--2 {
        background-image: url('../assets/EP3/EP3DESKTOP02.png');

        @media screen and (max-width: 990px) {
            background-image: url('../assets/EP3/EP3TABLET02.png');
        }

        @media screen and (max-width: 660px) {
            background-image: url('../assets/EP3/EP3MOBILE02.png')
        }

        iframe {
            height: 120px;
            width: 225px;
            margin-top: 50px;

            @media only screen 
            and (min-device-width: 768px) 
            and (max-device-width: 1024px) 
            and (-webkit-min-device-pixel-ratio: 1) {
                margin-top: 75px;
            }
        }
    }

    &--3 {
        background-image: url('../assets/EP3/EP3DESKTOP03.png');

        @media screen and (max-width: 990px) {
            background-image: url('../assets/EP3/EP3TABLET03.png');
        }

        @media screen and (max-width: 660px) {
            background-image: url('../assets/EP3/EP3MOBILE03.png')
        }
    }
}
</style>