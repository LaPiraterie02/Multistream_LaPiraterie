# Multistream_LaPiraterie

# 📺 MULTISTREAM - Multiplex Engine

Un outil minimaliste et performant pour regarder jusqu'à 6 flux simultanés (YouTube, Twitch, ou liens directs) sur une seule page.

## 🚀 Fonctionnalités

- **Grille Dynamique** : Choisissez d'afficher 1, 2, 4 ou 6 écrans simultanément.
- **Support Multi-Plateforme** : Compatible avec nos liens de stream mais aussi Youtube, Twitch etc
- **Nettoyage Automatique** : Convertit intelligemment les liens YouTube et Twitch standards en formats intégrables (embed).
- **Mode Plein Écran** : Zoomez sur un flux spécifique en un clic sans perdre votre configuration.
- **Persistance locale** : Vos liens et votre configuration de grille sont sauvegardés automatiquement dans votre navigateur.
- **Sans Sandbox** : Restrictions d'iframe levées pour une compatibilité maximale.

## 🛠️ Comment l'utiliser ?

1. Accédez à l'outil via le lien GitHub Pages.
2. Cliquez sur un slot vide ou sur le bouton **"Ajouter flux"**.
3. Collez l'URL de votre vidéo ou de votre stream.
4. Utilisez les boutons en haut à droite pour changer le nombre d'écrans.
5. Survolez un flux pour le modifier ou passer en plein écran.

## 🔒 Confidentialité

Ce projet n'utilise aucune base de données. Toutes vos données (liens des streams) sont stockées localement dans votre propre navigateur via le `localStorage`. Personne d'autre que vous ne peut voir votre configuration.

---
*Développé avec ❤️ pour la communauté.*
---
```javascript
/* 🏴‍☠️ LaPiraterie - Multistream Engine */
const status = {
  user: "LaPiraterie",
  mission: "Multiplexing the High Seas",
  stack: ["HTML5", "CSS3", "JS_Vanilla"],
  status: "Streaming..."
};

if (pirateMode) {
  console.log("Ready to board the streams! 📺");
}
