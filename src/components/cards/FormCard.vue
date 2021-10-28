<template>
    <div class="card"> 
      <form id="form" class="form1" @submit.prevent="onFormSubmit">
        <h1>Contacts</h1>
        <ul>
          <input
            required
            type="text"
            placeholder="Name: "
            :readonly="false"
          />
        </ul>

        <ul>
          <input
            type="text"
            placeholder="email"
            :readonly="false"
          />
        </ul>

        <ul><textarea required placeholder="what do you think about us?"></textarea></ul>
        
        <ul><button id="submitButton" type="submit">Send</button></ul>
          
        <label for="checkbox">capcha</label>

        <input
          required
          id="checkbox"
          type="checkbox"
          :value="true"
        />
      </form>
    </div>
</template>

<script>
export default {
  name: 'FormCard',
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>



input{
  display: inline-block;
  padding: auto;
  margin: 10px;
}

form{
  margin: 10px;
}

div{
  box-shadow: 5px 2px 2px rgba(0, 0, 0, 0.459);
}

</style>