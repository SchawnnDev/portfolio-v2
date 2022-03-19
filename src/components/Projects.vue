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
      <div class="project">
        <h2 class="project-title">
          Gestionnaire de notes
        </h2>
        <img class="project-image" alt="Gestionnaire de notes" src="../assets/projects/notes.png">
        <div class="project-description">
          Site crée avec un ami, pour avoir un aperçu de nos notes et calculer la moyenne de notre semestre.
          <ul>
            <li>VueJS</li>
            <li>Django</li>
          </ul>
        </div>
      </div>
    </div>
    <p>Si vous souhaitez voir plus de projets, n'hesitez pas à consulter mon <u><a href="https://github.com/SchawnnDev">GitHub</a></u>.</p>
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

@media (min-width: 320px) and (max-width: 600px) {
  /* Phones */
  .projects {
    align-items: center;
    flex-direction: column;
  }

  .project {
    width: 80vw;
  }

}

</style>