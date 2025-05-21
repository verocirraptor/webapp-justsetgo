<script>

</script>


<template>
    <div class="max-w-7xl mx-auto bg-[url(/src/assets/images/BG2.jpg)] text-white h-screen p-4 w-full">
        <div class="py-8">
            <p class="text-white text-lg">Crea una cuenta</p>
        </div>
        <div class="bg-white text-black p-6 flex flex-col items-start space-y-2">
            <input id="email" class="w-full border border-slate-300 p-4 text-md" type="email" placeholder="email" name="">
            <input class="w-full border border-slate-300 p-4 text-md" type="password" name="" placeholder="contraseña">
            <button @click="register" class="bg-[#38b6ff] text-black px-4 py-2 w-full text-lg hover:bg-[#ff8038] transition-all" to="/dashboard">Registrarse</button>
            <!--<p v-if="error" class="text-red-500 p-3 bg-red-100 w-full">Error: {{ error }}</p>-->
        </div>
    </div>
</template>