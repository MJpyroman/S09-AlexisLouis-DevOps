# S09-AlexisLouis-DevOps

## Stratégie de branches - Git Flow

Ce projet suit une stratégie **Git Flow** : une branche stable (`main`) et une branche de travail par membre.

## Convention de nommage

- `main` — branche principale, toujours stable et déployable. Personne ne pousse dessus directement.
- `user1`, `user2`, `user3`, ... — une branche personnelle par membre du groupe, où chacun développe ses modifications.

## Règle de merge

- Toute intégration vers `main` passe par une **Pull Request (PR)** depuis la branche de l'utilisateur (`user1`, `user2`, ...), jamais de push direct sur `main`.
