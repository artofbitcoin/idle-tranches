# 2. IdleCDO et stratégie

IdleCDO est le point d’entrée qui conserve les actifs des utilisateurs, frappe ou brûle les tokens AA et BB et délègue la stratégie de rendement. L’interface IIdleCDOStrategy sépare la logique du produit de la logique du fournisseur de liquidité.

IdleStrategy sert d’intermédiaire vers Idle Finance et ses actifs porteurs de rendement. La méthode harvest met à jour la comptabilité, traite les récompenses et réinvestit lorsque le modèle le prévoit. Le découplage permet de remplacer une stratégie après retrait de la position, mais il ne supprime pas le risque de l’intégration.

[Chapitre suivant : prix, frais et récompenses](03-pricing-rewards.md)
