Ce projet décrit des API publiées par le département et disponibles sur api.loire-atlantique.fr

Il contient :
* une description des API au format OpenApi v3 (fichier openapi.json)
* un site de documentation (basé sur swagger-ui)
* un script de test de toutes les API (Dossier jMeter)

jMeter
------

Test des différents point d'entrée de l'API
A éxécuter à chaque modification d'une API ou de la configuration Apache

Exemple de script d'utilisation :

```bash
/usr/share/jmeter/bin/jmeter.sh -n -t api-la-fr.jmx -l api-la-fr.xml
```

En retour :
* api-la-fr.xml : Résultat du test au format XML
* jmeter.log : console d'éxécution
* resultat.csv : tableau des résultats agrégés