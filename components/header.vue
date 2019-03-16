<template>
  <div>


    <div 
      id="header" 
      class="container"
    >
      <h1 
        id="home" 
        class="text-left ml-3 mt-4"
      >BARTER</h1>
      <div 
        class="searchbar float-right">
        <input 
          class="search_input" 
          type="text" 
          name="" 
          placeholder="">
        <a 
          href="#" 
          class="search_icon"><fa :icon="fas.faSearch"/>
        </a>
      </div>
      <nav id="nav">
        <button 
          id="nav-icon" 
          class="nav-icon float-right"><span/></button>
        <ul>
          <li><nuxt-link to="/">borrow</nuxt-link></li>
          <li><nuxt-link to="/lend">lend</nuxt-link></li>
          <li><nuxt-link to="/about">about</nuxt-link></li>
          <li><nuxt-link to="/contact">contact</nuxt-link></li>
        </ul>
      </nav>
    </div>
  </div>
</template>

<script>
import { fas } from '@fortawesome/free-solid-svg-icons'

export default {
  computed: {
    fas() {
      return fas
    }
  }
}
</script>
