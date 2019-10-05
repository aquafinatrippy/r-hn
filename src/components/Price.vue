<template>
  <div class="container">
    <div class="row">
      <div class="col s6">
        <model-obj src="./door.obj"></model-obj>
      </div>
      <div class="col s6">
        <div class="box"></div>
      </div>
    </div>
    <table>
      <thead>
        <tr>
          <th>Wood type</th>
          <th>4meter sill price</th>
          <th>Sills total price</th>
        </tr>
      </thead>

      <tbody>
        <tr>
          <td>Timber</td>
          <td>24&euro;</td>
          <td>62&euro;</td>
        </tr>
        <tr>
          <td>Timber</td>
          <td>24&euro;</td>
          <td>62&euro;</td>
        </tr>
        <tr>
          <td>Timber</td>
          <td>24&euro;</td>
          <td>62&euro;</td>
        </tr>
      </tbody>
    </table>
  </div>
</template>

<script>
import { ModelObj } from "vue-3d-model";
export default {
  name: "Price",
  components: {
    ModelObj
  }
};
</script>

<style lang="scss" scoped>
.box {
  border: 1px black solid;
  width: 160px;
  height: 300px;
  background-color: grey;
}
</style>