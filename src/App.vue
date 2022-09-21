<template>
  <div class="card container" style="width: 70%">
    <div class="card-body">
      <div class="row">
        <div class="col-sm-3">
          <img
            alt="Profile"
            class="img-thumbnail"
            src="./assets/pro.jpg"
            Width="90%"
          />
        </div>
        <div class="col-sm-9">
          <h1 class="display-4 text-info">Teeraphat Fumfoire</h1>
          <div class="row gy-3">
            <div class="section col-12">
              <i class="bi bi-person-circle"></i> ประวัติ
            </div>
            <div class="col-sm-5">
              <div>ชื่อ-นามสกุล : นายธรีภัทร ฟุ่มเฟือย</div>
            </div>
            <div class="col-sm-2">
              <div>อายุ : 22 ปี</div>
            </div>
            <div class="col-sm-3">
              <div>สถานะภาพ : โสด</div>
            </div>
            <div class="col-sm-2">
              <div>เพศ : ชาย</div>
            </div>
            <div class="col-sm-3">
              <div>สัญชาติ : ไทย</div>
            </div>
            <div class="col-sm-4">
              <div>วันเกิด : 7 ธันวาคม 2542</div>
            </div>
          </div>
        </div>
      </div>
      <br />
      <hr />
      <HelloWorld />
    </div>
  </div>
  <br />
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
  font-size: 100%;
}
.cards {
  margin: 2rem auto;
  max-width: 40rem;
  border-radius: 12px;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.25);
  padding: 2rem;
  background: #fff;
}
.logo {
  font-size: 250%;
  margin: center auto;
}
.section {
  font-size: 180%;
}
</style>
