# Agent Conversationnel Intelligent pour Agence Touristique (n8n & Gemini)

Ce projet présente un agent conversationnel intelligent automatisé via n8n, conçu pour gérer les demandes de réservation d'une agence de voyages et d'activités touristiques au Maroc (Génération Prospect).

## Fonctionnalités principales
- IA Conversationnelle : Utilisation de Google Gemini pour interagir naturellement avec les clients et comprendre leurs besoins.
- Base de Connaissance Documentaire : Récupération dynamique des informations sur les activités et les prix via un stockage vectoriel (Vector Store) alimenté par un document PDF.
- Gestion des Prospects (CRM) : Enregistrement automatique des coordonnées des clients dans Google Sheets (Append row).
- Planification de Rendez-vous : Création automatique d'événements de réservation dans Google Calendar.
- Confirmation par E-mail : Envoi d'un récapitulatif personnalisé au client via Gmail.

## Stack Technique
- Orchestration : n8n (Workflow d'IA et d'automatisation)
- Modèle LLM & Embeddings : Google Gemini
- Stockage & Outils : Google Workspace (Drive, Sheets, Calendar, Gmail)
- Format d'export : JSON (disponible dans ce dépôt)
