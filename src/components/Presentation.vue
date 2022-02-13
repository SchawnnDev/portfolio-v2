<template>
  <div class="presentation">
    <div class="profile">
      <img alt="Profile image" class="pp" src="../assets/pp.jpeg"/>
      <div class="description">
        <h1>Paul Meyer</h1>
        <h3>Etudiant en L3 Informatique</h3>
      </div>
    </div>

    <p class="bio">Bonjour, moi c'est <u>Paul Meyer</u>.</p>
    <p class="bio">Je suis actuellement en 3ème année d'une licence en informatique à l'<u>Université de Strasbourg.</u>
    </p>
    <p class="bio">Passioné par l'informatique depuis mes 12 ans, j'ai crée un certain nombre de projets que vous pouvez
      consulter ci-dessous.
    </p>

    <h4 class="bio">Bonne visite !</h4>

    <networks/>
  </div>
</template>

<script>
import Networks from "@/components/Networks";

export default {
  name: "Presentation",
  components: {Networks}
}
</script>

<style scoped>
.presentation {
  background-color: azure;
  width: 100%;
  height: 100%;
}

.presentation .description {
  text-align: left;
  margin-left: 30px;
}

.profile {
  display: flex;
  align-items: center;
  justify-items: center;
  justify-content: center;
}

.pp {
  border-radius: 50%;
  width: 150px;
  height: 150px;
  margin-top: 10px;

  border: #2c3e50 solid 2px;
}

.bio {
  font-size: 20px;
  margin-left: 40px;
  margin-right: 40px;
}
</style>