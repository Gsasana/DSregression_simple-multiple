# DSregression_simple

L’objectif est de se familiariser avec la notion de régression linéaire. 

On prédit la valeur de Y à partir des mesures des valeurs de X. 

Le modèle usuel de régression linéaire simple est le suivant :  𝑦=β0+β1𝑥+ε𝑦=β0+β1𝑥+ε
où :
-	Y est une variable quantitative continue à expliquer (ou variable dépendante). 
-	X est une variable quantitative continue explicative. 
-	Ε est un terme d’erreur aléatoire de loi normale d’espérance nulle et d’écart-type σ.


Le modèle de régression estimera les coefficients β0 et β1 par β̃0 et β̃1, nous permettant de calculer les valeurs ajustées 𝑦̃ =β̃ 0+β̃ 1𝑥𝑦~=β~0+β~1𝑥.


Les résidus sont définis par ε=𝑦−𝑦̃ 



Le jeu de données utilisé dans la suite contient de nombreuses caractéristiques à propos de différentes voitures observées en 1985. 
Par soucis de simplicité, seules les variables numériques ont été gardées et les lignes comprenant des valeurs manquantes ont été supprimées. 


•	L’attribut ‘symbolling’ correspond au degré de risques de la voiture que l’assurance estime. 
•	L’attribut ‘normalized_losses’ est le coût moyen relatif par an d’assurance du véhicule . Cette valeur est normalisée pour les voitures appartenant à la m^me classe de types de véhicule.
•	Les 13 attributs suivants concernent les caractéristiques techniques des différentes voitures comme la largeur, la cylindrée de moteur, le cheval-vapeur…
