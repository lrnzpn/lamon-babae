<template>
    <nuxt />
</template>

<style lang="scss">
html {
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

.container {
    img {
    padding: 1em;
    width: 150px;
    height: auto;

    @media screen and (max-width: 720px) {
            width: 120px;
            padding: .5em;
        }
    }
}


.background {
    background-size: 100% 100%;
    background-repeat: no-repeat;
    height: 100vh;
    width: 100vw;
}

.center-end {
    display: flex;
    justify-content: center;
    align-items: flex-end;
}

.pb-4 {
    padding-bottom: 4em;
}
</style>
