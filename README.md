# Cors-issue-camunda7-docker
correction (Response to preflight request doesn't pass access control check: It does not have HTTP ok status). 
4 etapes

1 étape: télécharger les jar suivant: - camunda-engine-rest-core-7.18.0-alpha3.jar 
-javax.ws.rs-api-2.1.1.jar

2 étapes: recopier code et compile: javac avec la version 11 de java (camunda7.18.0)

3 étapes: colle le code avec la commande docker cp

4 étapes: redemarer camunda7

Surcharge de la classe DefaultApplication.class utilise pour l'api engine-rest. 
