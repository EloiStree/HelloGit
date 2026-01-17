* [ ] Installer Git si pas déjà fait
* [ ] Créer un projet Unity de quarantaine
  * [ ] Un projet Unity qui servira à travailler hors du contexte de votre application afin d’éviter le code spaghetti
  * [ ] Je les fais commencer par `Q_`, par exemple `Q_OutilDeDessin`
* [ ] Créer un dossier `Assets/Package` pour faire nos outils
* [ ] Créer votre répertoire Git sur GitHub
  * [ ] Ma convention personnelle :
    * [ ] Commencer par la date de création : `2026_01_17_nom_outil`
    * [ ] Commencer par un `P` si ça doit rester privé : `P_2026_01_17_nom_outil`
    * [ ] Ajouter `upm` pour *Unity Package Manager* : `2026_01_17_upm_nom_outil`
* [ ] Utiliser `git clone` pour avoir le répertoire dans `Assets/Package`
* [ ] Ajouter des dossiers :
  * [ ] `Scene/Demo`
  * [ ] `Runtime`
  * [ ] `Prefab`
* [ ] Ajouter un `README.md` si ce n’est pas déjà fait
* [ ] Pour rendre le projet valide, il faut ajouter un `package.json`
  * [ ] Copier le JSON d’un de mes projets
    * [ ] [https://github.com/EloiStree?tab=repositories&q=_upm_&type=&language=&sort=](https://github.com/EloiStree?tab=repositories&q=_upm_&type=&language=&sort=)
  * [ ] Lire la documentation : [https://docs.unity3d.com/6000.3/Documentation/Manual/upm-manifestPkg.html](https://docs.unity3d.com/6000.3/Documentation/Manual/upm-manifestPkg.html)
  * [ ] Faire relire par une IA au besoin pour trouver les coquilles
* [ ] Ajouter une scène de démo dans `Scene/Demo` pour comprendre comment utiliser votre outil
* [ ] Créer quelques scripts dans `Runtime` pour faire fonctionner votre outil
* [ ] Ajouter un ou des prefabs pour faciliter l’utilisation de votre outil
* [ ] Pour que `Runtime` soit valide, il faut un assembly
  * [ ] Créer un assembly dans `Runtime` avec un nom `pays.entite.outil`, par exemple `be.elab.monoutil`
    * [ ] Éviter les chiffres et les majuscules
    * [ ] Attention : un assembly isole le code
      * [ ] Ajouter des dépendances si nécessaire dans l’assembly
* [ ] Normalement, on est prêt
* [ ] Un petit `Add`, `Commit`, `Pull`, `Push` et on est bon

### Aller les tester

* [ ] Aller dans un autre projet que celui de quarantaine
* [ ] Aller dans `Window / Package Manager`
* [ ] Cliquer sur le `+` et ajouter depuis un Git
* [ ] Ajouter le lien Git de votre boîte à outils
  * [ ] Ne pas oublier le `.git` dans l’URL
* [ ] S’il y a une erreur, la lire et ajuster
  * [ ] Recommencer
* [ ] Ta-dam 😉

