<template>
    <div id="wrapper" class="flex h-screen bg-white sm:flex-col md:flex-row font-light w-full">
        <aside> 
        <div id="sidebar" class="bg-orange-darker md:w-64 overflow-y-scroll sm:w-screen">
            <header class="flex justify-between items-center border-b border-orange-darkest pt-8 pb-8 pl-6 pr-6">
                <div id="logo">
                    <a href="#" class="no-underline text-black md:text-2xl sm:text-4xl font-bold">
                        <img src="./../../assets/logo.png" width="120" alt="">
                    </a>
                </div>
            </header>
            <ul id="menu" class="flex flex-col list-reset sm:hidden md:block">
                <li class="block">
                    <a href="#" class="no-underline text-black block h-full w-full border-b border-orange-darkest px-8 py-4 hover:text-orange">
                        <i class="fa fa-tachometer mr-2" aria-hidden="true"></i>
                        Dashboard
                    </a>
                </li>
                <li class="">
                    <a href="#" class="no-underline text-black block h-full w-full border-b border-orange-darkest px-8 py-4 hover:text-orange">
                        <i class="fa fa-user mr-2" aria-hidden="true"></i>
                        Account
                        <i class="fa fa-angle-right float-right" aria-hidden="true"></i>
                    </a>
                </li>
            </ul>
            <ul>
                <li>
                    cerrar sewion
                </li>
            </ul>
        </div>
    </aside>

    <section> 
        <nav>
        <div id="content" class="px-8 bg-transparent flex-grow flex-shrink flex-auto overflow-y-scroll">
            <div id="info" class="border-b border-grey-light h-24">
                <div class="flex justify-between flex-grow items-center border-b h-24">
                    <div class="flex">
                        <ul class="flex list-reset text-black">
                           
                        </ul>
                    </div>
                    <div class="flex">
                        <ul class="flex list-reset text-black">
                            <li class="px-4">
                                <span class="text-sm">
                                    roudned icon here
                                </span>
                            </li>
                            <li class="border-l px-4">
                                <span class="text-sm">
                                    name here
                                </span>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </nav>
    <main class="bg-grey-lightest">
        <div class="main-card flex-1 bg-white p-4 shadow rounded-lg md:w-1/2 margin:15px">
 
            <div> 
                 <h2 class="text-gray-500 text-lg font-semibold pb-1">Empleados</h2>
                    <div class="my-1">      
                        <div class="relative max-w-md w-full">
                            <div class="absolute top-1 left-2 inline-flex items-center p-2">
                                <i class="fas fa-search text-gray-400"></i>
                            </div>
                         <input class="w-full h-10 pl-10 pr-4 py-1 text-base placeholder-gray-500 border rounded-full focus:shadow-outline" type="Buscar" placeholder="Buscar...">
                        </div>
                    </div> <!-- Espacio de separación -->
                    <div>   
                        <div class="relative max-w-md w-full">
                            <div class="absolute top-1 left-2 inline-flex items-center p-2">
                                <i class="fas fa-search text-gray-400"></i>
                            </div>
                         <input class="w-full h-10 pl-10 pr-4 py-1 text-base placeholder-gray-500 border rounded-full focus:shadow-outline" type="Buscar" placeholder="Buscar...">
                        </div>

                    </div>
                    <div class="bg-gradient-to-r from-cyan-300 to-cyan-500 h-px mb-6"></div> <!-- Línea con gradiente -->
                  
                </div>

                <div>
                    <div class="mt-8 bg-white p-4 shadow rounded-lg">
                <div class="bg-white p-4 rounded-md mt-4">
                    <h2 class="text-gray-500 text-lg font-semibold pb-4">Transacciones</h2>
                    <div class="my-1"></div> <!-- Espacio de separación -->
                    <div class="bg-gradient-to-r from-cyan-300 to-cyan-500 h-px mb-6"></div> <!-- Línea con gradiente -->
                    <table class="w-full table-auto text-sm">
                        <thead>
                            <tr class="text-sm leading-normal">
                                <th class="py-2 px-4 bg-grey-lightest font-bold text-sm text-grey-light border-b border-grey-light">Nombre</th>
                                <th class="py-2 px-4 bg-grey-lightest font-bold text-sm text-grey-light border-b border-grey-light">Nombre cargo</th>
                                <th class="py-2 px-4 bg-grey-lightest font-bold text-sm text-grey-light border-b border-grey-light text-right">Departamento</th>
                                <th class="py-2 px-4 bg-grey-lightest font-bold text-sm text-grey-light border-b border-grey-light">Oficina</th>
                                <th class="py-2 px-4 bg-grey-lightest font-bold text-sm text-grey-light border-b border-grey-light">Cuenta</th>
                                <th class="py-2 px-4 bg-grey-lightest font-bold text-sm text-grey-light border-b border-grey-light text-right">Acciones</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr class="hover:bg-grey-lighter">
                                <td class="py-2 px-4 border-b border-grey-light">Carlos Sánchez</td>
                                <td class="py-2 px-4 border-b border-grey-light">27/07/2023</td>
                                <td class="py-2 px-4 border-b border-grey-light text-right">$1500</td>
                                <td class="py-2 px-4 border-b border-grey-light text-right">$1500</td>
                                <td class="py-2 px-4 border-b border-grey-light text-right">$1500</td>
                                <td class="py-2 px-4 border-b border-grey-light text-right">
                                    <div>
                                        <button type="button" class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-blue-600 dark:hover:bg-blue-700 focus:outline-none dark:focus:ring-blue-800">Default</button>
                                    </div>
                                    <div>
                                        <button type="button" class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-blue-600 dark:hover:bg-blue-700 focus:outline-none dark:focus:ring-blue-800">Default</button>
                                    </div>     
                                    <div>
                                        <button type="button" class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-blue-600 dark:hover:bg-blue-700 focus:outline-none dark:focus:ring-blue-800">Default</button>
                                    </div>
                                </td>
                            </tr>
                        </tbody>
                    </table>
                    <!-- Botón "Ver más" para la tabla de Transacciones -->
                    <div class="text-right mt-4">         
                            <button class="bg-cyan-500 hover:bg-cyan-600 text-white font-semibold py-2 px-4 rounded">
                                Ver más
                            </button>
                        </div>
                    </div>
                </div>
                    </div>
     
       
 
        </div>           
    </main>
</section>
</div>

   

</template>


<script>

export default {
  name: 'DashboardPanel'
}
</script>



<style>
*{
    list-style: none;
    text-decoration: none;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Open Sans', sans-serif;
}

body{
    background: #f5f6fa;
}

/* side bar style */

/* nav bar style */


</style>