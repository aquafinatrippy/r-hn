<template>
<div id="home" class="align-wrapper">
  <body class="container">
    <div class="row">
      <form class="col s12">
        <div class="row">
          <label>Input file</label>
          <div class="file-field input-field">
            <div class="btn">
              <span>Browse</span>
              <input type="file" />
            </div>

            <div class="file-path-wrapper">
              <input class="file-path validate" type="text" placeholder="Upload file" />
            </div>
          </div>
        </div>
        <a class="btn" href="/price">Submit</a>
      </form>
    </div>
  </body>
</div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "home",
  components: {}
};
</script>

<style lang="scss" scoped>
#home {
  height: 100vh;
  justify-content: center;
  display: flex;
  align-content: center;
  align-items: center;
  flex-direction: column;
}
</style>