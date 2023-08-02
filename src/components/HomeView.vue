<template>
  <div class="container mx-auto">

  <div class="bg-blue-100 shadow-lg overflow-hidden rounded-xl w-[50%] h-[32em] z-50">
    <div class="flex space-between items-start">
        <div class="image-container lg:w-[50%] xs:hidden">
          <img src="../assets/onboarding.png" alt="image"/>
        </div>
        <div class="lg:w-[50%] xs:w-full sm:w-full px-8 py-10">
            <div>
                <b class="text-2xl text-gray-800">Iniciar sesión</b>
            </div>
            <br>
            <div>
                <div class="flex flex-col">
                    <span class="font-bold mb-1 text-[12px]">
                        <i class="fa fa-user-circle-o"></i> Email
                    </span>
                    <input type="email" v-model="username" name="email" placeholder="ejemplo@gmail.com" class="p-3 rounded-lg border border-gray-300 w-full" />
                </div>
            </div>
            <br>
            <div class="mb-1">
                <div class="flex flex-col">
                    <span class="font-bold mb-1 text-[12px]">
                        <i class="fa fa-key"></i> Contraseña
                    </span>
                    <input type="password" v-model="password" name="password" placeholder="escriba su clave" class="p-3 rounded-lg border border-gray-300 w-full" />
                </div>
            </div>
            <br>
            <button v-on:click="validateFields()" class="transition p-3 w-full bg-blue-500 hover:bg-blue-600 text-white rounded-lg mb-4">
                continuar <i class="fa fa-send"></i>
            </button>
            <div class="text-center mb-3">
                <span class="text-[12px] text-gray-600">¿Eres neuvo aquí? 
                    <a href="#" class="text-[12px] text-blue-500 hover:text-blue-700 font-bold">
                        Crear cuenta
                    </a>
                </span>
            </div>
        
        </div>
    </div>
</div>


</div>

</template>

<style scoped>
   .image-container {
        background-position: center;
        background-size: cover;
    }
</style>




<script>

export default {
  name: 'HomeView',
  components: {

  }
}
</script>
