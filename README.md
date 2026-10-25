# ⚙️ RETRAUTO — Plateforme Web pour Association Automobile Rétro

> **Projet Universitaire — BUT Informatique Semestre 2 (Parcours DFS)**  
> Conception et développement d'un site web complet, vitrine et applicatif, pour une association fictive de passionnés de mécaniques anciennes, arborant une charte graphique unique inspirée de l'univers *Steampunk*.

---

## 📋 Présentation du Projet

Dans le cadre du parcours **Développement d'Applications et Direction des Systèmes d'Information (DFS)**, ce projet consistait à concevoir un écosystème numérique modélisant les besoins réels d'une structure associative d'envergure (1 200+ membres actifs). 

La plateforme intègre la gestion de la communication de l'association, la valorisation d'une collection de véhicules d'exception, un module d'adhésion interactif et des fonctionnalités de messagerie embarquées.

### Fonctionnalités Clés :
*   **Vitrine Associative :** Présentation de l'histoire, de la chronologie interactive (1998-2025) et de l'organigramme du bureau directeur.
*   **Gestion de Collection :** Catalogue détaillé de véhicules historiques doté d'un module de messagerie asynchrone pour échanger en direct avec les propriétaires de modèles (ex: Bugatti Type 35, Ferrari F40).
*   **Système d'Information & Adhésions :** Formulaire de recrutement complet (Collecte de données sociétaires, préférences de communication, typologies de cotisations).
*   **Gestion Événementielle :** Module de calendrier et de billetterie pour le suivi des rassemblements passés et à venir (Château de Versailles, Grand Palais).

---

## 🛠️ Stack Technique & Compétences Clés

Ce projet met en application les fondamentaux de l'ingénierie web et de l'intégration logicielle :

*   **Architecture & Sémantique :** HTML5 structuré pour un référencement et une accessibilité optimisés.
*   **Design & UI Avancée :** CSS3 pur (méthode de *Reset* CSS avancée intégrée) décliné sous une esthétique industrielle/Steampunk personnalisée.
*   **Responsive Web Design (RWD) :** Grilles fluides adaptatives basées sur des technologies modernes (`CSS Grid Layout`, `Flexbox`).
*   **Expérience Utilisateur (UX) :** Optimisation des layouts pour les interactions tactiles sur terminaux mobiles et tablettes (`pointer: coarse`).

---

## 📱 Focus Intégration Responsive & Performance

Une attention particulière a été portée à la flexibilité de l'interface graphique face aux contraintes matérielles, un point essentiel du parcours DFS.

| Breakpoint | Cible Matérielle | Adaptations Ergonomiques Réalisées |
| :--- | :--- | :--- |
| **Max 1024px** | Tablettes / iPad | Bascule du menu en mode wrap, réalignement des grilles en 2 colonnes (`cars-grid`), ajustement des carrousels. |
| **Max 768px** | Mobiles Standard | Transformation de la navigation en liste verticale, simplification des animations lourdes, agrandissement des zones de saisie et boutons de formulaires. |
| **Tactile (Hover: none)**| Périphériques tactiles | Augmentation de la surface de touch (min 44px) pour éviter les erreurs de saisie, désactivation des survols inutiles, micro-interactions au clic (`transform: scale(0.98)`). |
| **Print CSS** | Impression Papier | Suppression complète des éléments superflus (scripts, chat-box, menus, footer) pour assurer une édition propre des fiches techniques de véhicules en noir et blanc. |

---

## 🔒 Sécurité et Qualité du Code

*   **Gestion des Données Sensibles :** Implémentation de mécanismes d'exclusion de fichiers de configuration locaux via `.gitignore` (clés et variables d'environnement).
*   **Robustesse :** Isolation stricte des styles CSS pour prévenir les régressions visuelles lors du redimensionnement (Biais d'affichage mobile éliminés).

---

## 🚀 Installation et Lancement Rapide

### Prérequis
Un navigateur web moderne (Chrome, Firefox, Safari ou Edge).

### Procédure
1. Clonez le dépôt sur votre machine locale :
   ```bash
   git clone https://github.com
   ```
2. Ouvrez le répertoire du projet :
   ```bash
   cd retrauto-club
   ```
3. Lancez le fichier principal dans votre navigateur :
   ```bash
   open index.html
   ```

---

## 📈 Perspectives d'Évolution (BUT 2 / DFS)
Dans une optique d'évolution vers une architecture de Système d'Information robuste, les prochaines étapes de ce projet incluent :
1. La persistance des données du formulaire d'adhésion via une base de données relationnelle (SQL / PostgreSQL).
2. La dynamisation du système de messagerie des véhicules à l'aide d'un back-end orienté objet (Java / PHP).



