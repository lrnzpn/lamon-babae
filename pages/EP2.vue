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
          <div class="desktop--2 background">
          </div>
      </section>
      <section>
          <div class="desktop--3 background center">
              <!-- insert embed link here -->
              <iframe src="https://www.youtube.com/embed/UdsmY-CEWz4" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
          </div>
      </section>

      <section>
          <div class="desktop--4 background center-start">
              <!-- insert embed link here -->
              <iframe src="https://www.youtube.com/embed/Cu73yM8wUXA" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
          </div>
      </section>
  </div>
</template>

<script>
export default {
    data() {
        return {
         title: 'Lamon Babae | EP 2'  
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
        background-image: url('../assets/EP2/EP2DESKTOP01.png');

        // @media screen and (max-width: 1100px) {
        //     background-image: url('../assets/EP2/.png');
        // }

        @media screen and (max-width: 1100px) {
            background-image: url('../assets/EP2/EP2TABLET01.png');
        }

        @media screen and (max-width: 700px) {
            background-image: url('../assets/EP2/EP2MOBILE01.png')
        }
    }

    &--2 {
        background-image: url('../assets/EP2/EP2DESKTOP02.png');

        // @media screen and (max-width: 1100px) {
        //     background-image: url('../assets/EP2/.png');
        // }

        @media screen and (max-width: 1100px) {
            background-image: url('../assets/EP2/EP2TABLET02.png');
        }

        @media screen and (max-width: 700px) {
            background-image: url('../assets/EP2/EP2MOBILE02.png')
        }
    }

    &--3 {
        background-image: url('../assets/EP2/EP2DESKTOP03.png');

        @media screen and (max-width: 1100px) {
            background-image: url('../assets/EP2/EP2TABLET03.png');
        }

        @media screen and (max-width: 700px) {
            background-image: url('../assets/EP2/EP2MOBILE03.png')
        }

        iframe {

            height: 120px;
            width: 225px;
            margin-left: 15%;  
            margin-bottom: 12%;

            @media screen and (max-width: 1100px) {
                margin-left: 25%;  
                margin-bottom: 20%;            
            }

            @media screen and (max-width: 720px) {
                margin-left: 30%;   
                 margin-bottom: 35%;      
            }
        }
    }

    &--4 {
        background-image: url('../assets/EP2/EP2DESKTOP04.png');

        // @media screen and (max-width: 1100px) {
        //     background-image: url('../assets/EP2/.png');
        // }

        @media screen and (max-width: 1100px) {
            background-image: url('../assets/EP2/EP2TABLET04.png');
        }

        @media screen and (max-width: 700px) {
            background-image: url('../assets/EP2/EP2MOBILE04.png')
        }

        iframe {

            width: 250px;
            height: 150px;

            margin-top: 4.5%;
            @media screen and (max-width: 1100px) {
                margin-top: 8%;
            }

            @media screen and (max-width: 720px) {
                height: 150px;
                width: 200px;
                margin-top: 10%;
            }
        }
    }
}
</style>