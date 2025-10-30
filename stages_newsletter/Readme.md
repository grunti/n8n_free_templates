## 🛜 Notification Quotidienne des Dernières Offres d'Emploi Ciblées 🛜

🌟 **Aperçu** : Ne manquez plus jamais une offre d'emploi ! Ce workflow n8n automatise la collecte quotidienne d'offres d'emploi sur LinkedIn, Indeed, Welcome to the Jungle et d'autres plateformes, en utilisant Google Dorks et SerpAPI. Il filtre les offres avec un agent IA Gemini, les stocke dans Google Sheets et envoie une newsletter HTML élégante directement dans votre boîte mail ou à vos abonnés — le tout gérable depuis votre téléphone !

**💼 Cas d'Usage** :
- Étudiants en quête de stages en fusion-acquisition (M&A), évaluation ou services de transaction (6+ mois).
- Personnes en reconversion professionnelle souhaitant des alertes d'offres d'emploi automatisées et personnalisées.
- Créateurs de contenu développant une newsletter d'offres d'emploi pour monétiser leur audience.

**⚙️ Fonctionnement** :
1. **Collecte** : Utilise SerpAPI avec un Google Dork personnalisé pour récupérer quotidiennement les dernières offres d'emploi sur les principales plateformes.
2. **Filtrage** : Un agent IA Gemini valide les offres pour s'assurer qu'elles correspondent aux critères de la finance d'entreprise.
3. **Stockage** : Enregistre les nouvelles offres dans Google Sheets en marquant les doublons pour éviter le spam.
4. **Notification** : Génère une notification par e-mail/newsletter et l'envoie via Outlook.

**🛠️ Instructions de Configuration** :
- Importez le workflow JSON dans n8n.
- Ajoutez les identifiants : SerpAPI (clé API), Google Sheets (OAuth2), Microsoft Outlook (OAuth2).
- Personnalisez le Google Dork dans le nœud "Edit Fields" pour des critères d'emploi spécifiques.
- Planifiez l'exécution quotidienne à 7h. Testez et ajustez la requête IA pour plus de précision.

**🔑 Identifiants et Nœuds Requis** :
- **Identifiants** : SerpAPI, Google Sheets OAuth2, Microsoft Outlook OAuth2.
- **Nœuds** : Déclencheur de planification, Requête HTTP, Google Sheets, Agent IA (Gemini), Microsoft Outlook.

🔗 **Créateur** : Louis Delahaye | [n8n.io/creators/louisdl](https://n8n.io/creators/louisdl/)
🎥 YouTube : [@cash-routine](https://www.youtube.com/@cash-routine)
Mon Agence IA : [agence-alain.fr](https://agence-alain.fr)
