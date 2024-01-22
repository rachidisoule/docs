# Configuration

Chaque site ou poste de pointage est identifié par un code et une clef d'authentification. Si vous ne l'avez pas, veuillez vous rapprocher de l'administrateur.\


Dans le dossier, d'installation, editez le fichier config.json

Ci-dessous un exemple du contenu de ce fichier

```
{
  "Folders": {
    "Input": "C:\\Input",
    "Output": "C:\\Output",
    "ExtensionFile": "xls",
    "TransactionSize": 100
  },
  "Logging": {
    "LogLevel": {
      "Default": "Information",
      "Microsoft.AspNetCore": "Warning"
    }
  }
}
```

Dans la section <mark style="color:red;">Input</mark>, indiquez le dossier pour les fichiers de pointage

Dans la section <mark style="color:red;">Output</mark>, indiquez le dossier pour les fichiers d’archivage

{% hint style="warning" %}
`Attention : Ne modifiez aucunes autres informations dans ce fichier.`
{% endhint %}
