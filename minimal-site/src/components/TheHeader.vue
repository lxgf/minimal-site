<template>
  <header class="flex justify-between bg-blue-400 text-white w-full h-24">
    <div class="container flex mx-auto">
      <nav class="flex my-auto w-full font-normal uppercase">
        <ul class="flex flex-row justify-between my-auto w-full max-w-lg">
          <li><a class="transition duration-300 cursor-pointer hover:text-blue-600">Главная</a></li>
          <li><a class="cursor-pointer">О нас</a></li>
          <li><a class="cursor-pointer">Донат</a></li>
          <li><a class="cursor-pointer">F.A.Q.</a></li>
          <li><a class="cursor-pointer">Контакты</a></li>
        </ul>
      </nav>
      <div class="flex flex-row my-auto">
        <div class="flex cursor-pointer font-normal uppercase mr-2">IP:</div>
        <div class="flex cursor-pointer font-semibold uppercase ip">176.62.77.215</div>
      </div>
    </div>
  </header>
</template>

<style>
@import './../assets/css/header.css';
</style>