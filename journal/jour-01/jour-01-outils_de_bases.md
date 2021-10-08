# [Jour 1/100] - Quels outils pour #100DaysOfDevOps ?

## INTRODUCTION

- Quels outils sont nécessaires pour apprendre les technos devops ?

## PRE-REQUIS

- Aucun pré-requis n'est nécessaire pour cela.

## CAS D'USAGE

- Pouvoir éditer du code pour de l'infrastructure as code => vscode
- Pouvoir versionner ce code => git
- Pouvoir monter des environnements de test sur mon poste de travail pour certaines technos (docker, kubernetes,... ) qui ne nécessite pas d'utiliser un fournisseur de Cloud => virtualbox


## EN PRATIQUE

## VSCode

- Comment installer VSCode ? 

### Installation VSCode

- Se rendre sur https://code.visualstudio.com/
- Choisir le package relatif à son système d'exploitation *(pour ma part j'utilise Windows)*

![Capture d'écran code.visualstudio.com](medias/site_vscode_download.png)

- Suivre le processus d'installation

![Capture d'écran - Installation VSCode - etape 0](medias/vscode_installation-etape-00.png)
![Capture d'écran - Installation VSCode - etape 1](medias/vscode_installation-etape-01.png)
![Capture d'écran - Installation VSCode - etape 2](medias/vscode_installation-etape-02.png)
![Capture d'écran - Installation VSCode - etape 3](medias/vscode_installation-etape-03.png)
![Capture d'écran - Installation VSCode - etape 4](medias/vscode_installation-etape-04.png)


## Git

- Comment installer Git ?
- Comment configurer Git (les bases) ?

### Installation de Git

- Se rendre sur https://git-scm.com/downloads
- Choisir le package relatif à son système d'exploitation *(Pour ma part j'utilise Windows)*

![Capture d'écran git-scm.com](medias/site_git-scm_download.png)

 
- Suivre le processus d'installation spécifique à votre OS.

![Capture d'écran - Installation Git - etape 0](medias/git_installation-etape-00.png)
![Capture d'écran - Installation Git - etape 1](medias/git_installation-etape-01.png)
![Capture d'écran - Installation Git - etape 2](medias/git_installation-etape-02.png)
![Capture d'écran - Installation Git - etape 3](medias/git_installation-etape-03.png)
![Capture d'écran - Installation Git - etape 4](medias/git_installation-etape-04.png)
![Capture d'écran - Installation Git - etape 5](medias/git_installation-etape-05.png)
![Capture d'écran - Installation Git - etape 6](medias/git_installation-etape-06.png)
![Capture d'écran - Installation Git - etape 7](medias/git_installation-etape-07.png)
![Capture d'écran - Installation Git - etape 8](medias/git_installation-etape-08.png)
![Capture d'écran - Installation Git - etape 9](medias/git_installation-etape-09.png)
![Capture d'écran - Installation Git - etape 10](medias/git_installation-etape-10.png)
![Capture d'écran - Installation Git - etape 11](medias/git_installation-etape-11.png)
![Capture d'écran - Installation Git - etape 12](medias/git_installation-etape-12.png)
![Capture d'écran - Installation Git - etape 13](medias/git_installation-etape-13.png)
![Capture d'écran - Installation Git - etape 14](medias/git_installation-etape-14.png)
![Capture d'écran - Installation Git - etape 15](medias/git_installation-etape-15.png)
![Capture d'écran - Installation Git - etape 16](medias/git_installation-etape-16.png)


### Configuration git de base 
- Pour savoir qui commit 
```bash
git config --global user.name "Christophe @ctlabfr"
git config --global user.email "hello@ctlab.Fr"
```


### Initialiser un repository sur son poste
```bash
> cd 100daysofdevops
> git init
```

### Lister le repo distant
```bash
> git remote -v
```

### Ajouter un repo distant
```bash
> git remote add origin https://github.com/ctlabfr/100DaysOfDevOps.git
```
- dans la commande ci-dessus
    - origin est le nom court que l'on associe sur notre poste au repo distant 
    - ce nom court pourra être utilisé ultérieurement dans les commandes git

### Pousser le contenu sur le repo distant
```bash
> git branch -M main
> git push -u origin main
```



## Virtualbox

### Installation Virtualbox

- Se rendre sur 
- Choisir le package relatif à son système d'exploitation *(Pour ma part j'u>tilise Windows)*
![Capture d'écran git-scm.com](medias/site_virtualbox_download.png)

 
- Suivre le processus d'installation spécifique à votre OS.

![Capture d'écran - Installation Virtualbox - etape 0](medias/virtualbox_installation-etape-00.png)
![Capture d'écran - Installation Virtualbox - etape 1](medias/virtualbox_installation-etape-01.png)
![Capture d'écran - Installation Virtualbox - etape 2](medias/virtualbox_installation-etape-02.png)
![Capture d'écran - Installation Virtualbox - etape 3](medias/virtualbox_installation-etape-03.png)
![Capture d'écran - Installation Virtualbox - etape 4](medias/virtualbox_installation-etape-04.png)
![Capture d'écran - Installation Virtualbox - etape 5](medias/virtualbox_installation-etape-05.png)
![Capture d'écran - Installation Virtualbox - etape 6](medias/virtualbox_installation-etape-06.png)



## Ce que je retiens de cette journée

- Premier jour de chauffe pour se lancer dans le défi #100DaysOfDevOps
- Rien de bien compliqué jusqu'ici
- Installation de quelques outils essentiels (à mon avis) pour pouvoir expérimenter et apprendre autour du devops.

## Prochaines étapes

- Définir un plan de route pour les 99 prochains jours

</br>
---
</br>


## Preuve Sociale

[@ctlabfr / 100daysofdevops - Jour 1]()
