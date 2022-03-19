<template>
  <div class="comp">
    <div class="title">
      <h1>MES COMPETENCES</h1>
      <hr>
    </div>

    <div class="competences">
      <div class="competence">
        <ul>
          <li><h3>Desktop</h3></li>
          <li>C</li>
          <li>C# (WPF)</li>
          <li>Java (Swing)</li>
          <li>Python</li>
        </ul>
      </div>

      <div class="competence">
        <ul>
          <li><h3>Web</h3></li>
          <li>JavaScript (VueJS)</li>
          <li>PHP (Laravel)</li>
          <li>Python (Django)</li>
        </ul>
      </div>

      <div class="competence">
        <ul>
          <li><h3>Logiciels</h3></li>
          <li>PhpStorm</li>
          <li>PyCharm</li>
          <li>CLion</li>
          <li>Visual Studio</li>
        </ul>
      </div>
    </div>


  </div>
</template>

<script>
export default {
  name: "Competences"
}
</script>

<style scoped>
.comp {
  margin-bottom: 30px;
  background-color: azure;
}
.competences {
  display: flex;
  width: 100%;
}
.competence {
  width: 50%;
}

ul {
  list-style-type: none;
  font-size: 20px;
}

@media (min-width: 320px) and (max-width: 480px) {
  /* Phones */
  .competences {
    flex-wrap: wrap;
  }


}

</style>