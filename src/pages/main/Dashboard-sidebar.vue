<template>
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
</template>

<script>

export default {
  name: 'DashSideBar'

}
</script>
