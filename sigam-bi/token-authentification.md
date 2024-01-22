# Token authentification

Avant de pouvoir utiliser les API vous devez générer un token de sécurité. Pour ce faire dans la page de documentation des API accédez à l'api **Connexion**

![](<.gitbook/assets/image (12).png>)

Cliquez ensuite sur le le bouton **Try it out**. Il vous permettra de saisir vos données d'identification.

Dans **UserName** : saissisez votre nom d'utilisateur SIGAM\
Dans **Password** : saissisez votre mot de passe SIGAM

![](<.gitbook/assets/image (8).png>)

Cliquez ensuite sur le bouton **Execute**.

Si vous information d'identification sont correctes vous obtenez en dessous dans la partie **Response Body** un résultat avec un token. Veuillez copier la valeur du token et le conserver. Le token est valide pour trois mois. Au delà de trois mois vous devrez refaire l'opération d'identification.

Exemple :

```
{
  "message": "Authentification réussie",
  "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJleHAiOjE2MTk3Nzc2MDEsImlzcyI6Ik"
}
```

(c) Afinov Sarl 2020
