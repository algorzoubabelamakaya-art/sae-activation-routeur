# sae-activation-routeur

Automatisation de la mise en service, du contrôle et de la supervision d'un routeur client



\## Problématique

Comment automatiser et fiabiliser la mise en service d'un routeur client

chez un opérateur B2B afin de vérifier son bon fonctionnement, de le

superviser et de faciliter le traitement des anomalies ?



\## Contexte

Projet inspiré de mon stage au service Activation de Linkt, opérateur

télécom B2B, où une mise en service n'est terminée qu'après des vérifications.



\## Chaîne complète visée

1\. Une demande de mise en service est créée dans GLPI.

2\. Un script Python configure le routeur du client.

3\. Le script lance des contrôles automatiques (interface, connectivité, DNS, SNMP).

4\. Il rend un verdict : activation conforme ou non conforme.

5\. Si conforme, l'équipement est ajouté à la supervision (Observium).

6\. En cas d'anomalie ou de panne, un ticket est créé automatiquement dans GLPI.



\## Version minimale (objectif prioritaire)

Un script Python qui configure le routeur, lance les 4 contrôles

et affiche « conforme » ou « non conforme ».



\## Extensions (si le temps le permet)

\- Ajout automatique dans Observium

\- Création automatique de tickets dans GLPI



\## Outils

Python (netmiko), routeur Cisco, GLPI, Observium, Git.



\## Auteure

Algor ZOUBABELA MAKAYA

