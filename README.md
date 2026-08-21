# Compte à Rebours – Version Web

Ce projet propose un **compte à rebours personnalisable**, entièrement autonome et prêt à être intégré sur n’importe quel site web.  
Le fichier HTML contient tout : structure, style et logique JavaScript.

---

## Fonctionnement

Le script calcule en temps réel le nombre de **jours, heures, minutes et secondes** restants avant une date définie dans la configuration.  
L’affichage se met à jour automatiquement toutes les secondes.

---

## Personnalisation

Toutes les options modifiables se trouvent dans la section suivante :
La date est au format YY/MM/DD/HH/Min
```js
const CONFIG = {
    dateFin: new Date(2026, 9, 11, 9, 0).getTime(),
    couleurFond: "#FFFFFF",
    couleurChiffres: "#5D0B72",
    couleurTexte: "#5D0B72",
    policeChiffres: "bold 60px Verdana, sans-serif",
    policeUnites: "italic 15px Arial, sans-serif"
};
