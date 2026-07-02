# Tensura Ultimate Base Ruleset

Projet de départ **ultra détaillé** pour un mod Unciv inspiré de *That Time I Got Reincarnated as a Slime*.

## Objectif

Ce dépôt sert de base propre pour construire un vrai **base ruleset** Tensura pour Unciv.
Le squelette initial a été préparé à partir d'un template minimal de base ruleset, puis personnalisé pour un projet orienté Tensura.

## Structure importante

Le dépôt doit garder une structure simple à la racine :

- `jsons/` pour les règles du jeu
- `Images/` pour les icônes et atlas
- `README.md` pour la documentation
- `mod.json` pour les métadonnées du projet

## Point critique

Le réglage important pour qu'Unciv traite ce projet comme un **base ruleset** se trouve dans :

- `jsons/ModOptions.json`

Le champ `"isBaseRuleset": true` doit y rester.

## Direction du mod Tensura

Objectifs du projet :

- Nations : Tempest, Eurazania, Guy Crimson, Ramiris, Farmas, Lizardmen, Orcs, Jura Alliance
- Unités : Rimuru, Benimaru, Shion, Souei, Hakurou, Geld, Milim, Veldora, Guy Crimson, Ifrit
- Bâtiments : Palais de Tempest, Donjon de Ramiris, Autel des Âmes, Caverne de Veldora, Portail Spatial
- Progression : ères Tensura, technologies magiques, économie riche, guerre, domination, diplomatie
- Systèmes : croyances, politiques, terrains spéciaux, merveilles, victoire d'Ascension Divine

## Mise en route rapide

1. Copie ce dossier dans ton repo GitHub.
2. Garde `jsons/` et `Images/` à la racine.
3. Mets ton repo en public.
4. Ajoute le topic GitHub `unciv-mod`.
5. Pour un base ruleset, ajoute aussi `unciv-mod-rulesets`.
6. Teste avec **Download mod from URL** dans Unciv.
7. Lance ensuite **Locate mod errors** après chaque grosse modification.

## Conseils de dev

- Modifie petit à petit, pas 50 fichiers d'un coup.
- Garde des noms stables pour éviter les références cassées.
- Évite d'inventer des `uniques` non reconnus par Unciv.
- Valide souvent tes JSON.
- Sur mobile, fais des commits fréquents depuis Termux.

## Auteur

- GitHub prévu : `Script1-afk`

L'adresse e-mail n'a pas été intégrée automatiquement dans les fichiers publics du projet pour éviter de l'exposer dans un dépôt GitHub.

## Étape suivante

La prochaine étape logique est de remplacer progressivement le contenu générique du template par :

- `jsons/Nations.json` version Tensura
- `jsons/Units.json` version Tensura
- `jsons/Buildings.json` version Tensura
- `jsons/Techs.json` et `jsons/Eras.json` version Tensura
- ressources visuelles dans `Images/`
