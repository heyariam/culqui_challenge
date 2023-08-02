<template>
  <div class="container">
        <p>image goes here</p>
    <main>
      <section class="absolute w-full h-full">
        <div
          class="absolute top-0 w-full h-full bg-gray-900"
        ></div>
        <div class="container mx-auto px-4 h-full">
          <div class="flex content-center items-center justify-center h-full">
            <div class="w-full lg:w-4/12 px-4">
              <div
                class="relative flex flex-col min-w-0 break-words w-full mb-6 shadow-lg rounded-lg bg-gray-300 border-0"
              >
                <div class="rounded-t mb-0 px-6 py-6">
                  <div class="text-center mb-3">
                    <h6 class="text-gray-600 text-sm font-bold">
                      Iniciar Sesión
                    </h6>
                  </div>
                </div>
                <div class="flex-auto px-4 lg:px-10 py-10 pt-0">
                  <form>
                    <div class="relative w-full mb-3">
                      <label
                        class="block uppercase text-gray-700 text-xs font-bold mb-2"
                        for="grid-password"
                        >Correo Electrónico</label
                      > <input type="email" placeholder= "Ingresa el correo electrónico" v-model="email" />
                    </div>
                    <div class="relative w-full mb-3">
                      <label
                        class="block uppercase text-gray-700 text-xs font-bold mb-2"
                        for="grid-password"
                        >Contraseña</label
                      ><input type="password" placeholder= "Ingresa la contraseña" v-model="password" />
                    </div>
                      <div class="submit-button">
                        <input type="button" value="Iniciar Sesión">
                    </div>
                  </form>
                </div>
              </div>
              <div class="flex flex-wrap mt-6">
                <div class="w-1/2 text-right"><p>¿Eres nuevo aquí?
                  <a href="#pablo" class="text-gray-300"
                    ><small>Crea una cuenta</small></a
                  ></p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
    </main>
  </div>
</template>

<script>

  export default {
  name: 'LoginForm',
}
</script>


<style scoped>
body{
  background:#f8fafc;
}

.content{
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
    }
    
    .login-container{
        background: white;
        position: relative;
        border-radius: 5px;
        display: flex;
        width: 70vw;
        height: 70vh;
        box-shadow: 0 19px 38px rgba(0, 0, 0, 0.07);
        transition: .4s;
    }
    
    
    .login{
        transition: .4s;
       
    }
    
    .login#login-form{
        width: 50%;
        display: block;
        padding: 15px;
        align-items: center;
        text-align: center;
        position: relative;
        margin-top: 20px;
    }
    
    .login#login-bg{
        width: 50%;
        display: inline-flex;
        background-size: cover;
        background-position: center center;
        float: right;
        border-radius: 0 5px 5px 0;
    }
    

    .form-title{
       position: absolute;
       top: 11%;
       left: 0;
       right: 0;
       text-align: center;
       color: #dedede;
       font-size: 2.2em;

       line-height: 1.4;
       margin-top: -24px;
    }
   
    
    .form-container{
        padding: 25px 10px;
        border-radius: 5px;
        width: 80%;
        text-align: left;
        margin-top: 70px;
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
    }
    
    
    label{
        font-size: .7em;
        color: #7392ff;
        margin: 0px 0 !important;
        margin-left: 4px !important;
    }
    
    input{
        background: #f8fafc ;
        border: 0;
        width: 100%;
        display: block;
        padding: 10px 15px;
        border-radius: 5px;
        margin-bottom: 20px !important;
        outline: 0;
        transition: .4s;
    }
    
    input::placeholder{
        opacity: .4;
    }
    
    .submit-button{
        display: flex;
    }
    
    .submit-button input{
        width: 50%;
        text-align: center;
        color: white;
        transition: .2s;
    }
    
    .submit-button input:hover{
        opacity: .7;
    }
    
    .submit-button input:nth-of-type(1){
        border-radius: 5px 0 0 5px;
        background: #54a0ff;
    }
    
    .submit-button input:nth-of-type(2){
        border-radius: 0 5px 5px 0;
        background: #c8d6e5;
    }
    
</style>