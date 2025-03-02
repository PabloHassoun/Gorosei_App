# Gorosei_App
Application de gestion de base de données avec Agents IA

# 🚀 Gorosei_App

Gorosei_App est une application qui permet de gérer une base de données à l’aide d’une équipe d’agents IA spécialisés. Basée sur un système **RAG (Retrieval-Augmented Generation)**, elle offre une gestion intelligente des connaissances et une interface intuitive pour interagir avec les données.

## 📌 Fonctionnalités principales
- **📂 Importation et structuration des données** : Ajout de fichiers (PDF, JSON, CSV).
- **🧠 Agents IA spécialisés** : Chaque agent a un rôle défini (structuration, validation, génération…).
- **🔎 Recherche intelligente** : Posez des questions à votre base de connaissances avec un moteur RAG.
- **⚡ Interface Web moderne** : Application en **Next.js** pour une navigation fluide.
- **🔐 Sécurisation des données** : Chiffrement, authentification JWT et monitoring.

## 🛠️ Technologies utilisées
- **Backend** : Python, Flask, PostgreSQL, ChromaDB, CrewAI/LangChain
- **Frontend** : Next.js, React, Tailwind CSS
- **Infrastructure** : Docker, Docker Compose, WebSockets
- **IA** : LLMs open-source (Mistral, LLaMA), embeddings via Sentence Transformers

## 📥 Installation et exécution
### **Prérequis**
- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)
- Python 3.9+ (si utilisation sans Docker)
- Node.js 18+ (pour le frontend)

### **Étapes d’installation**
1. **Clonez le projet :**
   ```bash
   git clone https://github.com/PabloHassoun/Gorosei_App.git
   cd Gorosei_app
