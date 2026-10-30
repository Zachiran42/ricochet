# Ricochet

[Télécharger l’APK](https://github.com/Zachiran42/ricochet/releases/latest/download/ricochet-0.1.0.apk) · [Versions](https://github.com/Zachiran42/ricochet/releases) · [Page du jeu](https://zachiran42.github.io/ricochet/)

Prototype Android natif, hors ligne, sans permission ni publicité. Android 8+. Partie courte, record local, pause et reprise.

Trois tirs : glisser depuis la bille vers une cible. Les rebonds multiplient les points.

Sources Java et Canvas, licence MIT. Le script scripts/build.ps1 prend un fichier toolchain et une clé externe ; ne jamais publier de clé. APK de développement, pas encore testé sur téléphone physique.

## Dans Cercle

Dans « Ajouter depuis GitHub », coller `https://github.com/Zachiran42/ricochet`. La dernière Release contient un seul APK, signé, universel et sans permission Internet.

## Compilation

Copier `.toolchain.example.json` vers `.toolchain.json`, renseigner JDK21, Android SDK36 et Build Tools, puis définir `MINIGAMES_KEYSTORE_PASSWORD` dans l’environnement. Utiliser `scripts/build.ps1 -KeyStore C:/cles/jeu.keystore -KeyAlias votre-alias`. Garder les clés hors du dépôt.
