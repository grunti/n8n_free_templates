# Template n8n : Notification Quotidienne des Dernières Offres d'Emploi Ciblées 🛜

**Ce workflow est configuré par défaut pour les stages en finance d’entreprise (M&A, évaluation, services de transaction, 6+ mois).**  
Pour cibler un autre domaine → modifiez simplement le **Google Dork** (dans le nœud *Edit Fields*) et, si besoin, les sites scrapés dans la requête SerpAPI.

---

## 🚀 **Pas envie de t’embêter avec n8n ? Choisis ton niveau :**

| Option | Prix | Ce que tu reçois |
| --- | --- | --- |
| **Template adapté Corporate Finance (gratuit)** | 0 € | Workflow n8n fonctionnel (mail simple) – **à télécharger directement via le Gumroad du produit principal** |
| **Template adapté Corporate Finance + beau mail HTML** | **~~9.99€~~ 4,99 €** (promo valide 10 jours) | Newsletter pro, beau format responsive et adapté au dark mode (pour me soutenir 🙂) |
| **Newsletter live « Stages Corporate Finance »** | 9,99 €/mois (1 sem gratuite) | Offres filtrées chaque matin, zéro config |
| **Newsletter 100 % sur-mesure** | 39,99 €/mois (1 sem gratuite) | Critères ultra-précis (ville, durée, entreprise…) – je la développe pour toi |

👉 **Achat & liens :**  
- Template gratuit / premium → via le Gumroad du produit principal ou [ici pour le beau mail](https://cashroutine.gumroad.com/p/50-off-for-the-template-daily-notification-on-latest-job-offers)  
- Newsletter live → [https://cashroutine.gumroad.com/l/internship-alert](https://cashroutine.gumroad.com/l/internship-alert)  
- Sur-mesure → contacte-moi sur Telegram ou cashflows.routine@gmail.com

---

⚙️ **Fonctionnement :**

- **Collecte** : SerpAPI + Google Dork personnalisé → offres publiées dans les 24h sur LinkedIn, Indeed, Welcome to the Jungle, etc.  
- **Filtrage** : Agent IA Gemini valide la pertinence (« Oui/Non »).  
- **Stockage** : Google Sheets avec dédoublonnage automatique.  
- **Notification** : Envoi d’un e-mail via Outlook.  

> **Note** : L’e-mail du template gratuit est fonctionnel mais **basique**. La version **+4,99 €** inclut le **beau template HTML responsive + dark mode**.

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

🔗 **Liens utiles :**

🧞‍♂️ **20 % de réduction Hostinger** pour héberger n8n → [https://hostinger.fr/?REFERRALCODE=CASHROUTINE](https://hostinger.fr/?REFERRALCODE=CASHROUTINE)  
💻 **Apprends comment héberger n8n gratuitement** → [https://youtu.be/pFLgxJZv4gA](https://youtu.be/pFLgxJZv4gA)  
✨ **Essaie n8n gratuitement** → [https://n8n.partnerlinks.io/cm1t54p7lwdw](https://n8n.partnerlinks.io/cm1t54p7lwdw)  
💬 **Telegram (aide + newsletter)** → [https://t.me/+pfPxNZdQj_9jYjU0](https://t.me/+pfPxNZdQj_9jYjU0)  
👔 **Call / Agence IA** → [https://agence-alain.fr](https://agence-alain.fr)

---

**Créateur** : Louis Delahaye | n8n.io/creators/louisdl  
YouTube : [@cash-routine](https://www.youtube.com/@cash-routine)

**Prochaines étapes :**  
1. Choisis **Workflow**, **Newsletter standard** ou **sur-mesure**  
2. Reçois tes offres dès demain matin  
3. **Postule en premier, décroche le stage de tes rêves** 💼✨
