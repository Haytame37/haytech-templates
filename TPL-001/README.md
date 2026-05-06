# 📦 TPL-001 : 
**Système de Monitoring de Stock Industriel intelligent pour n8n.**

## 🎯 Description
Ce template permet de surveiller en temps réel l'écart entre le stock physique et les réservations, déclenchant une alerte mail immédiate en cas de franchissement de seuil critique.

## 🛠️ Configuration
1. **Importation** : Glissez le fichier `TPL-001.json` dans votre interface n8n.
2. **Identifiants** : Connectez votre compte SMTP ou Gmail dans le nœud "Notification Alerte Stock".
3. **Seuils** : Ajustez la variable `lowStockThreshold` dans le nœud "Vérification Seuil Critique" (par défaut à 10).

## 🚀 Fonctionnalités Avancées
* **Calcul Automatisé** : Logique JavaScript optimisée pour la précision des données.
* **Gestion des Erreurs** : Architecture compatible avec le `HAYTECH-ERROR-HANDLER` pour une surveillance 24h/24.
