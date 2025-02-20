# Salon d'événement

L'option **"Salon d'événement"** vous permet de définir le salon où seront envoyées les notifications des **débuts d'événements**. Certains événements nécessitent également un salon configuré via cette option pour fonctionner correctement, car le bot doit y envoyer des messages pendant l'événement.

## Comment configurer le salon d'événement ?

1. Utilisez la commande `/settings` et sélectionnez **Salon d'événement**.
2. Dans le menu déroulant, choisissez le salon où vous souhaitez que :
   * Les **notifications de début d’événement** soient envoyées.
   * Les événements nécessitant des interactions du bot puissent fonctionner.

## Fonctionnement du salon d'événement

1. **Notifications de début d'événement** :\
   Lorsque le bot démarre un événement, il envoie une notification dans le salon configuré pour informer les membres.
2. **Événements nécessitant un salon** :\
   Certains événements nécessitent un salon dédié où le bot pourra :
   * Envoyer des messages pour guider les membres.
   * Publier des mises à jour ou des actions spécifiques liées à l'événement.

{% hint style="danger" %}
Si aucun salon d'événement n'est configuré, ces événements ne pourront pas fonctionner
{% endhint %}

## Que se passe-t-il si je ne configure pas de salon d'événement ?

Si aucun salon n'est défini, les notifications de début d'événement ne seront pas envoyées, et certains événements nécessitant des interactions spécifiques du bot ne fonctionneront pas.

## Puis-je changer le salon d'événement plus tard ?

Oui, vous pouvez modifier le salon d'événement à tout moment en utilisant la commande `/settings`.

## Tous les événements nécessitent-ils un salon d'événement ?

Non, seuls certains événements spécifiques nécessitent un salon configuré pour fonctionner. Les autres événements peuvent se dérouler sans cette configuration.

## Puis-je utiliser le même salon pour les notifications de rang et les événements ?

Oui, vous pouvez utiliser le même salon pour les deux si cela convient à la structure de votre serveur.
