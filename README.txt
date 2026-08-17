LA MACHINE ORCHESTRE — INSTALLATION

En lançant MachineOrchestre-Setup.exe, Windows affiche cet avertissement :

    Windows a protégé votre ordinateur
    Microsoft Defender SmartScreen a empêché le démarrage d'une appli non
    reconnue. L'exécution de cette appli peut mettre votre PC en danger.

C'est normal : cet installateur n'est pas signé numériquement (aucun
certificat de signature de code). Windows avertit ainsi pour TOUT
exécutable téléchargé d'un éditeur non identifié, indépendamment de sa
fiabilité réelle.

La Machine Orchestre est un logiciel personnel, développé par son propre
auteur, sans collecte de données. Ce dépôt ne contient que cet installateur
et ce fichier, publiés par l'auteur lui-même.

Activité réseau du programme, une fois installé :

  - Au lancement : vérification de nouvelles versions (de l'application
    elle-même, sur cette page GitHub, et des outils FFmpeg/FluidSynth
    utilisés pour l'export vidéo) — jamais de téléchargement sans une
    confirmation explicite.
  - En continu : un petit serveur web LOCAL démarre automatiquement (port
    8080) pour piloter la lecture depuis une tablette sur le même réseau
    Wi-Fi (voir l'Aide du programme, section « Télécommande réseau »).
    Sans mot de passe : toute personne sur le même réseau peut y accéder.

Pour continuer l'installation :

  1. Cliquer sur « Informations complémentaires » (petit lien texte sous
     le message d'avertissement).
  2. Un bouton « Exécuter quand même » apparaît en bas à droite de la
     fenêtre. Cliquer dessus.
  3. L'installation reprend normalement.

Aucun droit administrateur n'est requis : le programme s'installe hors de
Program Files et peut écrire ses propres préférences sans élévation.
