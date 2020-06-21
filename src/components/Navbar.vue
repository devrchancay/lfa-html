<template>
  <header>
    <navbar>
      <nav class="container mx-auto flex items-center justify-between my-4 px-5">
        <ul class="flex items-center space-x-10">
          <li>
            <a href>
              <img style="min-width: 27px;" src="../assets/burger.svg" class="mr-2" alt />
            </a>
          </li>
          <li class="hidden lg:block">
            <a class="text-blue-800 uppercase italic font-bold flex items-center" href>Inicio</a>
          </li>
          <li class="hidden lg:block">
            <a class="text-blue-800 uppercase italic font-bold flex items-center" href>Ofertas</a>
          </li>
          <li class="hidden lg:block">
            <a class="text-blue-800 uppercase italic font-bold flex items-center" href>Catalogo</a>
          </li>
          <li class="hidden lg:block">
            <a class="text-blue-800 uppercase italic font-bold flex items-center" href>Expertos</a>
          </li>
        </ul>
        <a href class="mx-10">
          <img src="../assets/logo.svg" alt />
        </a>
        <ul class="flex items-center space-x-10">
          <li class="hidden lg:block">
            <a class="text-blue-800 uppercase italic font-bold flex items-center" href>
              <img src="../assets/zoom.svg" class="mr-2" alt />Buscar
            </a>
          </li>
          <li class="hidden lg:block">
            <a
              class="text-blue-800 whitespace-no-wrap uppercase italic font-bold flex items-center"
              href
            >
              <img src="../assets/heart.svg" class="mr-2" alt />Me Gusta
            </a>
          </li>
          <li>
            <a class="text-blue-800 uppercase italic font-bold flex items-center" href>
              <img src="../assets/cart.svg" class="mr-2" alt />(1)
            </a>
          </li>
          <li>
            <a class="text-blue-800 uppercase italic font-bold flex items-center" href>
              <img style="min-width: 2x;" src="../assets/user.svg" class="mr-2" alt />
            </a>
          </li>
        </ul>
      </nav>
    </navbar>
  </header>
</template>

<script>
export default {
  name: 'HelloWorld'
};
</script>
