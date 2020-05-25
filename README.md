# Description

The implementation of Deep Learning models to encode user profiles (keywords of the methods used: Embedding, HashingTrick, Multi-task learning, Auto-encoding).
The use of user encodings for various marketing issues, including the optimization of notification campaigns. For this, the previously learned encoding will be used as input for a contextual bandit algorithm (it's like reinforcement, but more focused on fast convergence at the expense of complex relationships between variables, that's why we do an encoding with auto-encoder before). In the case of notification campaigns, the goal will be to send notifications to the user base, maximizing positive feedback.To do this, we will send the notifications in waves, gradually optimizing the relevance of the notification according to the user's profile thanks to the contextual bandits that embeds a regression model.
The objective will then be to use his work to optimize the numerous push notification campaigns.





# Les bandits manchot, multi-armed-bandit

L’implémentation de modèles de Deep Learning pour encoder les pro ls utilisateurs(les mots clés des méthodes utilisées : Embedding, HashingTrick, Multi-task learning, Auto-encoder).
L’utilisation des encodages des utilisateurs à divers problèmes marketings, notamment l’optimisation de campagnes de noti cations. Pour cela, l’encodage précédemment appris sera utilisé en entrée d’un algorithme de bandits contextuels (c’est comme le renforcement, mais d’avantage axé sur la convergence rapide au détriment de relations complexes entre les variables, c’est pour ça qu’on fait un encodage avec du deep avant). Dans le cas des campagnes de noti cations, le but sera d’envoyer des noti cations au parc d’utilisateurs, en maximisant un retour positif. Pour cela, on enverra les noti cations par vagues, en optimisant petit à petit la pertinence de la noti cation en fonction du pro l utilisateur grâce à l’algorithme
de bandits contextuels qui embarque un modèle de régression.
L’objectif sera ensuite d’utiliser ses travaux pour optimiser les nombreuses campagnes de push notification.
