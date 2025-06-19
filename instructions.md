# Instructions de génération – Usine à projets

## Projet
nom: CauseMapster

## Fichier
nom: formulaire_accident.html
type: html

## Contenu
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>Déclaration d'accident</title>
</head>
<body>
  <h1>Déclaration d'accident du travail</h1>
  <form>
    <label>Nom :
      <input type="text" name="nom" />
    </label>
  </form>
</body>
</html>

## Commit
message: "Ajout du formulaire formulaire_accident.html"

---

## Fichier
nom: formulaire_accident.js
type: js

## Contenu
document.addEventListener("DOMContentLoaded", () => {
  console.log("Formulaire chargé !");
});

## Commit
message: "Ajout du script formulaire_accident.js"
