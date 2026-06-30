# TELAUDIT - Guide utilisateur

## 1. Présentation

TELAUDIT est une application Windows permettant de transformer des sauvegardes IPBX en documentation professionnelle.

Il peut générer des rapports PDF, rapports HTML, exports CSV, schémas et constats d'audit automatiques.

L'analyse est effectuée localement. Aucune donnée IPBX n'est envoyée sur Internet.

## 2. Première utilisation

1. Lancez TELAUDIT.
2. Sélectionnez la langue.
3. Glissez-déposez une sauvegarde ou cliquez sur le bouton de sélection.
4. Choisissez le dossier de sortie si nécessaire.
5. Cliquez sur **Analyser et générer**.

Formats actuellement acceptés : `.tar`, `.tar.gz`, `.tgz` et `.gz`.

## 3. Résultats

Après analyse, TELAUDIT crée les fichiers dans le dossier de sortie sélectionné.

Les sorties courantes incluent :

- rapport PDF ;
- rapport HTML ;
- exports CSV ;
- CSV d'audit ;
- schéma PNG ;
- schéma Draw.io.

## 4. Comprendre le rapport PDF

Le rapport PDF peut inclure :

- page de couverture ;
- informations IPBX détectées ;
- schéma général ;
- routes entrantes ;
- queues ;
- extensions ;
- informations de renvois d'appels ;
- constats d'audit automatique.

## 5. Comprendre l'audit

L'audit signale des points utiles à vérifier.

Exemples :

- queue vide ;
- trunk inutilisé ;
- route sans destination claire ;
- IVR avec destination inconnue ;
- extension référencée mais absente.

Niveaux possibles :

- critique ;
- important ;
- avertissement ;
- information.

## 6. Comparer deux sauvegardes

Activez l'option de comparaison et sélectionnez une deuxième sauvegarde.

TELAUDIT peut détecter les ajouts, suppressions et modifications lorsque les informations disponibles le permettent.

## 7. À propos et support

Le menu **À propos** affiche :

- version de l'application ;
- nom du projet ;
- contact officiel ;
- rappel de l'analyse locale.

Le bouton de copie des informations système peut aider à préparer une demande de support.

Page de soutien : https://ko-fi.com/telaudit  
Contact : telauditwin@gmail.com

## 8. Notes de sécurité

TELAUDIT n'exécute aucun script issu de la sauvegarde.

L'analyse est locale.

Aucune connexion Internet n'est nécessaire pour l'analyse.

## 9. Dépannage

En cas de problème, vérifiez :

- que la sauvegarde est complète ;
- que l'extension du fichier est supportée ;
- que le dossier de sortie est accessible en écriture ;
- que l'antivirus n'a pas bloqué l'exécutable ;
- que vous utilisez la dernière version de TELAUDIT.

Avant de signaler un problème, anonymisez les fichiers sensibles si vous devez les partager.
