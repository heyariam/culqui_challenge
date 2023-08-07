<template>
<div id="wrapper" class="flex h-screen bg-grey-lightest sm:flex-col md:flex-row font-light w-full">
        <div id="sidebar" class="bg-orange-darker md:w-64 overflow-y-scroll sm:w-screen">
            <header class="flex justify-between items-center border-b border-orange-darkest pt-8 pb-8 pl-6 pr-6">
                <div id="logo">
                    <a href="#" class="no-underline text-black md:text-2xl sm:text-4xl font-bold">
                        <img src="#" width="120" alt="">
                   culqui
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
                <li class="flex justify-between block">
                    <a href="#" class="no-underline text-black block h-full w-full border-b border-orange-darkest px-8 py-4 hover:text-orange">
                        <i class="fa fa-user mr-2" aria-hidden="true"></i>
                        Account
                        <i class="fa fa-angle-right float-right" aria-hidden="true"></i>
                    </a>
                </li>
            </ul>
        </div>
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