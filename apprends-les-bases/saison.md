# Saison

Le **Système de Saison** apporte une nouvelle dynamique au bot en réinitialisant les rangs tous les 60 jours. Chaque saison permet de repartir à zéro, tout en récompensant les membres en fonction de leur rang à la fin de la saison précédente.

> Les saisons offrent à tous les membres une chance de briller à nouveau et de grimper dans le classement global !

## Durée d’une saison

* Une saison dure **60 jours maximum**.
* À la fin de chaque saison, **tous les rangs sont réinitialisés** sur tous les serveurs.

## Réinitialisation des rangs

À chaque début de saison, les membres sont réinitialisés à des rangs spécifiques en fonction de leur rang final lors de la saison précédente :

| Rang final (précédente saison) | Nouveau rang (début de saison) |
| ------------------------------ | ------------------------------ |
| **Master**                     | **Gold 1**                     |
| **Diamond**                    | **Silver 1**                   |
| **Autres rangs**               | **Bronze 1**                   |

{% hint style="warning" %}
La réinitialisation des rangs est globale et s’applique à tous les serveurs utilisant le bot.
{% endhint %}

## Saisons globales et leaderboard

Les saisons sont les mêmes pour **tous les serveurs** :

* Un **leaderboard global** permet de comparer les performances des membres à travers tous les serveurs utilisant le bot.
* Le changement de saison est global, ce qui signifie que **tous les utilisateurs du bot sont réinitialisés au même moment**.

## Récompenses de saison

À la fin de chaque saison, des **récompenses** sont distribuées en fonction du rang final de chaque membre. Ces récompenses sont attribuées automatiquement au début de la nouvelle saison.

## Démarrer une nouvelle saison

La nouvelle saison se lancera **automatiquement** à la date et à l’heure prévues.\
Pour connaître la date et l’heure exactes, utilisez la commande `/season`

Lorsqu’une nouvelle saison démarre :

1. Les **anciens rôles de rang** (de la saison précédente) **ne sont pas supprimés** automatiquement.
   * Vous pouvez les conserver si vous souhaitez garder une trace des saisons passées.
   * Si vous préférez faire le ménage, vous pouvez toujours les supprimer manuellement.
2. Pour **reconfigurer** les rôles pour la nouvelle saison, exécutez `/settings > Rangs > Créer les rôles`
   * Tous les **nouveaux rôles** seront alors créés et **associés automatiquement** à chaque rang de la nouvelle saison.

{% hint style="success" %}
Si vous souhaitez éviter toute confusion entre les anciens et nouveaux rôles, pensez à renommer ou supprimer les rôles obsolètes avant de créer les nouveaux.
{% endhint %}

### **Les saisons sont-elles différentes d’un serveur à l’autre ?**

Non, les saisons sont **globales**. Tous les serveurs utilisant le bot partagent le même calendrier de saison.

### **Puis-je conserver mon rang après une réinitialisation ?**

Non, tous les rangs sont réinitialisés en fonction du système décrit ci-dessus. Cela garantit une équité pour tous les membres.

### **Quelles sont les récompenses exactes de fin de saison ?**

Les récompenses varient en fonction du rang final, mais incluent toujours un certain montant de RP. Consultez les annonces sur le serveur officiel pour connaître les détails spécifiques de chaque saison.

### **Le classement global est-il remis à zéro ?**

Oui, le classement global est réinitialisé en même temps que les rangs.
