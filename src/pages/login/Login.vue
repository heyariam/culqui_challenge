<template>

   <div class="w-full flex flex-wrap">
<!--image-->

  <div class="w-1/2 shadow-2xl">
      <img class="object-cover w-full h-screen hidden md:block" src="../../assets/Onboarding.png" alt="lol">
    </div>
<!--login -->
<div class="w-full md:w-1/2 flex flex-col">

    <div class="flex flex-col justify-center md:justify-start my-auto pt-8 md:pt-0 px-8 md:px-24 lg:px-32">
        <p class="text-center text-3xl">Iniciar Sesión</p>
        <form class="flex flex-col pt-3 md:pt-8" @submit.prevent="handleLogin">
            <div class="flex flex-col pt-4">
                <label for="email" class="text-lg">Correo Electrónico</label>
                <input v-model="correo" type="email" id="email" placeholder="Ingresa el correo electrónico" class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 mt-1 leading-tight focus:outline-none focus:shadow-outline">
            </div>

            <div class="flex flex-col pt-4">
                <label for="password" class="text-lg">Contraseña</label>
                <input v-model="password" type="password" id="password" placeholder="Ingresa la contraseña" class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 mt-1 leading-tight focus:outline-none focus:shadow-outline">
            </div>

            <input type="submit" value="Iniciar Sesión" class="bg-black text-white font-bold text-lg hover:bg-gray-700 p-2 mt-8" >
        </form>
        <div class="text-center pt-12 pb-12">
            <p>¿Eres nuevo aquí? <a href="register.html" class="underline font-semibold">Crea una cuenta</a></p>
        </div>
    </div>
    <Footer />
</div>

</div>
</template>

<script>
import Footer from './Footer.vue';

export default {
  name: 'LoginForm',
  data() {
    return {
      correo: '',
      password: ''
    };
  },
  methods: {
    async handleLogin() {
      const url = 'https://fepruebatecnicaculqi-backend-production.up.railway.app/auth/login';
      const data = {
        correo: this.correo,
        password: this.password
      };

      try {
        const response = await fetch(url, {
          method: 'POST',
          headers: {
            'Content-Type': 'application/json'
          },
          body: JSON.stringify(data)
        });

        const responseData = await response.json();
        console.log(responseData);
      } catch (error) {
        console.error('Error', error);
      }
    }
  }
}
</script>


<style scoped>
body{
  background:#f8fafc;
}
    
</style>