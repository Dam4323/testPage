---
title: "Mon Portfolio Interactif"
description: "Portfolio de Julie Martin - BTS SIO SISR"
author: "Julie Martin"
---

<!-- Intégration des bibliothèques CSS -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"/>

<style>
    body {
        padding-top: 4.5rem;
    }
    .section {
        padding: 60px 0;
    }
    .navbar-brand {
        font-weight: bold;
    }
    .footer {
        background-color: #f8f9fa;
        padding: 20px 0;
        text-align: center;
    }
</style>

# Mon Portfolio Interactif

Ce portfolio est à la fois un support pour l'examen E4 et un outil pour valoriser vos compétences auprès des employeurs. Il contient vos projets, vos expériences professionnelles et votre veille technologique.

---

## Navigation

<nav class="navbar navbar-expand-md navbar-dark bg-dark fixed-top">
    <div class="container">
        <a class="navbar-brand" href="#">Portfolio de Julie Martin</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" 
            aria-controls="navbarNav" aria-expanded="false" aria-label="Basculer la navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
            <ul class="navbar-nav">
                <li class="nav-item">
                    <a class="nav-link active" href="#presentation-personnelle">Présentation</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#presentation-du-bts">Le BTS</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#projets-realises">Projets</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#stages-effectues">Stages</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#veille-technologique">Veille</a>
                </li>
            </ul>
        </div>
    </div>
</nav>

---

## Présentation personnelle {#presentation-personnelle}

<div class="container animate__animated animate__fadeIn">
    <h2>Présentation Personnelle</h2>
    <p>
        Bonjour ! Je m'appelle <strong>Julie Martin</strong> et je suis étudiante en <strong>BTS SIO</strong>, option <strong>SISR</strong>.
        Passionnée par les technologies de l'information, je me spécialise dans l'administration des réseaux, des systèmes et la sécurité informatique.
    </p>
    <ul>
        <li>🎓 <strong>Formation :</strong> BTS SIO (Services Informatiques aux Organisations), option SISR.</li>
        <li>💻 <strong>Spécialisation :</strong> Administration réseaux, systèmes et sécurité.</li>
        <li>🌱 <strong>Compétences :</strong> Développement, déploiement et méthodologie de projets.</li>
    </ul>
</div>

---

## Présentation du BTS {#presentation-du-bts}

<div class="container animate__animated animate__slideInLeft">
    <h2>Présentation du BTS SIO</h2>
    <p>
        Le <strong>BTS SIO (Services Informatiques aux Organisations)</strong> est une formation en deux ans qui permet de développer des compétences dans les domaines suivants :
    </p>
    <ul>
        <li>Gestion du patrimoine informatique.</li>
        <li>Réponse aux incidents et demandes d’assistance.</li>
        <li>Développement et valorisation de la présence en ligne.</li>
        <li>Travail en mode projet et accompagnement des utilisateurs.</li>
    </ul>
    <p><strong>Option SISR :</strong> Administration des réseaux et systèmes.</p>
</div>

---

## Projets réalisés {#projets-realises}

<div class="container animate__animated animate__zoomIn">
    ### Projet 1 : Gestionnaire de Tâches

    - **Description** : Développement d’une application web pour la gestion des tâches quotidiennes, permettant aux utilisateurs de créer, modifier et suivre l’avancement de leurs tâches.
    - **Technologies utilisées** : JavaScript, React, Node.js, MongoDB.
    - **Compétences acquises** :
        - Gestion du patrimoine informatique.
        - Mise en œuvre de référentiels et normes.
        - Développement full-stack.
    - **Lien** : [Voir le projet](https://github.com/juliemartin/gestionnaire-taches)

    ### Projet 2 : Plateforme de E-learning

    - **Description** : Création d’une plateforme de formation en ligne offrant des cours interactifs, des quiz et un suivi des progrès des apprenants.
    - **Technologies utilisées** : Python, Django, PostgreSQL, Bootstrap.
    - **Compétences acquises** :
        - Déploiement d’un service web.
        - Réalisation de tests d’intégration.
        - Gestion de bases de données relationnelles.
    - **Lien** : [Voir le projet](https://github.com/juliemartin/e-learning-platform)
</div>

---

## Stages effectués {#stages-effectues}

<div class="container animate__animated animate__bounceIn">
    ### Stage 1 : TechSolutions

    - **Durée** : Juin 2023 - Août 2023
    - **Mission principale** : Mise en place d’un système de sauvegarde automatisé pour les serveurs de l’entreprise.
    - **Compétences développées** :
        - Gestion des sauvegardes et restaurations.
        - Vérification des conditions de continuité de service.
        - Automatisation des tâches administratives.

    ### Stage 2 : NetSecure

    - **Durée** : Janvier 2024 - Mars 2024
    - **Mission principale** : Participation au déploiement d’une infrastructure réseau sécurisée pour un nouveau client.
    - **Compétences développées** :
        - Traitement des demandes relatives aux services réseau.
        - Mise en œuvre d’outils de suivi et de diagnostic réseau.
        - Configuration et sécurisation des équipements réseau.
</div>

---

## Veille technologique {#veille-technologique}

<div class="container animate__animated animate__fadeInUp">
    ### Thème : Sécurité des Réseaux 5G

    - **Description** : Analyse des tendances technologiques dans le domaine de la sécurité des réseaux 5G, en mettant l’accent sur les nouvelles menaces et les solutions de protection innovantes.
    - **Méthodologie** :
        - **Outils utilisés** : Flux RSS, alertes Google, agrégateurs de contenu.
        - **Sources principales** : Blogs spécialisés, articles scientifiques, rapports de sécurité.
    - **Résultats** : Identification des principales vulnérabilités des réseaux 5G et des meilleures pratiques pour les atténuer, notamment l’utilisation de l’intelligence artificielle pour la détection des intrusions.
</div>

---

## Hébergement et Évolution

<div class="container animate__animated animate__fadeIn">
    - **Hébergement personnel** : Déployé sur [GitHub Pages](https://pages.github.com).
    - Contenu mis à jour régulièrement en fonction des projets réalisés et des stages.
    - Validation régulière par un enseignant pour garantir la conformité avec les attentes de l’examen E4.
</div>

---

## Effets visuels et styles

Pour activer les animations, la bibliothèque [Animate.css](https://animate.style/) est intégrée via le lien dans l'en-tête. De plus, **Bootstrap** est utilisé pour une mise en page responsive et esthétique. Les classes d'animation comme `animate__fadeIn`, `animate__slideInLeft` ou `animate__bounceIn` sont ajoutées aux conteneurs pour rendre l'expérience utilisateur plus engageante.

---

## Footer

<div class="footer">
    © 2024 Julie Martin. Tous droits réservés.
    <br>
    <a href="https://github.com/juliemartin" target="_blank">GitHub</a> |
    <a href="https://linkedin.com/in/juliemartin" target="_blank">LinkedIn</a>
</div>

<!-- Intégration des scripts Bootstrap -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
