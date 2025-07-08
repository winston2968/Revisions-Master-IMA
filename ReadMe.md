# 📚 Plan de Révision – Master Intelligence Artificielle (été)

## 🧠 Objectifs généraux

- Consolider les bases théoriques en **probabilités** et **optimisation**
- Pratiquer les méthodes de **simulation** et implémenter des algorithmes
- Rédiger une **fiche de révision complète en probabilités**
- Être prêt pour les cours/examens en IA, stats, simulation, etc.

---

## ✅ À réviser par thème

### 🔵 Probabilités

#### Variables aléatoires (VA)
- Définition d’une VA, loi de probabilité
- Espérance, variance, moments
- Loi discrète vs continue
- Lois classiques : Bernoulli, Binomiale, Poisson, Géométrique, Exponentielle, Normale

#### Loi des Grands Nombres
- LLN faible et fort (définitions, intuition)
- Démonstrations simples
- Application à la convergence de Monte Carlo

#### Théorème Central Limite
- TCL classique (i.i.d., loi normale)
- Version multivariée
- Applications à l’estimation

#### Méthodes de Monte Carlo
- Estimation d’intégrales
- Approximation de constantes
- Analyse de l’erreur (biais, variance)
- Importance du TCL

#### Inégalités de concentration *(facultatif mais utile)*
- Chebyshev, Hoeffding
- Bahadur-Rao, Cramér-Chernoff (à lire seulement si temps)

#### Chaînes de Markov
- Définition, transition, matrice
- Espaces d’états finis et continus
- Simulation d’une chaîne
- Convergence vers l’invariant

#### TD Université
- Faire tous les exercices du TD
- Ajouter dans la fiche les définitions/manips utiles

---

### 🟠 Optimisation

#### Problèmes sans contraintes
- Descente de gradient, taux de convergence
- Méthode de Newton
- Propriétés des fonctions (Lipschitz, différentiabilité)

#### Problèmes avec contraintes
- Méthode des multiplicateurs de Lagrange
- Conditions de Karush-Kuhn-Tucker (KKT)
- Méthode de projection sur un convexe

#### Convexité et topologie
- Ensemble convexe, fonction convexe
- Fermeture, compacité, coercivité
- Lien entre topologie et existence d’un minimum

#### Programmation d’algorithmes
- Gradient sur fonction quadratique
- Newton avec matrice Hessienne
- Optimisation avec contraintes simples

---

### 🟢 Simulation (cours de 6 ECTS)

#### Simulations de VA et Monte Carlo
- Méthode de la fonction de répartition inverse
- Méthode du rejet
- Méthode de Box-Muller (génération loi normale)
- Monte Carlo brut (avec erreur)

#### Rééchantillonnage
- Bootstrap (intervalles de confiance)
- Jackknife
- Validation croisée pour estimation

#### Simulation dans modèle gaussien
- Vecteurs gaussiens
- Conditionnement gaussien
- Régression linéaire gaussienne
- Filtrage de Kalman
- TCL multidimensionnel

#### Grandes déviations *(bonus)*
- Inégalités : Chebyshev, Hoeffding, Cramér

#### Chaînes de Markov
- Simulations d’états
- Estimations de transition
- Illustration de la convergence

---

## 📅 Planning hebdomadaire (8 semaines)

| Semaine | Thèmes | Objectifs détaillés |
|--------|--------|----------------------|
| **S1** | Probas (VA, LLN), Opti (sans contraintes), Simu (Monte Carlo brut) |<ul><li>Rédiger fiche : définitions VA, espérance, variance</li><li>Faire démo LLN + exos</li><li>Implémenter Monte Carlo brut (intégrale simple)</li><li>Réviser gradient descente (algorithme + code)</li></ul>|
| **S2** | TCL, Monte Carlo, Opti (avec contraintes), Simu (méthodes inversion, rejet) |<ul><li>Fiche : TCL, preuve, applications</li><li>Implémenter méthode de rejet</li><li>Faire 1 exo Lagrange</li><li>Code : Newton 1D + gradient 2D</li></ul>|
| **S3** | TD Toul, Convexité/topologie, Simu (bootstrap, jackknife) |<ul><li>Faire tous les exos du TD Toul</li><li>Ajouter parties à la fiche (résumés + techniques vues dans les exos)</li><li>Rappels topologie/convexité (théorie + exemples)</li><li>Bootstrap sur estimation d’une moyenne</li></ul>|
| **S4** | Rédaction fiche + exos, Opti (méthodes numériques), Simu (Box-Muller, gaussienne) |<ul><li>Compléter fiche (focus loi normale, exemples)</li><li>Implémenter Box-Muller + visualisation</li><li>Exercices optimisation avec descente</li></ul>|
| **S5** | Inégalités de concentration, Opti (exos complexes), Simu (conditionnement, régression) |<ul><li>Fiche : Chebyshev + Hoeffding</li><li>Exemple simple régression gaussienne</li><li>Simuler le conditionnement</li></ul>|
| **S6** | Chaînes de Markov (introduction), Kalman, Simu |<ul><li>Simulation d’une chaîne de Markov finie</li><li>Implémenter Kalman simple</li><li>Faire point sur convergence + invariante</li></ul>|
| **S7** | Relecture, exercices transverses, fiche optimisation |<ul><li>Finaliser fiche probas</li><li>Rédiger fiche optim</li><li>Refaire exos simul + Markov</li></ul>|
| **S8** | Révisions générales, mini-projet |<ul><li>Revoir toutes les méthodes codées</li><li>Corriger les fiches</li><li>Préparer projet simulation s’il y en a un</li></ul>|

---

## 🛠️ Conseils pratiques

- Gérer ta fiche de probas en **LaTeX** ou **Markdown** (structure claire)
- Conserver un dossier `simu/` pour tous les scripts de simulation
- Si besoin : crée un dépôt Git (`probas-ai`) pour versionner ton travail
- Une fois par semaine, **relire tes notes de simulation** comme si tu devais les enseigner

---

## 📦 Bonus si temps

- Lire sur **méthodes MCMC** (Metropolis-Hastings, Gibbs)
- Regarder un cas réel d'application du **filtrage de Kalman**
- Implémenter un **simulateur simple de chaîne de Markov cachée**
