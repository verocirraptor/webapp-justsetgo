<script>
import { RouterLink, RouterView } from 'vue-router';


</script>

<template>
  <header>

    <div class="max-w-7xl mx-auto py-4 px-4 sm:px-6 lg:px-8 bg-slate-200 border-b border-slate-400 shadow">
      <nav class="flex space-x-4">
        <RouterLink class="hover:bg-yellow-500 transition-all px-2 py-1" to="/">Home</RouterLink>
        <RouterLink class="hover:bg-yellow-500 transition-all px-2 py-1" to="/login">Login</RouterLink>
        <RouterLink class="hover:bg-yellow-500 transition-all px-2 py-1" to="/register">Register</RouterLink>
        <RouterLink class="hover:bg-yellow-500 transition-all px-2 py-1" to="/dashboard">Dashboard</RouterLink>
        <button class="hover:bg-yellow-500 transition-all px-2 py-1" @click="logout">Logout</button>
      </nav>
    </div>

  </header>

  <RouterView />
</template>
