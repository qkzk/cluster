# Raspberry Pi Cluster Project

## Objectif

Créer un cluster de raspberry pi dans un but pédagogique afin d'illustrer

* le parallélisme
* le partage de Ressources
* le contrôle à distance des machines

etc.

## Matériel estimation

| Objet            	| dispo 	| souhaité 	| prix  	| prix total 	|
|------------------	|-------	|----------	|-------	|------------	|
| raspberry pi 2   	| 8     	| 6        	| 0     	| 0          	|
| cartes sd        	| 2     	| 8        	| 2.70  	| 21.60      	|
| alim usb 8 ports 	| 0     	| 1        	| 15.00 	| 15.00      	|
| switch 8 ports   	| 0     	| 1        	| 14.00 	| 14.00      	|
| câbles RJ45 1m   	| 2     	| 8       	| 2.00  	| 16.00      	|
| câble micro usb  	| 0     	| 8        	| 2.00  	| 16.00      	|
| cluster case     	| 0     	| 1        	| 18.00 	| 18.00      	|
| grand total      	|       	|          	|       	| 100.60     	|


## Sources

## Change log

### Day 1 : 2019/12/24

* revue du matériel disponible

grosso modo les raspberry...
manque plus ou moins tout le reste pour le projet final

Le plus important c'est le switch, le reste je peux me débrouiller
donc je vais acheter un switch 8 ports gibabits et attendre pour le reste

* booter et établir le ssh password less sur ceux qui ont une carte sd prête

**cluster avec 6 raspberry**

* cluster1
  * sd done
  * ssh done
  * ip 192.168.1.101 done
* cluster2
  * ip 192.168.1.102 done
* cluster3
  * ip 192.168.1.103 done
* cluster4
  * ip 192.168.1.104 done
* cluster5
  * ip 192.168.1.104 done
* cluster6
  * sd done
  * ssh done
  * ip 192.168.1.106 done

**ansible**

* crée la team : done
* créer un playbook pour mettre à jour
