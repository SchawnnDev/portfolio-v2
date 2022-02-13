<template>
  <div style="margin-bottom: 30px">
    <div class="title">
      <h1>MES COMPETENCES</h1>
      <hr>
    </div>

    <div class="competences">
      <div class="competence">
        <h3>Logiciel</h3>
        <ul>
          <li>C</li>
          <li>C# (WPF)</li>
          <li>Java (Swing)</li>
          <li>Python</li>
        </ul>
      </div>

      <div class="competence">
        <h3>Web</h3>
        <ul>
          <li>JavaScript (VueJS)</li>
          <li>PHP (Laravel)</li>
          <li>Python (Django)</li>
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
.competences {
  display: flex;
  width: 100%;
}
.competence {
  width: 50%;
}
</style>