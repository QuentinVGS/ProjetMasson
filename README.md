# ⚽ Projet Web : L'Actu Foot

## 🎯 Objectif
Créer un site web complet avec un **front office** et un **back office**, basé sur le wireframe fourni, et ayant pour thème le football. Le site est **responsive** et utilise une base de données pour afficher et gérer des informations via des jointures SQL.

---

## 🧱 Structure du site

### 🧭 Front Office (utilisateur)
- **Accueil** : dernières actualités du football avec images.
- **Navigation latérale** : liens vers les différentes pages.
- **Section "Classement / Statistiques"** à droite.
- **Pages dynamiques** :
  - `Accueil` : news football.
  - `Matchs` : calendrier des matchs à venir + matchs passés.
  - `Liste` : affichage des joueurs de la base de données.

📌 **Design conforme au wireframe fourni**.

---

### 🔐 Back Office
Fonctionnalités :
- **Ajouter** un joueur dans la base.
- **Modifier** les informations d’un joueur.
- **Supprimer** un joueur.
- Accès protégé (champs obligatoires + sécurisation de la suppression/modification via ID).

---

## 💾 Base de données
- Une table `joueurs` (nom, prénom, date de naissance, pays, poste)
- Une table `match_foot` (date, compétition, équipes, score, lieu)
- Une table `equipe` (nom, pays, ville, anne_fondation)
- Une table `pays` (nom, code)
- Utilisation de **jointures SQL** pour relier les informations lors de l’affichage.

---

## 🛠️ Technologies utilisées
- HTML / CSS
- PHP (avec includes pour l'optimisation des pages)
- SQL (MySQL via WAMP)
- Utilisation du système de routing simple avec `?id=page`
- Responsive design via `flexbox`

---

## ✅ Livrables
- `brief_projet.md` : ce fichier
- `index.php` + dossier `pages/` + `css/` + `decoupes/`
- Site responsive fonctionnel
- Backoffice avec authentification
- Utilisation de `include()` pour éviter la redondance

---

## 👨‍💻 Équipe projet
- Quentin Veigas.
- Emrane Smaki
- Riyad Menas
