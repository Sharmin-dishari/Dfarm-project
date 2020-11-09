<template>
  <q-page>
    <div class="button-holder">
      <div class="rounded-btn" @click="$router.push('/poshu')">
        <img src="../assets/cow5.png" style="width:100px; height:100px" />
        <span class="button-text">poshu palon</span>
      </div>
      <div class="rounded-btn">
        <img src="../assets/cow5.png" style="width:100px; height:100px" />
        <span class="button-text">tets</span>
      </div>
    </div>
    <div class="button-holder">
      <div class="rounded-btn">
        <img src="../assets/cow5.png" style="width:100px; height:100px" />
        <span class="button-text">tets</span>
      </div>
      <div class="rounded-btn">
        <img src="../assets/cow5.png" style="width:100px; height:100px" />
        <span class="button-text">tets</span>
      </div>
    </div>
  </q-page>
</template>

<script>
export default {
  name: "PageIndex",
  components: {},
};
</script>
<style scoped>
.rounded-btn {
  display: flex;
  justify-content: center;
  justify-items: s;
  align-items: center;
  width: 150px;
  height: 150px;
  overflow: hidden;
  border-radius: 50%;
  position: relative;
  border: 5px solid rgb(214, 214, 214);
}
.button-text {
  position: absolute;
  bottom: 10px;
}
.button-holder {
  display: flex;
  justify-content: space-around;
  margin-top: 10px;
}
</style>
