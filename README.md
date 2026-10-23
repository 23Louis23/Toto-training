# Toto Training App

App de suivi pour le cycle **Base renfo** de Toto (6 semaines, 2 séances par semaine, 12 séances au total). Elle utilise la **même base de données Supabase** que les apps de Jox, Loan, Fifi, Manon, Suzy et Killian — pas besoin de recréer un compte ou un projet.

## Programme

- Semaines 1-2 : RPE 7. Semaines 3-4 : RPE 8. Semaine 5 : RPE 8-9. Semaine 6 : allégée, 2 séries par exercice.
- Nordic curl : 3×4, puis 4×5, puis 4×6.
- Objectif : apprendre les mouvements, construire une base de force générale et renforcer tendons et ischios.

## 1. Base de données

✅ Déjà faite — la colonne `athlete` ("Toto") sépare ses données de celles des autres athlètes.

## 2. Configurer l'appli

✅ Déjà fait — `index.html` contient l'URL et la clé Supabase, et un code d'accès (`3948` par défaut, modifiable en cherchant `APP_PIN` dans le fichier).

## 3. Déployer sur Vercel (gratuit) — sans rien installer

1. Crée un nouveau repo GitHub (ex: `toto-training-app`).
2. Upload les 2 fichiers (`index.html`, `README.md`) via "uploading an existing file".
3. Va sur [vercel.com/new](https://vercel.com/new), importe ce repo, déploie avec les réglages par défaut.
4. Récupère l'URL propre du projet dans la section "Domains".

## 4. Utilisation

Envoie l'URL + le code `3948` à Toto. À chaque séance : Hooper, charges, notes, puis "Enregistrer la séance". Le site s'ouvre directement sur la séance qui suit la dernière séance faite.
