# Première installation

## Étape 1

Vous devez faire cette première configuration sur votre serveur de test sur votre PC pour éviter les erreurs et les redémarrages trop nombreux... les joueurs n'aiment pas quand le serveur est en panne ;\) Vous pouvez télécharger des fichiers sur votre vrai serveur après avoir terminé ici.

{% hint style="danger" %}
Si vous possédez déjà l'ancienne version 1.0 d'ItemsAdder, veuillez renommer le dossier **plugins/ItemsAdder** en **ItemsAdder\_backup**.
{% endhint %}

* Installer [**ProtocolLib**](https://www.spigotmc.org/resources/protocollib.1997/)
* Installer [**IALib**](https://www.spigotmc.org/resources/ialib.75974/)
* Installer [**LightAPI**](https://www.spigotmc.org/resources/lightapi-fork.48247/)
* Mettez le fichier **ItemsAdder.jar** dans votre dossier de plugins
* Démarrer le serveur
* Laisser ItemsAdder terminer **tout** le chargement 
* Arrêter le serveur

## Étape 2

* Rejoindre le serveur et exécuter la commande `/iazip` lorsque le plugin est complètement chargé
* Ouvrir le fichier plugins\ItemsAdder\config.yml
* Suivez ce tutoriel :

{% page-ref page="plugin-usage/resourcepack-hosting/resourcepack-self-hosting.md" %}



{% hint style="warning" %}
N'oubliez pas d'utiliser la commande `/iazip` chaque fois que vous voulez que le plugin mette à jour le fichier `pack.zip`.
{% endhint %}

