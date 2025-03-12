# GIT MAVEN JUNIT

## TP 0
- Penser à bien configurer les alias pour gagner du temps
- Penser à bien configurer les couleurs pour la lisibilité

## TP 1
- "oubli" page 40 : il faut supprimer le tag "bugTag" (`git tag -d bugTag`) pour que le commit concerné n'apparaisse plus dans le `git log`
- Ne pas supprimer le travail : vous en aurez besoin pour le TP2
- COR - check git lol a la fin. 5pts en - par différence + -2pts pour le flag s'il est resté. Importance noms des commits.

## TP 2
- P3, sur la gommande `git log`, certains caractères peuvent poser problème en cas de copier/coller
- P6, le screen montre "enumerating 3 objects" alors qu'il y en a 5 sur le repo des étudiants
- P12, pour la création des "Personnal Access Token", la bonne url est : https://gitlab.esiea.fr/-/user_settings/personal_access_tokens
- P12, pour la création du repo "helloworld", laissez la case "readme" active
- P13 : si vous avez des soucis en executant la commande `ssh -T git@gitlab.esiea.fr`, essayez de vous mettre en 4G !
- P14 : si une interface graphique s'ouvre en vous demandant un mot de passe, vous avez probablement cloner l'URL de votre repo en HTTP plutôt qu'en SSH !
- LIVRABLES : faire les commandes log & reflog dans tous les dossiers. Les zipper tous dans un seul dossier et livrer ce dossier. Pensez à ajouter kévin niel au repo gitlab avec le rôle maintainer.
- COR : check 5 repo, merge request fork, clone grocery

## TP 3 - Rappels Java

## TP 4 - UnitTest
- C'est bien kevin niel qu'il faut ajouter en maintainer !

## TP 5 - UnitTest
- L'image "reference-grayscale" n'est pas bonne dans le TP de base. Remplacez là par celle qui est dans ce repository !

# SOLID

## TP 6
- Développez toutes vos classes dans un seul fichier "Orchestra" pour pouvoir tout soumettre facilement dans moodle pour le TP !
- URL repo : https://gitlab.esiea.fr/felicia.ionascu/solidanddesignpatterns-2025/-/tree/main/src/main/java/fr/esiea/tools/solid?ref_type=heads
- Ne pas implémenter la classe "Music", ce sont les tests dans Moodle qui vont exécuter les tests qui sont sensé être dedans !
- N'oubliez pas de tout lire dans les énoncés ! notamment pour la classe "Stringed" de l'exercice 2 !

## TP 7

- n'oubliez pas de me mettre en tant que `maintainer` sur votre repo gitlab (`kevin.niel@ext.esiea.fr` ou `@kevin.niel`)
- COR : Barème sur doc des 4 attentes : 3 / 3 / 7 / 7

# DESIGN PATTERNS

## TP 8

## TP 9

## TP 10

## Questions globales

### Interface ou Classe Abstraite ?

🔥 Récap rapide :
Critère	| Interface	| Classe Abstraite
--- | --- | ---
Héritage multiple	| ✅ Oui | ❌ Non
Implémentation par défaut |	❌ Non |	✅ Oui
Définition d’un contrat |	✅ Oui |	✅ Oui
Ajout de nouvelles méthodes sans casser l’existant | ❌ Non (risque de casser les implémentations existantes) |	✅ Oui (car les enfants héritent des nouvelles méthodes par défaut)
Utilisation en tant que type parent |	✅ Oui | ✅ Oui
