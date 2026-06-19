# Pocket Love Destiny - Destinee Matchmaker

Un mini-jeu d'analyse de compatibilité amoureuse basé sur l'astrologie, les langages de l'amour, les loisirs, la vision de vie et le caractère. Développé en Python avec Tkinter, ce jeu genere un score de compatibilite personnalise entre deux personnes.

## Fonctionnalités

- Saisie des profils: prenom, date de naissance, couleur preferee, langage de l'amour, loisirs, caractere et vision de la vie
- Determination automatique du signe astrologique selon la date de naissance
- Calcul du score de compatibilite base sur:
  - Langage de l'amour identique: +10 pts
  - Vision de vie identique: +15 pts
  - Compatibilite des elements astrologiques: +10 pts
  - Loisirs communs: +5 pts
- Affichage d'une citation personnalisee selon le score obtenu
- Interface graphique colorée et conviviale avec avatars masculin/feminin
- Validation d'age (minimum 15 ans requise)

## Technologies utilisées

| Technologie | Version | Rôle |
|-------------|---------|------|
| Python | 3.8+ | Langage de programmation principal |
| Tkinter | Inclus | Interface graphique (GUI) |
| tkcalendar | 3.6+ | Sélecteur de date intégré |
| Pillow (PIL) | 9.0+ | Traitement et manipulation d'images |

## Prérequis

Assure-toi d'avoir installé:

- Python 3.8 ou supérieur
- Les bibliothèques suivantes:

```bash
pip install tkcalendar pillow
```

Note: tkinter est inclus par défaut avec Python sur la plupart des systèmes.

## Comment lancer le jeu

1. Clone ou télécharge ce dépôt
2. Place les fichiers d'avatars dans le même dossier:
   - AvatarBoy.jfif
   - AvatarGirl.jfif
3. Exécute le script:

```bash
python pocket_love_destiny.py
```

4. Remplis les profils des deux personnes et clique sur "VÉRIFIER LE DESTIN"

## Logique de calcul du score

Le score de compatibilité est calculé selon les règles suivantes:

| Critère | Points |
|---------|--------|
| Langage de l'amour identique | +10 |
| Vision de vie identique | +15 |
| Compatibilité des éléments | +10 |
| Loisirs communs | +5 |

Le score final détermine la catégorie de citation affichée:
- Score > 80: Citation "excellent"
- 55 < Score <= 80: Citation "moyen"
- Score <= 55: Citation "faible"

## Design de l'interface

- Couleurs douces et romantiques (pastel rose, beige, blanc)
- Polices Comic Sans MS pour un style ludique
- Avatars en forme circulaire avec masque alpha
- Bulles de dialogue affichant les signes astrologiques

## Notes importantes

- L'astrologie utilisée est symbolique et divertissante, basée sur des tendances observées et non sur des probabilités mathématiques garanties
- Les signes "chanceux" (Poissons, Gémeaux, etc.) proviennent d'études d'observation et ne constituent pas des prédictions fiables
- Ce projet est conçu à but éducatif et divertissant

## Contribuer

Les contributions sont les bienvenues! N'hésite pas à:
- Soumettre des issues pour signaler des bugs
- Proposer des pull requests pour ajouter des fonctionnalités

## Licence

Ce projet est sous licence MIT. Cette licence permissive autorise:

- Utiliser le logiciel pour un usage personnel ou commercial
- Modifier le code source comme bon vous semble
- Distribuer le code original ou modifié
- Sublicencer et intégrer dans d'autres projets
- Vendre le logiciel

Seule obligation: inclure le copyright original et la licence MIT dans toute copie du code. Si quelqu'un utilise ton code, il doit garder ta mention de propriétaire.

Avantages: montre que tu es ouvert à la collaboration, attire d'autres développeurs pour contribuer, et démontre tes compétences tout en restant flexible.

## Auteur

Développé par un développeur full stack passionné par l'astrologie, l'UI/UX et Python.

Amuse-toi bien à tester les compatibilités amoureuses! 