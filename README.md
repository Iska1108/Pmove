# 🚌 PMove – Solution d’assistance pour personnes à mobilité réduite

PMove est une application web et mobile permettant de gérer en temps réel l'assistance aux personnes à mobilité réduite dans les transports publics. Ce projet complet repose sur une architecture microservices répartie en plusieurs composants.

## 🎯 Objectif

Faciliter la gestion des demandes d’accompagnement en temps réel, depuis la demande client jusqu’à la prise en charge par un agent.

---

## 🧩 Architecture du projet

| Composant       | Description                                               | Lien GitHub |
|-----------------|-----------------------------------------------------------|-------------|
| 📱 ClientMobile | Application mobile React Native pour les agents | [ClientMobile](https://github.com/PMRSAE5/ClientMobile) |
| 💻 ClientWeb    | Interface web React pour les clients utilisateurs         | [ClientWeb](https://github.com/PMRSAE5/Client) |
| ⚙️ API          | Backend central (Node / Express / Mongo)                  | [API](https://github.com/PMRSAE5/API) |
| 📄 PageQRCode   | Génération de QR codes pour accéder aux demandes          | [PageQRCode](https://github.com/PMRSAE5/PageQRCode) |

---

## 🛠️ Stack Technique

- **Frontend** : React / React Native / Tailwind / TypeScript
- **Backend** : Node.js / Express / MongoDB / Redis
- **CI/CD** : GitHub Actions
- **Autres** : Docker, Neo4j, Firebase

---

## 🖼️ Captures d'écran (à ajouter)

> Tu peux ici ajouter quelques visuels clés de l’app mobile, dashboard web, etc.

---

## ✨ Fonctionnalités principales

- 📍 Géolocalisation des agents disponibles
- 📲 Gestion des demandes clients via QR code ou formulaire
- 🔄 Communication en temps réel
- 🔔 Notifications push
- ⚙️ Architecture scalable avec base NoSQL

---

## 👨‍💻 Auteur

Kaïs Dilmi  
➡️ [LinkedIn](https://www.linkedin.com/in/kais-dilmi/)  
📫 kaisdilmi2003@gmail.com

---

> Ce projet est un démonstrateur complet d’architecture distribuée mobile + web.  
> Idéal pour cas d’usage dans la mobilité, la logistique ou le service à la personne.
