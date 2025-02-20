# Blacklist

L'option **"Blacklist"** vous permet de bloquer le gain de RP dans certains salons spécifiques de votre serveur. Cela peut être utile pour éviter que l'activité dans des salons non pertinents, comme un salon de spam ou de jeux, n'influence les rangs des membres.

## Comment ajouter ou retirer un salon à la blacklist ?

1. Accédez à la commande `/settings` et sélectionnez **Blacklist**.
2. Dans le menu déroulant, choisissez :
   * **Ajouter** : pour empêcher le gain de RP dans un salon spécifique.
   * **Retirer** : pour permettre à nouveau le gain de RP dans un salon précédemment blacklisté.
3. Sélectionnez le salon concerné dans la liste.
4. Cliquez sur **Enregistrer** pour appliquer les modifications.

## Fonctionnement de la blacklist

* Les salons ajoutés à la blacklist **ne génèrent plus aucun RP** pour les membres qui y interagissent.
* Le bot continue de fonctionner normalement dans ces salons (commandes, logs, etc.), mais l'activité des membres n'y est pas prise en compte pour les rangs.

## Exemple d'utilisation

* Vous avez un salon `#jeux` où les membres passent beaucoup de temps à interagir.\
  👉 Ajoutez ce salon à la blacklist pour que cette activité n'impacte pas leurs rangs.
* Vous avez blacklisté le salon `#général` par erreur.\
  👉 Utilisez l'option **Retirer** pour que ce salon génère à nouveau des RP.

### **Puis-je blacklister plusieurs salons en même temps ?**

Oui, vous pouvez ajouter plusieurs salons à la blacklist. Répétez simplement le processus pour chaque salon.

### **Que se passe-t-il si je supprime un salon blacklisté ?**

Si le salon est supprimé, il disparaîtra automatiquement de la blacklist.
