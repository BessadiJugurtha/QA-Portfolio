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

**Scénario U1 : Création d’un compte utilisateur**
- Cas de test U1.1 : Création d’un compte particulier avec tous les champs valides  
- Cas de test U1.2 : Création d’un compte professionnel avec tous les champs valides  

**Scénario U2 : Connexion utilisateur**
- Cas de test U2.1 : Connexion avec identifiants valides  
- Cas de test U2.2 : Connexion avec mot de passe incorrect  
- Cas de test U2.3 : Connexion avec email inexistant  

**Scénario U3 : Gestion du profil**
- Cas de test U3.1 : Modification des informations personnelles  
- Cas de test U3.2 : Suppression du compte  

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

