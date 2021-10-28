<template>
  <div class="hello">
    <InfoCard />
    <FormCard />
  </div>
</template>
  
<script>
import InfoCard from '../cards/InfoCard.vue'
import FormCard from "../cards/FormCard.vue"

export default {
  components: { InfoCard, FormCard },
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

div{
  box-shadow: 5px 2px 2px rgba(0, 0, 0, 0.459);
}
.card{
  padding: 25px; 
  border-radius: 10px; 
  max-height: 500px;
  min-height: 100px;
  width: 310px;
  max-width: 500px;
  margin-top: 70px;
  background-color: rgb(0, 104, 0);
  float: left;
  margin-left: 260px;
}

</style>

