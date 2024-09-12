<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <h1>{{ msg }}</h1>

   <form action="input">
    <input type="text" class="user-month"> 
    <button>
      Submit You Birth Month
    </button>
   </form>
   
</template>
<script>
const userMonth = document.getElementsByClassName('user-month')
 
if(userMonth == "January"){
  alert("Belongs to Ravenclaw")
 }
else if(userMonth == "Feburary")
   alert("Belongs to Ravenclaw")

else if(userMonth == "March")
   alert("Belongs to Ravenclaw")

else if(userMonth == "April")
   alert("Belongs to Ravenclaw")

else if(userMonth == "May")
   alert("Belongs to Ravenclaw")

else if(userMonth == "June")
   alert("Belongs to Ravenclaw")

else if(userMonth == "July")
   alert("Belongs to Ravenclaw")

else if(userMonth == "August")
   alert("Belongs to Ravenclaw")
   
else if(userMonth == "September")
   alert("Belongs to Ravenclaw")


</script>
<style scoped>
.read-the-docs {
  color: #888;
}
</style>
