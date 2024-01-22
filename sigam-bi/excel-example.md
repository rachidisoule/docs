---
description: Cette page décrit comment extraire les données de SIGAM BI dans Excel
---

# Excel Exemple

Avant tout veuillez identifier l'api et ses paramètres à partir de la documentation des api de SIGAM BI.\
Dans cet exercice nous voulons extraire les achats pour la période du 01/06/2020 au 30/06/2020. \


![](<.gitbook/assets/image (13).png>)

L'API que nous allons utiliser est **/api/services/pesee/getAchatsAcceptes** &#x20;

![](<.gitbook/assets/image (7).png>)

Cette API a deux paramètres **dateDebut** et **dateFin**

Dans Excel allez dans le menu **Données** et cliquez sur l'icone **Obtenir des données**, puis **A partir d'autres sources** puis **A partir du Web**

![](<.gitbook/assets/image (1).png>)

Sur l'écran qui s'affichera cliquez sur le bouton **Avancé**

![](<.gitbook/assets/image (9).png>)

_**Ci-dessous les informations à renseigner :**_

**1/** Parties d'URL : Indiquez l'url de l'API\
**2/** Dans le zone en dessous ajouté le nom du 1er paramètre précédé de ? avec la valeur assigné. **Exemple : ?dateDebut=2020/06/01** (_Veuillez noter que les dates doivent être au format aaaa/mm/jj_)\
Cliquez sur Ajouter une partie afin d'avoir une zone pour le second paramètre et indiquez ce paramètre précédé de &. **Exemple :** **\&dateFin=2020/06/30**\
**3/** Dans la zone **Paramètres de l'en-tête de la requête HTTP**, saisissez **Authorization**, dans la zone suivante saisissez **Bearer** suivi du token que vous avez récupérer précédemment.\
\
Cliquez sur le bouton **OK**

Si les données sont correctes vous obtenez l'écran suivant :

![](<.gitbook/assets/image (3).png>)

Cliquez sur l'icone **Vers la table** et ensuite ok sur l'écran qui s'affiche. Vous obtenez l'écran ci-dessous

![](<.gitbook/assets/image (14).png>)

Cliquez sur la petite icone à droite de la colonne . Un fenêtre s'affichera avec le noms des colonnes du résultat des données. Dans cette fenêtre décochez la case **Utiliser le nom de la colonne d'origine comme préfixe**.

![](<.gitbook/assets/image (4).png>)

Cliquez sur le bouton **OK**. Les données vont s'afficher.

![](<.gitbook/assets/image (15).png>)

Cliquez ensuite sur l'icone **Fermer et charger**. Les données sont automatiquement envoyé dans une nouvelle feuille Excel.

![](<.gitbook/assets/image (10).png>)





