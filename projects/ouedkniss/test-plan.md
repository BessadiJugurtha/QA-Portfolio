# 📄 Plan de Test – Projet Ouedkniss

**Projet :** Ouedkniss – Site e-commerce (achat et vente en ligne, particuliers et professionnels)  
**Type de tests :** Fonctionnels manuels  
**Auteur :** Jugurtha Bessadi  
**Date :** 2025  

---

## 1️⃣ Objectif du test

Vérifier que toutes les fonctionnalités principales du site Ouedkniss fonctionnent correctement selon les spécifications.  
L’objectif est de détecter des anomalies dans :  
- Gestion des utilisateurs  
- Gestion des annonces  
- Recherche et navigation  
- Consultation des annonces  

---

## 2️⃣ Portée du test

- Scénarios classiques et alternatifs pour utilisateurs particuliers et professionnels  
- Création compte, connexion, publication d’annonce, recherche, filtrage, consultation  
- Tests réalisés **manuellement**, avec capture d’écran et documentation des anomalies  

---

## 3️⃣ Scénarios et Cas de test

### Épique 1 : Gestion des utilisateurs

**Scénario U1 : Connexion Standard d'un utilisateur**
- Cas de test U1.1 : Vérifier la connexion avec un nom d'utilisateur et mot de passe valides
- Cas de test U1.2 : Vérifier connexion avec un nom d'utilisateur invalide
- Cas de test U1.3 : Vérifier connexion avec mot passe invalide
- Cas de test U1.4 : Laisser le champ nom d'utilisateur vide
- Cas de test U1.5 : Laisser le champ mot de passe vide
- Cas de test U1.6 : Tentative de connexion avec un compte non enregistré
- Cas de test U1.7 : Tentatives multiples de connexion échouées (plus de 3 tentatives)

**Scénario U2 : connexion via Google ou Facebook d'un utilisateur**
- Cas de test U2.1 : Vérifier la connexion avec une adresse mail valides
- Cas de test U2.2 : Vérifier la connexion avec un compte Facebook  valide
- Cas de test U2.3 : Annulation de l’authentification Google
- Cas de test U2.4 : Annulation de l’authentification Facebook

**Scénario U3 : Deconnexion d'un utilisatuer**
- Cas de test U3.1 : Déconnexion via le bouton “Se déconnecter”
- Cas de test U3.2 : Accès à une page protégée après déconnexion
- Cas de test U3.3 : Utilisation du bouton “Retour” du navigateur après déconnexion
- Cas de test U3.4 : Déconnexion après rafraîchissement de la page
- Cas de test U3.5 : Visibilité du bouton “Se déconnecter”
- Cas de test U3.6 : Déconnexion après inactivité 

**Scénario U4 : Inscription d'un utilisateur**
- Cas de test U4.1 : Inscription avec des données valides   
- Cas de test U4.2 : Saisir un nom d'utilsateur invalide
- Cas de test U4.3 : Sasir mot de passe invalide
- Cas de test U4.4 : Saisir une adresse mail invalide
- Cas de test U4.5 : Ne Pas accepter les condition d'utilisation
- Cas de test U4.6 : Renseigner des données différentes dans les champs « Mot de passe » et « Confirmer le mot de passe »
- Cas de test U4.7 : Laisser le champs "nom d'utilsateur" vide
- Cas de test U4.8 : Laisser le champs "mot de passse"  vide
- Cas de test U4.9 : Laisser le champs "confirmer mot de passe" vide
- Cas de test U4.10 : Laisser le champs "E-mail" vide 

**Scénario U5 : Modification du mot de passe**


---

### Épique 2 : Gestion des annonces

**Scénario A1 : Création d’une annonce**
- Cas de test A1.1 : Tous les champs valides  
- Cas de test A1.2 : Champ obligatoire manquant  
- Cas de test A1.3 : Image trop lourde  
- Cas de test A1.4 : Prix invalide  

**Scénario A2 : Gestion des annonces**
- Cas de test A2.1 : Modification d’une annonce  
- Cas de test A2.2 : Suppression d’une annonce  
- Cas de test A2.3 : Ajout / suppression d’images  

---

### Épique 3 : Recherche et navigation

**Scénario R1 : Recherche par mot-clé**
- Cas de test R1.1 : Recherche avec mot exact  
- Cas de test R1.2 : Recherche avec majuscules / minuscules  
- Cas de test R1.3 : Recherche avec mot inexistant  
- Cas de test R1.4 : Recherche avec caractères spéciaux  

**Scénario R2 : Filtrage et tri**
- Cas de test R2.1 : Filtrage par catégorie  
- Cas de test R2.2 : Tri par prix / date  
- Cas de test R2.3 : Pagination des résultats  

---

### Épique 4 : Consultation des annonces

**Scénario C1 : Affichage d’une annonce**
- Cas de test C1.1 : Détails complets (titre, description, prix, images)  

**Scénario C2 : Interaction avec l’annonce**
- Cas de test C2.1 : Contacter le vendeur  
- Cas de test C2.2 : Partager l’annonce  
- Cas de test C2.3 : Ajouter aux favoris  

---

## 4️⃣ Suivi des tests

- Tous les scénarios et cas de test seront documentés dans **Jira** ou un tableau similaire  
- Chaque anomalie sera signalée avec : ID test, description, capture d’écran ou vidéo, étapes pour reproduire  
- Statut des tests : **Pass / Fail / Blocked**  

---

## 5️⃣ Remarques

- Tests **fonctionnels uniquement**, réalisés **manuellement**  
- Priorité donnée aux fonctionnalités critiques : création compte, publication d’annonce, recherche, consultation  

---

💡 Ce plan de test est **prêt à être intégré dans un portfolio QA**, avec la possibilité de compléter chaque cas de test par les étapes détaillées dans un document séparé ou Jira.

