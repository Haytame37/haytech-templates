# 📨 TPL-001 : HayTech Support Form
**Système de capture de tickets de support client via n8n.**

## 🎯 Description
Ce template génère un formulaire natif n8n ("Support HayTech") permettant à vos utilisateurs de poser leurs questions et vous transmet instantanément les requêtes par email.

## 🛠️ Configuration
1. **Importation** : Glissez le fichier `TPL-001.json` dans n8n.
2. **Formulaire** : Activez le nœud "On form submission" pour générer l'URL de votre formulaire.
3. **Email** : Configurez vos identifiants SMTP dans le nœud "Send an Email" et ajustez l'adresse de réception (`toEmail`).