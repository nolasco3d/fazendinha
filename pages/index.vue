<template>
  <section class="h-[80vh] bg-gray-200 flex flex-col items-center justify-center">
    <div>
      <h4 class="text-sm">text here of discount</h4>
      <h2 class="text-4xl mb-4">Tudo para seu pet <br/>você encontra aqui</h2>
      <button class="btn">Ver mais</button>
    </div>
  </section>

  <section class="text-center py-16">
    <!--  TITLE SECTION  -->
    <div class="px-4 mb-8">
      <h4 class="text-sm">Categorias</h4>
      <h2 class="text-4xl mb-4">Artigos para todos os pets</h2>
    </div>

    <div class="flex flex-wrap justify-center gap-6 p-4">
      <!--   ANIMAL PHOTO   -->
      <div class="flex flex-col items-center gap-6">
        <div class="w-44 h-44 rounded-full bg-gray-200 ">
        </div>
        <span>Animal</span>
      </div>
      <!--   ANIMAL PHOTO   -->
      <div class="flex flex-col items-center gap-6">
        <div class="w-44 h-44 rounded-full bg-gray-200 ">
        </div>
        <span>Animal</span>
      </div>
      <!--   ANIMAL PHOTO   -->
      <div class="flex flex-col items-center gap-6">
        <div class="w-44 h-44 rounded-full bg-gray-200 ">
        </div>
        <span>Animal</span>
      </div>
      <!--   ANIMAL PHOTO   -->
      <div class="flex flex-col items-center gap-6">
        <div class="w-44 h-44 rounded-full bg-gray-200 ">
        </div>
        <span>Animal</span>
      </div>
    </div>
  </section>

  <section class="container mx-auto flex flex-col justify-around gap-4">
    <div class="bg-primary text-white flex basis-[320px] p-4 items-center justify-center h-[30px]">
      <h3 class="text-5xl">BANNER 1</h3>
    </div>
    <div class="bg-primary text-white flex basis-[320px] p-4 items-center justify-center h-[30px]">
      <h3 class="text-5xl">BANNER 2</h3>
    </div>
  </section>

  <section class="container mx-auto flex flex-col gap-4 text-center py-16">
    <!--  TITLE SECTION  -->
    <div class="px-4 mb-8">
      <h4 class="text-sm">Mais procurados</h4>
      <h2 class="text-4xl mb-4">Nossos Produtos</h2>
    </div>

    <div class="grid grid-cols-2 gap-6 p-6">
      <!--   PRODUCT ITEM   -->
      <div class="flex flex-col justify-center">
        <div class="bg-gray-200 h-[240px]">

        </div>
        <h5>Product name here</h5>
        <span>R$ 23,90</span>
      </div>

      <!--   PRODUCT ITEM   -->
      <div class="flex flex-col justify-center">
        <div class="bg-gray-200 h-[240px]">

        </div>
        <h5>Product name here</h5>
        <span>R$ 23,90</span>
      </div>

      <!--   PRODUCT ITEM   -->
      <div class="flex flex-col justify-center">
        <div class="bg-gray-200 h-[240px]">

        </div>
        <h5>Product name here</h5>
        <span>R$ 23,90</span>
      </div>

      <!--   PRODUCT ITEM   -->
      <div class="flex flex-col justify-center">
        <div class="bg-gray-200 h-[240px]">

        </div>
        <h5>Product name here</h5>
        <span>R$ 23,90</span>
      </div>
    </div>
  </section>


  <section class="py-16 text-center bg-gray-200 px-4">
    <div class="mb-8">
      <span class="text-xs">IMAGE BANNER</span>
      <h4 class="text-2xl">Oferta Limitada!</h4>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Accusantium aliquid animi atque debitis distinctio harum illo quaerat quam quo quod tenetur voluptate, voluptatem?</p>
    </div>

    <button class="btn btn-primary rounded-full">Aproveitar Oferta</button>
  </section>
</template>

<script>
export default {
  name: "index"
}
</script>

<style scoped>
/** {*/
/*  @apply border border-red-400 border-dotted;*/
/*}*/
</style>