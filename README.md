# Lab 2 MLOps 
## Étape 1 : Initialisation de Git (mlops-lab-01)

Objectif

Initialiser un dépôt Git pour assurer le suivi de versions du projet mlops-lab-01.

1. Initialisation du dépôt Git

Commande utilisée :

<img width="941" height="92" alt="image" src="https://github.com/user-attachments/assets/86d45cdf-93c6-46f4-9dcd-5f3d45226640" />
2. Création du fichier .gitignore

Le fichier .gitignore permet d’exclure certains dossiers et fichiers du suivi Git.

![WhatsApp Image 2025-12-13 à 15 07 40_78ad870c](https://github.com/user-attachments/assets/b0a8fbd9-2879-44f6-a738-8f73f21dc3ec)

3. Vérification de l’état du dépôt

Commande utilisée :

![WhatsApp Image 2025-12-13 à 15 09 14_c577d763](https://github.com/user-attachments/assets/5355ca82-091b-446d-9b5a-f1a763351b3b)


Cette commande permet de vérifier l’état des fichiers du dépôt.

## Étape 2 : Premier commit du projet MLOps
Objectif

Versionner la structure initiale du projet à l’aide d’un premier commit Git.

1. Ajout des fichiers et dossiers au suivi Git

Commande utilisée :

![WhatsApp Image 2025-12-13 à 15 09 58_6ecef696](https://github.com/user-attachments/assets/71f9966e-781f-4cec-90a0-4249ce0a3060)


Cette commande permet d’ajouter le code et les fichiers de configuration au dépôt.

2. Création du premier commit

Commande utilisée :

![WhatsApp Image 2025-12-13 à 15 10 36_92286610](https://github.com/user-attachments/assets/ea5f4f93-0ecb-4f46-b458-831a59bc8414)


Ce commit marque la création officielle de la structure initiale du projet MLOps.

3. Affichage de l’historique des commits

Commande utilisée :

![WhatsApp Image 2025-12-13 à 15 11 04_9d629849](https://github.com/user-attachments/assets/2947d8fc-f9e3-48a6-831a-6866f94c3b60)


Cette commande affiche l’historique simplifié des commits.

## Étape 3 : Observer une modification avec git diff
Objectif

Analyser une modification de code avant et après son ajout à l’index Git.

1. Modification d’un script existant

Le paramètre z_threshold est modifié dans le fichier suivant :
<img width="1182" height="354" alt="image" src="https://github.com/user-attachments/assets/064d4498-bd50-4f47-9aa3-4e262d673bb5" />

2. Affichage des différences non indexées

Commande utilisée :

![WhatsApp Image 2025-12-13 à 15 13 16_e014608f](https://github.com/user-attachments/assets/5c326820-0b06-456b-9a25-c05cdaf74830)


Cette commande affiche les différences entre le fichier modifié et le dernier commit.

3. Ajout du fichier modifié à l’index

Commande utilisée :

<img width="1135" height="92" alt="image" src="https://github.com/user-attachments/assets/21543f62-8ca8-4743-b943-bf95f043635a" />

4. Création du commit

Commande utilisée :

<img width="1677" height="238" alt="image" src="https://github.com/user-attachments/assets/296acc97-8600-4a62-8e40-a129b98e9e6d" />

## Étape 4 : Création d’une branche de fonctionnalité

Objectif
Isoler le développement d’une nouvelle fonctionnalité à l’aide d’une branche Git dédiée.

1. Création de la branche

Commande utilisée :

<img width="1287" height="77" alt="image" src="https://github.com/user-attachments/assets/93e1bc9c-16ca-4874-8b97-a75d9e68e97c" />

2. Modification du fichier src/api.py

Ajout d’une logique simple pour la gestion automatique de request_id, j'ai changé sa valeur de None à 2.

<img width="826" height="255" alt="image" src="https://github.com/user-attachments/assets/54b39697-c3fa-4b05-a207-7ee284d58092" />

3. Ajout et commit des modifications

Commandes utilisées :

<img width="1094" height="131" alt="image" src="https://github.com/user-attachments/assets/23eecfee-124b-49f7-a6f8-bcabe4cc42a3" />

4. Liste des branches

Commande utilisée :

<img width="642" height="135" alt="image" src="https://github.com/user-attachments/assets/503ca6ec-8896-4d86-973e-afb424803d46" />

5. Retour à la branche principale

Commande utilisée :

<img width="690" height="93" alt="image" src="https://github.com/user-attachments/assets/5d940ff8-26ba-4dcd-8d4b-5202181d75c0" />

## Étape 5 : Fusion de la branche feature

Objectif

Intégrer la fonctionnalité développée dans la branche principale du projet.

1. Positionnement sur la branche principale

Commande utilisée :

![WhatsApp Image 2025-12-13 à 15 25 05_ad830b49](https://github.com/user-attachments/assets/ff0f7b98-f997-4017-84e6-2f2b86b11fab)

2. Fusion de la branche feature

Commande utilisée :

![WhatsApp Image 2025-12-13 à 15 30 34_4baa23f9](https://github.com/user-attachments/assets/8b5897af-98ff-4133-be83-9f04effb38f9)

Cette commande intègre les changements de la branche feature.

3. Vérification de l’historique

Commande utilisée :

![WhatsApp Image 2025-12-13 à 15 30 53_882a31f1](https://github.com/user-attachments/assets/52cbb56b-da86-4be6-9c53-0c172d60612a)

## Étape 6 : Création et résolution d’un conflit de merge

Objectif

Simuler un conflit Git et apprendre à le résoudre correctement.

1. Création d’une nouvelle branche

Commande utilisée :

![WhatsApp Image 2025-12-13 à 15 33 17_0c8a9a98](https://github.com/user-attachments/assets/e582f574-b859-402e-aae4-b31854d89c71)

2. Modification dans la branche feature

Modification du paramètre gate_f1 dans :src/train.py

![WhatsApp Image 2025-12-13 à 15 33 43_e3a4d14e](https://github.com/user-attachments/assets/5e98004f-9a96-4f14-9af8-0620fe6a32a2)


Valeur définie à 0.60.

![WhatsApp Image 2025-12-13 à 15 34 13_13af5022](https://github.com/user-attachments/assets/f18eeb7a-604f-4ee5-9ddd-2c11d60967ae)

3. Modification concurrente sur la branche principale

Retour sur la branche principale :

![WhatsApp Image 2025-12-13 à 15 37 10_08525acb](https://github.com/user-attachments/assets/710169d9-c2eb-450d-b1de-1269f5c61764)


Modification de la même ligne avec la valeur 0.75, puis commit : 
![WhatsApp Image 2025-12-13 à 15 37 55_84a44127](https://github.com/user-attachments/assets/724186f4-cbc1-481d-928d-27cd2f4a0112)

4. Tentative de fusion et conflit

Commande utilisée :

<img width="1384" height="137" alt="image" src="https://github.com/user-attachments/assets/6960ea13-5006-404d-a742-efa5065a0945" />

Un conflit est détecté dans le fichier src/train.py.

5. Résolution du conflit

Le conflit est résolu manuellement en choisissant la valeur 0.70 pour gate_f1.

![WhatsApp Image 2025-12-13 à 15 43 54_565a9835](https://github.com/user-attachments/assets/bb50dbcc-1d84-452a-a579-087a2c99116a)

## Étape 7 : Utilisation de git stash

Objectif

Mettre temporairement de côté des modifications non finalisées sans créer de commit.

1. Modification non commitée

Ajout d’un commentaire TODO dans le fichier :src/rollback.py

<img width="1092" height="558" alt="image" src="https://github.com/user-attachments/assets/2d1f7466-0f9e-4c46-ba99-fa4595e4caac" />

2. Vérification de l’état du dépôt

Commande utilisée :

<img width="820" height="255" alt="image" src="https://github.com/user-attachments/assets/9bb2532f-fe8c-4730-875a-3c7ab56b13a9" />

3. Mise de côté des modifications

Commande utilisée :

<img width="1170" height="90" alt="image" src="https://github.com/user-attachments/assets/534f5dee-6821-4cfe-b547-d8ad22125f4a" />

4. Liste des stash

Commande utilisée :

<img width="945" height="110" alt="image" src="https://github.com/user-attachments/assets/f221c811-0453-47a0-94b8-c7bb6f038e1c" />

5. Récupération des modifications

Commande utilisée :

<img width="833" height="222" alt="image" src="https://github.com/user-attachments/assets/a8b99894-92ca-435e-b4e9-d5c222d1fbfa" />


Option alternative :

<img width="918" height="284" alt="image" src="https://github.com/user-attachments/assets/56e0e23d-bf24-40cf-91cf-91ecbfa16b3a" />

## Étape 8 : Utilisation de git reset

Objectif

Comprendre les différents modes de git reset (soft, mixed, hard) sur un fichier d’expérimentation.

1. Création d’un dossier et d’un fichier de test

Commandes utilisées :

<img width="1076" height="345" alt="image" src="https://github.com/user-attachments/assets/aa10c465-385f-41d2-9a6d-c874c7aa405e" />

2. Modifications successives et commits

Passage à v2 puis v3 :

<img width="1167" height="279" alt="image" src="https://github.com/user-attachments/assets/7452ed73-5dbb-4490-858f-107be4bca7f3" />

3. Reset soft

Commande utilisée :

<img width="866" height="265" alt="image" src="https://github.com/user-attachments/assets/dbce74f4-a5dd-4f5f-a614-8a77a4d054d9" />

Le commit est annulé mais les modifications restent en staging.

4. Reset mixed

Commande utilisée :

<img width="868" height="253" alt="image" src="https://github.com/user-attachments/assets/d8ca8430-59aa-4896-a6c4-f3b3298909b6" />

Le commit est annulé et les modifications restent dans le working directory.

5. Reset hard

Commande utilisée :

<img width="796" height="180" alt="image" src="https://github.com/user-attachments/assets/328d76b4-18d9-4bfc-b885-d3246d6caf0b" />


Le commit et les modifications sont définitivement supprimés.

## Étape 9 : Annuler un commit avec git revert

Objectif

Annuler un commit sans réécrire l’historique Git.

1. Ajout d’un changement non souhaité

Commandes utilisées :

<img width="956" height="168" alt="image" src="https://github.com/user-attachments/assets/00f68b8c-d694-415c-96e4-8f0faaab2927" />

2. Affichage de l’historique

Commande utilisée :

<img width="844" height="308" alt="image" src="https://github.com/user-attachments/assets/6f3c80d8-e4ca-4f68-be38-e7164790d21b" />

3. Revert du dernier commit

Commande utilisée :

<img width="687" height="117" alt="image" src="https://github.com/user-attachments/assets/00b00d04-1b8a-44b0-aac7-75685431c6fd" />

Cette commande crée un nouveau commit qui annule le changement précédent.

4. Vérification du contenu du fichier

Commande utilisée :

<img width="1060" height="304" alt="image" src="https://github.com/user-attachments/assets/6c6ddda6-56be-4df4-b720-a5ce4141a616" />

<img width="610" height="328" alt="image" src="https://github.com/user-attachments/assets/3ce2ad28-c3df-4691-87e0-0d43418f689b" />

## Étape 10 : Rebase d’une branche feature sur la branche principale

Objectif

Mettre à jour une branche feature avec les derniers commits de la branche principale en conservant un historique linéaire.

1. Création de la branche feature

Commande utilisée :

<img width="898" height="90" alt="image" src="https://github.com/user-attachments/assets/47500764-e1d9-407b-851f-95d52ade97c0" />

2. Modification et commit dans la branche feature

Modification du paramètre last_n dans : src/monitor_drift.py

<img width="939" height="143" alt="image" src="https://github.com/user-attachments/assets/8f1db2af-b71e-4448-a65a-fb9e58afbd2a" />

Valeur définie à 500. Puis ajout et commit des modifications :

<img width="1160" height="143" alt="image" src="https://github.com/user-attachments/assets/5d0bc1ea-de07-40af-b968-89ef51161c80" />

3. Création d’un commit sur la branche principale

Retour sur la branche principale :

<img width="1099" height="86" alt="image" src="https://github.com/user-attachments/assets/bbd34b06-74d6-4d45-abff-0712de51be47" />

Modification d’un autre fichier pour simuler des changements parallèles :

<img width="1098" height="150" alt="image" src="https://github.com/user-attachments/assets/67988d06-50e7-4b5b-93f3-8dc4384fb50b" />

4. Rebase de la branche feature

Retour sur la branche feature :

<img width="851" height="62" alt="image" src="https://github.com/user-attachments/assets/ffb50060-ba51-4a5b-8383-2ccad6de196f" />



Puis rebase sur la branche principale pour intégrer les derniers commits :

<img width="859" height="62" alt="image" src="https://github.com/user-attachments/assets/1288d726-0f06-47ac-baf9-f5f0eb74da37" />



5. Vérification de l’historique

Commande utilisée pour afficher l’historique des commits de manière linéaire :

<img width="996" height="329" alt="image" src="https://github.com/user-attachments/assets/cc77bc7e-1e8d-4ffd-8db3-e832f610976d" />

