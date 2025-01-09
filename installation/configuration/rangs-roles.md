# Rangs (Rôles)

L'option **"Rangs (Rôles)"** permet de créer et de gérer automatiquement les rôles associés aux rangs du bot. Ces rôles sont essentiels pour structurer votre serveur et donner des permissions spécifiques en fonction du rang des membres.

## Création automatique des rôles

1. Utilisez la commande `/setup ranks` pour créer automatiquement tous les rôles associés aux rangs du bot.
2. Le bot génère deux types de rôles pour chaque palier :
   * **Rôle de palier** : Exemple : `Bronze`
   * **Rôles de niveau de palier** : Exemple : `Bronze 1`, `Bronze 2`, `Bronze 3`

Veuillez noter que l'exécution de cette commande peut prendre environ 20s.

## Pourquoi un rôle de palier sans nombre (comme `Bronze`) ?

Le rôle de palier (sans nombre) est créé pour deux raisons principales :

1. **Organisation** : Séparer les membres dans la liste des salons pour une meilleure visibilité.
2. **Permissions** : Attribuer des permissions à un ensemble de paliers facilement.

Vous pouvez supprimer ces rôles si vous le souhaitez, mais le membre concerné ne recevra plus ce rôle lorsqu'il sera dans le rang correspondant.

## Personnalisation des rôles

Vous pouvez personnaliser les rôles créés par le bot selon vos besoins :

* **Renommer** les rôles
* Modifier les **couleurs**
* Ajouter des **icônes**

Ces modifications n'affecteront pas le nom des rôles dans les commandes du bot (comme `/ranks`) ni l'apparence du canvas.

## Gestion des rôles liés aux rangs

Pour relier ou supprimer un rôle associé à un rang :

1. Utilisez la commande `/settings`, puis sélectionnez **Rang**.
2. Choisissez le rang que vous souhaitez modifier.
3. Ajoutez ou supprimez-le ou les rôles associés.

## Fonctionnement des rôles par rang

Le bot gère automatiquement les rôles attribués aux membres :

* Un membre gardera **le ou les derniers rôles liés à son rang actuel**.
* Les rôles des rangs inférieurs seront automatiquement retirés.

**Exemple :**\
Un membre avec le rang `Gold 2` aura les rôles suivants :\
`Gold` et `Gold 2`.\
Tous les rôles inférieurs (`Bronze`, `Silver`, etc.) lui seront retirés.

### **Puis-je personnaliser les noms des rôles ?**

Oui, vous pouvez renommer les rôles. Le changement n'affectera pas leur fonctionnement dans le bot.

### **Que se passe-t-il si je supprime un rôle ?**

Si vous supprimez un rôle, le membre concerné ne recevra plus ce rôle lorsqu'il atteindra le rang correspondant.

### **Comment attribuer des permissions spécifiques aux rôles ?**

Configurez les permissions directement sur Discord pour chaque rôle. Vous pouvez utiliser le rôle de palier (ex. `Bronze`) pour donner des permissions globales à un groupe.
