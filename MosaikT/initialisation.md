# Initialisation

La procédure d’initialisation à pour objectif d’indiquer au programme de synchronisation les paramètres à utiliser pour transmettre les données au serveur.

Les paramètres d'initialisation sont :

* Le code du site/zone : ce code est transmis par l'administrateur pour chaque site de pointage.
* La clef de vérification : Elle est également communiqué lors de création du site par l'administrateur.
* L'url du serveur : L'url est également communiqué par l'administrateur.

Muni de ces trois paramètres, veuillez exécuter en ligne de commande le programme suivant la syntaxe ci-dessous :

```
MosaicPointages -s <Zone> <Clef> <Url serveur>
```

Exemple :

```
MosaicPointages -s MT2PLTX a8139383a3b248a2bf18a8b77e34d97b78 https://api.mosaik.afinov.com:1443
```
