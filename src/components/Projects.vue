<template>
  <div style="margin-bottom: 30px">
    <div class="title">
      <h1>MES PROJETS</h1>
      <hr>
    </div>

    <div class="projects">
      <div class="project">
        <h2 class="project-title">
          FanaConcours
        </h2>
        <img class="project-image" alt="FanaConcours" src="../assets/projects/fanaconcours.png">
        <div class="project-description">
          Site gestion des concours de l'association. Les utilisateurs mettent en ligne des photos de leur création,
          puis sera voté par certains membres un ou plusieurs gagnants.

          <ul>
            <li>Laravel</li>
          </ul>
        </div>
      </div>
      <div class="project">
        <h2 class="project-title">
          FanaCatalogue
        </h2>
        <img class="project-image" alt="FanaCatalogue" src="../assets/projects/fanacatalogue.png">
        <div class="project-description">
            Site regroupant tout les services proposés par l'association. Génération de devis estimatifs en PDF.

            <ul>
              <li>VueJS</li>
              <li>Laravel</li>
            </ul>
        </div>
      </div>
    </div>
    <p>Si vous souhaitez voir plus de projets, n'hesitez pas à consulter mon <u><a href="https://gitlab.com/SchawnnDev">GitHub</a></u>.</p>
  </div>
</template>

<script>
export default {
  name: "Projects"
}
</script>

<style scoped>

.projects {
  display: flex;
  margin-left: 50px;
  margin-right: 50px;
}

.project {
  height: 400px;
  width: 50%;
 /* border: 1px #2c3e50 solid; */
  box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
  margin: 6px;
}

.project-title {

}

.project-image {
  width: 80%;
}

.project-description {
  margin-left: 10%;
  margin-right: 10%;
  text-align: left;
  font-size: 18px;
}
</style>