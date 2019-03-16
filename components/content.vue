<template>
  <div 
    class="card">
    <img 
      src="~/assets/pic.jpg"
      class="card-img-top" 
      alt="Cover Image">
    <div 
      class="card-img-overlay"><a 
        href="#borrowBook" 
        class="card-link">
      <fa :icon="fas.faPlus" />Borrow</a>
    </div>
    <div class="card-body">
      <div class="card-title">only time will tell</div>
      <h2 class="card-subtitle mb-2 text-muted">Jeffrey Archer</h2>
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
