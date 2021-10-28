<template>
    <div class="card">
      <h1>Personal card</h1>
      <h3>My name is:</h3>
      <ul>
        <li>Vyaznikov</li>
        <li>Pavel</li>
        <li>Andreevich</li>
      </ul>
      <h3>Thats me!</h3>
      <img alt="Vue logo" src="../../assets/me.png" />
      <h3>Group number</h3>
      <p>BSBO-04-19</p>
      <h3>Skills:</h3>
      <ul>
        <li>Studing at RTU MIREA</li>
        <li>Know some Machine Learning</li>
        <li>Know some Python</li>
        <li>Know some C#</li>
      </ul>
    </div>
</template>

<script>
export default {
  name: 'InfoCard',
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
img {
  width: 100px;
  border-radius: 10px;
}
h1 {
  color: rgb(4, 20, 255);
}
h3 {
  color: rgb(255, 255, 255);
  margin: 20px 0 0;
}
p {
  color: rgb(255, 255, 255);
}

li {
  display: inline-block;
  margin: 0 10px;
  color: rgb(255, 255, 255);
}


div{
  box-shadow: 5px 2px 2px rgba(0, 0, 0, 0.459);
}

</style>

