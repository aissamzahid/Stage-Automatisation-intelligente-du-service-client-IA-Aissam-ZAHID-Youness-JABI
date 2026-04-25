Bonjour Monsieur Neuman, Veuillez trouver ci-dessous le rapport de ma semaine de stage :

📅 Semaine du 13/04 au 17/04

Objectif du projet: Le projet vise à développer un système intelligent capable d’automatiser et d’améliorer le service client d’une entreprise, en offrant des réponses rapides, fiables et sécurisées aux utilisateurs, tout en réduisant la charge du support humain.

Description générale du système Le système sera basé sur une architecture multi-agents, où chaque agent possède un rôle spécifique :

Agent Conversationnel (LLM) Dialogue avec les clients Comprend les questions en langage naturel Produit des réponses claires et professionnelles
Agent de Classification Identifie le type de demande (réclamation, information, support, devis…) Oriente la requête vers le bon agent
Agent de Recherche (RAG) Accède à la base de connaissances (FAQ, documents internes, policies) Fournit des réponses fiables basées sur des données réelles
Agent de Décision Décide si la requête peut être traitée automatiquement Ou doit être escaladée vers un agent humain
Agent d’Apprentissage Analyse les feedbacks utilisateurs Améliore progressivement les performances via fine-tuning et optimisation des prompts
Agents de Sécurité et de Contrôle Protection des données sensibles des clients Respect des politiques de l’entreprise Détection des demandes suspectes ou malveillantes Prévention des hallucinations (éviter les réponses inventées) Contrôle du périmètre des conversations et arrêt si hors sujet
Technologies envisagées Python (FastAPI / Flask) LLM (Open Source ou API) RAG (FAISS / ChromaDB) Fine-tuning du modèle sur des données de service client Base de données MySQL / PostgreSQL 🔄 EN COURS Nous sommes en train de chercher des datasets appropie pour le projet.
