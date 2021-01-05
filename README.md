[:arrow_left: Retour vers le portfolio](https://github.com/ThibaultLanthiez/Portfolio)

# Web scaping

Le but de ce projet était de découvrir le web scraping et ses applications.

Mon objectif était, via des techniques de web scraping, d'obtenir les coordonnées géographiques de chacune des capitales des pays du monde. 

Mon lien d'entrée était la [page wikipedia des capitales](https://fr.wikipedia.org/wiki/Liste_des_capitales_du_monde). Pour aller dans cette page, j'ai utilisé une librairie python nommée BeautifulSoup. Puis en itérant dans la liste des capitales présentes sur la page, j'ai pu obtenir les noms des capitales. 

Ensuite, j'ai utilisé Selenium pour naviguer dans chacune des pages correspondantes aux noms de capitales précédemment obtenues. Ainsi, j'ai pu obtenir la position de toutes les capitales. Voici un exemple pour [Paris](https://fr.wikipedia.org/wiki/Paris#/maplink/0) : serez-vous retrouver ses coordonnées géographiques ?

# Code

Voici le notebook du projet : [notebook](https://github.com/ThibaultLanthiez/Web-scaping/blob/main/Projet_5_Web_Scaping_Position_des_capitals.ipynb)
