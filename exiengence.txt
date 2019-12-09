# Exigence dans le lab (binôme : Quentin CESCHIN et Ancelin GLORIES)

Le client veut  affichage d’un indicateur de santé de la maison sur la température [ici](https://github.com/quentinceschin123456/re-experimentations/blob/master/README.txt#L5)


## Les mesures classées par dommaine:
### Environnement
#### Qualité de l'air :

Mesure de paramètre physique ne dépendant pas l'utilisateur : 
* Le client veut mesurer la température
* Le client veut mesurer le taux d'humidité
* Le client veut mesurer le taux de CO²
* Le client veut mesurer le taux de COV
* Le client veut mesurer le déplacement de l'air -> (taux d'aeration)

### Consomation
#### Electrique
* Le client veut mesurer la consomation électrique en details 


#### Eau
* Le client veut pouvoir connaitre sa consomation d'eau
### Production electrique
* Le client veut pouvoir connaitre la production électrique de sa maison
### Rendement electrique 
* Le client veut pouvoir connaitre le rendement électrique de sa maison
### Domotique
 Dans l'optique de mesurer la consomation életrique, il faut mesurer la consomation des objets automatisées de la maison

## Les Analyses

Les résultats des messures doivent être intelligibles par l'homme, instantanées et modélisées avec des graphiques.
On pourra les regroupés de cette façon :
* Qualité de l’air
* Consommation électrique (par rapport à une journée type de la saison ou bien en €)
* Production électrique (par rapport à une journée type de la saison ou bien en €)
* Voiture (en capacité de déplacement)
* Quantité d’eau chaude (en nombre de douche ou autres)
* Ratio production/consommation électrique

## Les prévisions

Le système doit être capable de prévoir pour la journée ou pour la semaine 
* l'évolution de la qualité de l'air
* Consommation électrique prévue
* Production d’énergie prévue
* Prévision du ratio production / consommation
* Prédire si le trajet quotidien n'est pas compromis par la charge incomplete de la voiture.


## Les fonctionnaltées

* Le client veut lancer une recharge quotidienne de ça voiture afin qu'elle soit chargée et disponible pour 16h30
* Le client veut pouvoir prendre une douche chaude à 8h10
* Ouvrir la fenêtre pendant 10 minutes
* Ne pas faire entrer de nouveaux visiteurs
* Limiter à 5 pendant les 2 prochaines heures le nombre de personnes présentes dans la maison
* Il faut notifier le client "N’oubliez pas de fermer la fenêtre"
* Faire des signaux sonores (~ alarme environnementale)