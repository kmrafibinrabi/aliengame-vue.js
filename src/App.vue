<template>
  <div id="app" class="contain"></div>
  <h3>Hello this is the fist app from vue</h3>
</template>

<script>

</script>

<style lang="scss">
body {
  margin: 0;
  padding: 0;
  font-family: "Recursive", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  font-size: 19px;
  color: #2c3e50;
  position: relative;
  width: 100%;
  height: 100vh;
  overflow: hidden;
  background-size: cover !important;
  background: url("./assets/background.svg") no-repeat center center scroll,
    #29abe2;
}

h1,
h2,
h3,
h4 {
  font-weight: 800;
}

svg.main,
.contain {
  position: absolute;
  top: 0;
  left: 50%;
  transform: translate(-50%, 0);
  width: 1300px;
}

.character-clip {
  clip-path: url(#bottom-clip);
}

.zombie-clip {
  clip-path: url(#top-clip);
}

.modal {
  position: absolute;
  left: calc(50% - 300px);
  max-width: 550px;
  top: 100px;
  background: white;
  padding: 30px 60px 60px;
  border-radius: 20px;
}

.character-choices {
  margin: 5px 0;
}

.friendtalk {
  position: absolute;
  z-index: 1000;
  top: 300px;
  left: 265px;
  width: 200px;
}

button {
  display: inline-block;
  border: none;
  padding: 0.5rem 1rem;
  margin: 10px 0;
  border-radius: 5px;
  text-decoration: none;
  background: #0c719b;
  color: #ffffff;
  font-size: 1rem;
  font-family: "Recursive", Helvetica, Arial, sans-serif;
  cursor: pointer;
  text-align: center;
  -webkit-appearance: none;
  -moz-appearance: none;
}

text {
  font-family: "Recursive", Helvetica, Arial, sans-serif;
}

.zombietalk {
  position: absolute;
  z-index: 1000;
  top: 445px;
  left: 665px;
  width: 200px;
  height: 200px;
  display: flex;
  flex-direction: column;
  justify-content: center;

  p {
    margin: 0;
    text-align: center;
  }

  button {
    padding: 0.25rem 1rem;
    margin: 7px 0;
    border-radius: 5px;
    text-decoration: none;
    background: #fff;
    color: #1e1e1e;
    border: 1px solid #cfcece;
  }
}

.text {
  fill: white;
}

.cls-2 {
  fill: #29abe2;
}

.cls-3 {
  fill: #3d2f45;
}

.cls-4 {
  fill: #ff4d60;
}

.cls-5 {
  fill: #bf593a;
}

.cls-6 {
  fill: #96442b;
}

.cls-7 {
  fill: #852028;
}

.cls-8 {
  fill: #fffaf1;
}

.cls-9 {
  fill: #b8343f;
}

.cls-10 {
  fill: #66273a;
}

.cls-11 {
  fill: #d64151;
}

.cls-12 {
  fill: #9c2f3b;
}

.cls-13 {
  fill: #5c4769;
}

.cls-14 {
  fill: #bf571f;
}

.cls-15 {
  fill: #f58a4c;
}

.cls-16 {
  fill: #ffa870;
}

.cls-17 {
  fill: #ff8366;
}

.cls-18 {
  fill: #7a2f45;
}

.cls-19 {
  fill: #a12d37;
}

.cls-20 {
  fill: #fff;
}

.cls-21 {
  fill: #c93945;
}

.cls-22 {
  fill: #644b6e;
}

.cls-23 {
  fill: #382a3d;
}

.cls-24 {
  fill: #96c466;
}

.cls-25 {
  fill: #7bad47;
}

.cls-26 {
  fill: #d1e6ff;
}

.cls-27 {
  fill: #c6f7be;
}

.cls-28 {
  fill: #b3e084;
}

.cls-29 {
  fill: #dfffbd;
}

.cls-30 {
  fill: #6fc716;
}

.cls-32 {
  fill: #73648c;
}

.cls-33 {
  fill: #f59055;
}

.cls-34 {
  fill: #f57355;
}

.cls-35 {
  fill: #fe932e;
}

.cls-36 {
  fill: #f27501;
}

.cls-37 {
  fill: #fcea10;
}

.cls-38 {
  fill: #e6332a;
}

.cls-39 {
  fill: #8cb214;
}

.cls-40 {
  fill: #f39200;
}

.cls-41 {
  fill: #95c11f;
}

.cls-42 {
  fill: #d81d19;
}

.cls-43 {
  fill: #33415e;
}

.cls-44 {
  fill: #263147;
}

.cls-45 {
  fill: #0071bc;
} 
</style>
