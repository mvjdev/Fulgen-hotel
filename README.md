# Fulgen-hotel
Hotel database implementation
```
##Cahier de charge (client et prestataire)
###Gestion des réservations :
.Les clients peuvent réserver des chambres d'hôtel.
.Les chambres peuvent être de différents types : chambre simple, chambre double, gamme familiale et VIP.
.Ils peuvent aussi réserver 1 salle de conférence
.Il est possible de vérifier la disponibilité des chambres,salles de conférences.
.La réservation doit être effectuée avant 12h avec une vérification.
.Les réservations peuvent être annulées avec une pénalité de 20%.
###Gestion des paiements :
.Les paiements peuvent être effectués soit en totalité, soit à l'avance.
.Les modes de paiement acceptés sont l'espèce (paiement directement à l'hôtel) et le mobile money.
.Il est possible de vérifier qui n'a pas encore effectué le paiement.
.Une prolongation de réservation de 3 jours est autorisée.
.Des réductions peuvent être appliquées, notamment pour les clients fidèles (5% de réduction sur le prix de base).
###Services complémentaires :
.Il est possible de louer une salle de conférence moyennant des frais de 50 000 Ar.
.Un service de recommandation de plats est disponible, avec une liste de plats proposés.
.Différents services sont proposés, tels que le service familial et le service VIP.
###Utilisateurs et rôles :
.Les visiteurs peuvent consulter les chambres et le restaurant.
.Les utilisateurs peuvent modifier leurs réservations, créer un compte, consulter leurs réservations, et fournir des informations personnelles telles que le nom, le numéro de CIN, le numéro de téléphone et le genre.
.Les réceptionnistes ont accès aux réservations, peuvent voir si elles ont été payées ou non, et ont la responsabilité de recevoir les paiements des clients.
.Les administrateurs peuvent modifier les informations financières.
###Gestion des disponibilités :
.Si toutes les chambres sont déjà occupées, les réservations des nouveaux clients sont rejetées et des chambres libres sont proposées à un autre moment.
.Il est possible de spécifier le nombre de personnes dans une réservation.
###Autres informations :
.Le système doit prendre en charge les langues français et malgache.
.La réduction appliquée peut varier en fonction des décisions de l'hôtel.
.Les réceptionnistes doivent avoir un compte pour accéder au système.
.L'horaire de travail des réceptionnistes est lié à la réception des paiements des clients.
```
