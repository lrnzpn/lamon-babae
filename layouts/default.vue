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
    padding: .5em;
    width: 120px;
    height: auto;
    display: block;
    position: fixed;

    @media screen and (max-width: 991px) {
            display: none;
        }
    }
}


.background {
    background-size: 100% 100%;
    background-repeat: no-repeat;
    height: 100vh;
    width: 100vw;
}

.center {
    display: flex;
    justify-content: center;
    align-items: center;
}

.center-end {
    display: flex;
    justify-content: center;
    align-items: flex-end;
}

.center-start {
    display: flex;
    justify-content: center;
    align-items: flex-start;
}

.pb-4 {
    padding-bottom: 4em;
}
</style>
