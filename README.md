# 🤖 Chatbot Seatech – Un assistant intelligent pour l’information académique  

## 📌 Présentation du projet  
Ce projet vise à développer un **chatbot intelligent** pour **Seatech**, permettant aux étudiants et candidats d’accéder rapidement aux informations académiques et administratives.  

### 🔹 Pourquoi un chatbot ?  
- 📌 **Simplifier la recherche d’informations** sur le site.  
- ⚡ **Automatiser les réponses aux questions fréquentes**.  
- 🎯 **Améliorer l’expérience utilisateur** avec une assistance interactive.  

---

## 🏗 Architecture et fonctionnement  

Le chatbot repose sur l’approche **RAG (Retrieval-Augmented Generation)** pour récupérer et générer des réponses pertinentes.  

### 🔹 **Pipeline RAG : Étapes clés**  
1️⃣ **Collecte des données** : Extraction des contenus du site Seatech avec **Firecrawl** et nettoyage manuel.  
2️⃣ **Chunking** : Découpage des textes en fragments exploitables pour une meilleure structuration des informations.  
3️⃣ **Embeddings** : Conversion des fragments en **vecteurs numériques** avec **ChromaDB**.  
4️⃣ **Stockage** : Indexation des embeddings dans une **base vectorielle**.  
5️⃣ **Recherche et récupération** : Identification des documents les plus pertinents en fonction des requêtes utilisateur.  
6️⃣ **Génération de réponses** : Utilisation de **LangChain** et du **LLM Groq (Llama3-70B)** pour formuler une réponse adaptée.  

---

## ⚙️ Technologies utilisées  
✅ **ChromaDB** → Stockage et recherche vectorielle des documents.  
✅ **LangChain** → Orchestration entre la base de données et le modèle LLM.  
✅ **Groq (Llama3-70B)** → Génération de réponses optimisées.  
✅ **Streamlit** → Interface utilisateur interactive et facile à utiliser.  
✅ **GitHub** → Gestion du code et intégration avec **Streamlit Share** pour le déploiement.  

---

## 🚀 Déploiement et accès  

Nous avons déployé le chatbot avec **Streamlit Share**, qui permet un accès instantané via une **URL publique**.  

### 🔹 **Processus de déploiement :**  
1️⃣ **Hébergement du code sur GitHub**.  
2️⃣ **Connexion à Streamlit Cloud**.  
3️⃣ **Synchronisation automatique** avec GitHub à chaque mise à jour.  

🔗 **Lien du chatbot en ligne** : 👉 [Ajoute l’URL ici]  

---

## 🛠 Installation et exécution locale  

Si tu veux exécuter le chatbot en **local**, voici les étapes :  

### 1️⃣ **Cloner le projet**  
```bash
git clone https://github.com/ton-repo/chatbot-seatech.git
cd chatbot-seatech
