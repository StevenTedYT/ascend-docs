# Rôle d'événement

L'option **"Rôle d'événement"** vous permet de configurer un rôle spécifique qui sera mentionné pour notifier les membres lors du lancement d’événements. Cela permet de cibler uniquement les membres intéressés par les événements sans déranger tout le serveur.

## Comment configurer le rôle d'événement ?

1. Utilisez la commande `/settings` et sélectionnez **Rôle d'événement**.
2. Dans le menu déroulant, choisissez le rôle que vous souhaitez utiliser pour les notifications d’événements.
3. Cliquez sur **Enregistrer** pour confirmer votre choix.

{% hint style="warning" %}
Le bot **ne crée pas le rôle automatiquement**. Vous devez avoir créé le rôle au préalable dans les paramètres de votre serveur Discord.
{% endhint %}

## Fonctionnement du rôle d'événement

* **Notifications ciblées** : Lorsqu'un événement est lancé, le bot mentionnera uniquement le rôle configuré, attirant ainsi l’attention des membres concernés.
* **Personnalisation totale** : Vous pouvez choisir n’importe quel rôle existant sur votre serveur pour cette fonction. Cela vous permet de gérer les événements selon vos besoins spécifiques.

## Le bot crée-t-il automatiquement le rôle d'événement ?

Non, le bot ne crée pas de rôle. Vous devez d'abord créer le rôle manuellement dans les paramètres de votre serveur Discord, puis le configurer via `/settings`.

## Puis-je changer le rôle d'événement plus tard ?

Oui, vous pouvez modifier le rôle à tout moment en utilisant `/settings`.

## Que se passe-t-il si aucun rôle d'événement n’est configuré ?

Si aucun rôle n'est configuré, le bot ne mentionnera aucun rôle lors des notifications d’événements.

## Puis-je désactiver les mentions pour les événements ?

Oui, si vous ne configurez pas de rôle d'événement, aucune mention ne sera envoyée. Vous pouvez également supprimer le rôle de l'événement via `/settings`.
