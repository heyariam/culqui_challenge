<template>
  <div class="main-cont flex w-1/2 h-3/4 ">
    <div class="lil-cont flex flex-col items-left h-full w-full">
      <img class="object-cover mb-1" src="../../assets/Photo.png" alt="image">
      <div class=" small-cont p-10 h-2/4">
          <img class="culqui-logo mb-5" src="../../assets/Logo.png" alt="image">
            <div class="">
              <p class="text-title">Dale más power ⚡ a tus empleados hoy 💪</p>
            <p class="subtitle">Te ayudamos a gestionarlos de manera más sencilla</p>
          </div>
        </div>
      </div>
    </div>
</template>

<script>
export default {
  name: 'Sideimage',
}
</script>

<style scoped>

.lil-cont{
  background: #27A376;
}
.culqui-logo{
  width: 117px;
  height: 36px;
}
.text-title{
  font-weight: 800px;
  font-size: 48px;
  line-height: 57.5px;
  text-align: left;
  margin: 0px 20px 40px;
  color: #fff;
}
.subtitle{
  font-weight: 400px;
  font-size: 18px;
  line-height: 27px;
  text-align: left;
  margin: 0px 20px 40px;
  color: #fff;
}

.small-cont{
  background: #111827;
}
</style>