# 📦 [TPL-001] OptiStock Core
**Automated Stock Monitoring & Alert System**

### 🎯 Overview
This workflow prevents production downtime by calculating real-time available stock and sending instant email notifications when inventory hits a critical threshold.

### ⚙️ Logic breakdown
1.  **Input**: Receives `stockOnHand` and `stockReserved`.
2.  **Calculation**: Computes `stockDisponible = stockOnHand - stockReserved` via JavaScript.
3.  **Condition**: Triggers an alert if `stockDisponible` is low.
4.  **Action**: Sends a professional email alert.

### 🚀 How to use
1.  Import the `TPL-001.json` file into your n8n instance.
2.  Configure your Gmail/SMTP credentials in the "Send an Email" node.
3.  Adjust the threshold in the "If" node to match your industrial needs.
