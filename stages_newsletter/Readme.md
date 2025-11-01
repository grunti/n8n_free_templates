# Template n8n : Notification Quotidienne des Dernières Offres d'Emploi Ciblées 🛜

**Ce workflow est configuré par défaut pour les stages en finance d’entreprise (M&A, évaluation, services de transaction, 6+ mois).**  
Pour cibler un autre domaine → modifiez simplement le **Google Dork** (dans le nœud *Edit Fields*) et, si besoin, les sites scrapés dans la requête SerpAPI.

---

⚙️ **Fonctionnement :**

- **Collecte** : SerpAPI + Google Dork personnalisé → offres publiées dans les 24h sur LinkedIn, Indeed, Welcome to the Jungle, etc.  
- **Filtrage** : Agent IA Gemini valide la pertinence (« Oui/Non »).  
- **Stockage** : Google Sheets avec dédoublonnage automatique.  
- **Notification** : Envoi d’un e-mail via Outlook.  

> **Note** : L’e-mail généré est fonctionnel mais **basique** (pas de mise en page avancée).  
> Pour un **beau template HTML responsive + dark mode**, passez à la version premium → **+4,99 €** (et soutenez le projet !)  
> 👉 [https://cashroutine.gumroad.com/p/50-off-for-the-template-daily-notification-on-latest-job-offers](https://cashroutine.gumroad.com/p/50-off-for-the-template-daily-notification-on-latest-job-offers)

---

🛠️ **Instructions de Configuration :**

1. Importez le JSON dans n8n.  
2. Ajoutez vos identifiants :  
   - SerpAPI (clé API)  
   - Google Sheets (OAuth2)  
   - Microsoft Outlook (OAuth2)  
3. Modifiez le **Google Dork** si besoin.  
4. Planifiez à 7 h → testez → ajustez le prompt IA.  

🔑 **Identifiants & Nœuds requis :**  
- **Identifiants** : SerpAPI, Google Sheets OAuth2, Microsoft Outlook OAuth2.  
- **Nœuds** : Schedule Trigger, HTTP Request, Google Sheets, AI Agent (Gemini), Microsoft Outlook.

---

🎥 **Tuto complet du template** → [https://youtu.be/dMFFVp0DcII](https://youtu.be/dMFFVp0DcII)  
*(Abonne-toi + 🔔 pour les prochaines automatisations IA !)*

---

### Tu ne veux pas t’embêter avec n8n ?  
**S’abonne à la Newsletter Live** (€9,99/mois – **1 semaine GRATUITE**)  
Zéro config → offres filtrées chaque matin.  
👉 [https://cashroutine.gumroad.com/l/internship-alert](https://cashroutine.gumroad.com/l/internship-alert)

---

🔗 **Liens utiles :**

🧞‍♂️ **20 % de réduction Hostinger** → [https://hostinger.fr/?REFERRALCODE=CASHROUTINE](https://hostinger.fr/?REFERRALCODE=CASHROUTINE)  
✨ **Essaie n8n gratuitement** → [https://n8n.partnerlinks.io/cm1t54p7lwdw](https://n8n.partnerlinks.io/cm1t54p7lwdw)  
💬 **Telegram (aide + newsletter)** → [https://t.me/+pfPxNZdQj_9jYjU0](https://t.me/+pfPxNZdQj_9jYjU0)  
👔 **Call / Agence IA** → [https://agence-alain.fr](https://agence-alain.fr)

---

**Créateur** : Louis Delahaye | n8n.io/creators/louisdl  
YouTube : [@cash-routine](https://www.youtube.com/@cash-routine)

**Prochaines étapes :**  
1. Choisis **Workflow** OU **Newsletter** (ou les deux !)  
2. Reçois tes offres dès demain matin  
3. **Postule en premier, décroche le stage de tes rêves** 💼✨
