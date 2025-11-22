# Backlog – Application de Gestion des Tâches Étudiant (Tâches)

## 1. Authentification et Compte Utilisateur

### Tâche 1 : Création de compte
- Implémenter le formulaire de création de compte.
- Vérifier les champs (email, nom d’utilisateur, mot de passe).
- Ajouter la validation côté serveur.
- Enregistrer l’utilisateur dans la base.
- Afficher un message de confirmation.

### Tâche 2 : Connexion au compte
- Créer interface de connexion.
- Ajouter la connexion via Gmail ou via nom d’utilisateur avec mot de passe.
- Implémenter vérification des identifiants.
- Gérer les sessions utilisateurs.

### Tâche 3 : Déconnexion
- Ajouter bouton de déconnexion.
- Supprimer la session de l’utilisateur.

### Tâche 4 : Changer le mot de passe
- Implémenter page de changement de mot de passe.
- Vérifier ancien mot de passe.
- Mettre à jour le mot de passe dans la BD.

---

## 2. Gestion des Tâches et Révisions

### Tâche 5 : Ajouter une tâche / séance de révision
- Créer formulaire d’ajout.
- Ajouter champs : titre, description, date, matière, priorité.
- Enregistrer la tâche dans la BD.

### Tâche 6 : Modifier une tâche
- Afficher les données existantes.
- Mettre à jour les informations.
- Enregistrer les modifications.

### Tâche 7 : Supprimer une tâche
- Ajouter bouton de suppression.
- Confirmer la suppression.
- Supprimer de la base.

### Tâche 8 : Définir priorité et état
- Ajouter options : basse, moyenne, haute.
- Ajouter états : en cours, terminé.
- Mettre à jour la tâche.

### Tâche 9 : Associer matière à une tâche
- Ajouter liste des matières.
- Lier matière à la tâche.

### Tâche 10 : Rappel avant un cours
- Ajouter système de notifications.
- Définir délai de rappel.
- Envoyer notification.

---

## 3. Emploi du Temps

### Tâche 11 : Ajouter un cours
- Créer formulaire d’ajout de cours.
- Champs : jour, horaire, matière.
- Enregistrer dans la base.

### Tâche 12 : Modifier ou supprimer un cours
- Afficher les cours existants.
- Modifier un cours.
- Supprimer un cours.

### Tâche 13 : Voir l'emploi du temps
- Créer interface d’affichage hebdomadaire.
- Charger les cours depuis la BD.

---

## 4. Vue Globale et Organisation

### Tâche 14 : Voir les tâches du jour
- Filtrer les tâches par date du jour.
- Afficher dans interface.

### Tâche 15 : Voir les tâches à venir
- Filtrer par date future.
- Afficher liste des tâches.

### Tâche 16 : Filtrer les tâches
- Ajouter filtres : matière, priorité, date.
- Implémenter affichage dynamique.

### Tâche 17 : Rechercher une tâche
- Implémenter barre de recherche.
- Rechercher par mots-clés.

---

## 5. Fonctionnalités Potentielles

### Tâche 18 : Assistant intelligent
- Créer module d’analyse des tâches.
- Générer résumés automatiques.
- Ajouter interface de chat.

### Tâche 19 : To-do list d’équipe
- Créer listes partagées.
- Ajouter système d’invitations.
- Synchroniser les tâches.

### Tâche 20 : Attribution des tâches en équipe
- Ajouter option "assigner un membre".
- Notifier les membres assignés.
- Suivre l’avancement des tâches.