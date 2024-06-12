# GestionConfTogo
On a déjà mis en place la partie utilisateur avec Blazor Identity.NET Core 8 et MySQL.

Voici une proposition de structure pour notre application :

Pages

Accueil : Page d'accueil de l'application qui affichera les conférences à venir et les dernières actualités.
Conférences : Page qui affichera la liste des conférences avec leurs détails (nom, sigle, thème, calendrier).
Soumission d'article : Page qui permettra aux auteurs de soumettre un article avec un titre, une brève description et un fichier PDF.
Gestion des articles : Page qui permettra aux auteurs de consulter le statut de leurs articles soumis et les justificatifs des décisions rendues.
Affectation des relecteurs : Page qui permettra aux co-présidents d'affecter des relecteurs pour chaque article.
Évaluation des articles : Page qui permettra aux relecteurs de renseigner les différents critères d'évaluation.
Notification des résultats : Page qui affichera les résultats des évaluations des articles.
Réservation de place : Page qui permettra aux participants de réserver leur place pour une conférence donnée.
Profil : Page qui affichera les informations de l'utilisateur connecté (auteur, participant, co-président, etc.).
Rôles

Administrateur : peut gérer les conférences, les articles, les relecteurs, les évaluations, etc.
Co-président : peut affecter des relecteurs pour chaque article et gérer les évaluations.
Auteur : peut soumettre des articles et consulter le statut de ses articles soumis.
Relecteur : peut évaluer les articles assignés.
Participant : peut réserver sa place pour une conférence donnée.
Fonctionnalités

Gestion des conférences : création, modification, suppression de conférences.
Gestion des articles : soumission, évaluation, notification des résultats.
Gestion des relecteurs : affectation, évaluation des articles.
Gestion des réservations : réservation de place pour une conférence donnée.
Gestion des utilisateurs : gestion des rôles, des autorisations, etc.
Technologies

Blazor Server 2..NET Core 8
MySQL
Blazor Identity
Architecture

Créez un projet Blazor Server avec.NET Core 8.
Configurez Blazor Identity pour gérer les utilisateurs et les rôles.
Créez les pages et les composants nécessaires pour chaque fonctionnalité.
Utilisez MySQL pour stocker les données de l'application.
Mettez en place les autorisations et les contrôles d'accès pour chaque fonctionnalité en fonction des rôles.
