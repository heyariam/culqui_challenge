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
    <main class= "p-16">
        <div class="main-card flex-1 p-4 shadow rounded-lg">
 
            <div> 
                 <h2 class="text-gray-500 text-lg font-semibold pb-1">Empleados</h2>
                 <div class="my-1 flex space-x-4">
                    <div class="search-bar flex-grow">
                        <label class="relative block">
                            <span class="absolute inset-y-0 right-0 flex items-center pr-2">
                                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M21 21l-5.197-5.197m0 0A7.5 7.5 0 105.196 5.196a7.5 7.5 0 0010.607 10.607z" />
                                </svg>
                            </span>
                            <input class="placeholder:text-slate-400 block bg-white w-full border border-slate-300 rounded-md py-2 pl-3 pr-9 shadow-sm focus:outline-none focus:border-sky-500 focus:ring-sky-500 focus:ring-1 sm:text-sm" placeholder="Buscar empleado" type="text" name="search"/>
                        </label>
                    </div>
                    
                    <div class="icon relative max-w-md w-full">
                        <div>
                          
                        </div>
                    </div>
                </div>


            </div>
                <div>
                    <div class="mt-8 bg-white p-4">
                        <div class="bg-white p-4 rounded-md mt-4">
                            <h2 class="text-gray-500 text-lg font-semibold pb-4">Transacciones</h2>
                    <div class="grid-cols-5">
                        <table class="w-full table-fixed text-sm"> 
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
                                        <button type="button" class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 font-medium rounded-md text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-blue-600 dark:hover:bg-blue-700 focus:outline-none dark:focus:ring-blue-800">
                                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                                                <path stroke-linecap="round" stroke-linejoin="round" d="M2.036 12.322a1.012 1.012 0 010-.639C3.423 7.51 7.36 4.5 12 4.5c4.638 0 8.573 3.007 9.963 7.178.07.207.07.431 0 .639C20.577 16.49 16.64 19.5 12 19.5c-4.638 0-8.573-3.007-9.963-7.178z" />
                                                <path stroke-linecap="round" stroke-linejoin="round" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z" />
                                            </svg>

                                        </button>
                                    </div>
                                    <div>
                                        <button type="button" class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-blue-600 dark:hover:bg-blue-700 focus:outline-none dark:focus:ring-blue-800">
                                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                                                <path stroke-linecap="round" stroke-linejoin="round" d="M16.862 4.487l1.687-1.688a1.875 1.875 0 112.652 2.652L6.832 19.82a4.5 4.5 0 01-1.897 1.13l-2.685.8.8-2.685a4.5 4.5 0 011.13-1.897L16.863 4.487zm0 0L19.5 7.125" />
                                            </svg>
                                        </button>
                                    </div>     
                                    <div>
                                        <button type="button" class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-blue-600 dark:hover:bg-blue-700 focus:outline-none dark:focus:ring-blue-800">
                                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                                                <path stroke-linecap="round" stroke-linejoin="round" d="M14.74 9l-.346 9m-4.788 0L9.26 9m9.968-3.21c.342.052.682.107 1.022.166m-1.022-.165L18.16 19.673a2.25 2.25 0 01-2.244 2.077H8.084a2.25 2.25 0 01-2.244-2.077L4.772 5.79m14.456 0a48.108 48.108 0 00-3.478-.397m-12 .562c.34-.059.68-.114 1.022-.165m0 0a48.11 48.11 0 013.478-.397m7.5 0v-.916c0-1.18-.91-2.164-2.09-2.201a51.964 51.964 0 00-3.32 0c-1.18.037-2.09 1.022-2.09 2.201v.916m7.5 0a48.667 48.667 0 00-7.5 0" />
                                            </svg>

                                        </button>
                                    </div>
                                </td>
                            </tr>
                        </tbody>
                    </table>
                </div>
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
},

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


</style>