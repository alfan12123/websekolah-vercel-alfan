<template>
  <nav>
    <h3>Alfan - Onlineshop📮</h3>
 <hr />
    <RouterLink to="/">Landing</RouterLink>|
    <RouterLink to="/product">Product</RouterLink> |
    <RouterLink to="/about">About</RouterLink>|
    <RouterLink to="/contact">Contact</RouterLink> 
    </nav>

 
</template>

<style scoped>
nav {
  display: flex;
  align-items: center;
  padding: 1rem;
  background-color: #ff0000;
  color: var(--color-text);
  border-radius: 10px;
} 
.atas{
background-color: #0d3b97;
  color: #fffdfd;
  padding: 10px;
  border-radius: 10px;
}   
h3 {
  color: #fdfeff;
  padding: 10px;
  
}
</style>
