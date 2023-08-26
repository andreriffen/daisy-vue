<template>
<main>
    <div id="content" class="mx-auto max-w-9xl sm:px-6 sm:pt-20 lg:px-8 lg:pt-16 lg:pb-6">
      <div class="hero min-h-screen" style="background-image: url(../assets/hero-bg.jpg);">
        <div class="hero-overlay bg-opacity-40"></div>
        <div class="hero-content text-center text-neutral-content">
          <div class="max-w-md">
            <h1 class="mb-5 text-5xl font-bold">Greetings!</h1>
              <p class="mb-5">Riffen aqui. Estou testando esta bagaça pra ver/mostrar/testar como se comporta a natureza de um framework como o Vue 3 hospedado no Github Pages...</p><p> Também para mostrar para meus amigos e colegas desenvolvedores. Não tem muito conteúdo aqui, apenas um layoutzinho bonito. 👻</p> <br>
              <button class="btn btn-neutral"><a href="#who-am-i"> Tá bonito! </a></button>
          </div>
        </div>
      </div>
    </div>
    
    <!-- glass card-->
  <div id="who-am-i" class="card w-full glass p-5">
    <figure><img src="/assets/eu2.jpg" class="w-96 h-96" alt="Personagem Puro Osso, de 'Billy e Mandy', sentado mexendo no computador com um semblante mal-humorado."/></figure>
    <div class="card-body">
      <h2 class="card-title">Só tem isso?</h2>
        <p>Parece pouca coisa, mas pra fazer esta bagaça demorou um pouco pra eu entender o funcionamento. Principalmente as diferenças entre Common JS e ES Modules 6/7. (apanhei? sim, um pouco!) No pain, No Gain.</p>
        <div class="card-actions justify-start">
        <button class="btn btn-neutral"><p class="ml-2"><a href="https://github.com/andreriffen">Perfil GitHub</a></p></button>
    </div>
    </div>
  </div>

  </main>
</template>
<script>
export default {
  name: "Main"
};
</script>
<style>
</style>