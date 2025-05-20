<script>
import { RouterLink, RouterView } from 'vue-router';
</script>

<template>
    <div class="max-w-7xl mx-auto bg-[url(/src/assets/images/BG2.jpg)] text-white h-screen p-4 w-full">
        <div class="py-8">
            <p class="text-white text-lg">Inicia sesión</p>
        </div>
        <div class="bg-white text-black p-6 flex flex-col items-start space-y-2">
            <input  id="email" class="w-full border border-slate-300 p-4 text-md" type="email" placeholder="email" name="">
            <input  id="pass" class="w-full border border-slate-300 p-4 text-md" type="password" name="" placeholder="contraseña">
            <button @click="login" class="bg-[#38b6ff] text-black px-4 py-2 w-full text-lg hover:bg-[#ff8038] transition-all">Entrar</button>
        </div>
        <div class="py-8">
            <p class="text-white text-lg">o crea una cuenta</p>
        </div>
            <div class="bg-white text-black p-6 flex flex-col items-start space-y-2">
                <RouterLink class="bg-[#38b6ff] text-black px-4 py-2 w-full text-lg hover:bg-[#ff8038] transition-all text-center" to="/register">Registrarse</RouterLink>
            </div>
    </div>
</template>
