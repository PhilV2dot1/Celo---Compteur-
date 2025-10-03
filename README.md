# Celo---Compteur-

Caractéristiques principales :
Fonction de base :

incrementer() - Ajoute 1 au compteur à chaque appel (nécessite une transaction)
Règles du jeu :

Le même participant ne peut pas incrémenter deux fois de suite
Le compteur s'arrête automatiquement à 100
Chaque participation est enregistrée dans l'historique
Suivi et statistiques :

historique - Qui a compté quel nombre
participations - Combien de fois chaque adresse a participé
dernierParticipant - L'adresse du dernier joueur
Gestion du jeu :

reinitialiser() - Redémarre le compteur une fois arrivé à 100
forcerReinitialisation() - Réinitialisation d'urgence accessible à tous
obtenirInfosJeu() - Affiche toutes les informations actuelles
Événements émis :

CompteurIncrement - À chaque nouveau compte
JeuTermine - Quand on atteint 100
JeuReinitialise - Quand le jeu redémarre
C'est un jeu collaboratif où plusieurs participants doivent travailler ensemble (ou en compétition) pour atteindre 100, sans utiliser aucun fonds !





