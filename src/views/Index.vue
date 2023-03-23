<template>
    <header>

    <div class="wrapper">

      <nav>
        <RouterLink to="/">Home</RouterLink> 
        <RouterLink to="/about">About</RouterLink>
        <RouterLink to="/product">Product</RouterLink>
        <button @click="$emit('checkout')">Go To Check Out</button>

      </nav>
    </div>
  </header>
  
 <RouterView />
</template>