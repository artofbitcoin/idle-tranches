# 3. Prix, frais et récompenses

Les prix de tranche sont mis à jour au harvest afin de limiter les écarts entre la valeur comptable et les actifs réellement disponibles. Une sortie utilise un prix checkpointé, ce qui rend le calcul plus prévisible mais crée une dépendance au rythme des harvests.

Le paramètre trancheAPRSplitRatio répartit l’intérêt entre AA et BB. Le ratio de poids idéal décrit une composition souhaitée du capital, tandis que des contrats de récompenses peuvent encourager les utilisateurs à rapprocher le pool de cette cible. Les récompenses sont libérées progressivement selon les paramètres du contrat.

Les frais de performance et la dilution de l’offre doivent être étudiés avec les conversions et les arrondis du code.

[Chapitre suivant : urgence et limites](04-emergency-limits.md)
