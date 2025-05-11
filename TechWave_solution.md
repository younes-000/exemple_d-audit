# 📄 Case Study — TechWave Solutions

## 🏢 Fictional Company Overview

**TechWave Solutions** est une entreprise canadienne de taille moyenne spécialisée dans les solutions **cloud** et **SaaS** pour les **PME**. Elle dispose de deux sites :
- Siège social à **Montréal**
- Bureau secondaire à **Vancouver**

Grâce à sa croissance rapide, l'entreprise a élargi son portefeuille client à travers le **Canada** et **l'Europe**. Face à cette expansion et aux exigences réglementaires, la direction informatique initie un **audit interne** pour :
- Renforcer la **sécurité informatique**
- Assurer la **conformité réglementaire**

La responsable IT adopte le **Cadre de cybersécurité du NIST (NIST CSF)** pour mener cet audit.

---

## 🔍 Scenario

### 📌 Scope

L'audit couvre :
- L'ensemble du programme de sécurité
- Les **actifs physiques et numériques**
- Les **processus internes**
- Les **politiques de conformité**

### 🎯 Goals

- Évaluer les actifs existants
- Compléter une **checklist de conformité**
- Identifier les **améliorations nécessaires**

---

## 💻 Current Assets

- Infrastructure cloud propriétaire
- Équipements physiques (serveurs, routeurs, switches)
- Postes de travail (ordinateurs portables, smartphones)
- Applications SaaS internes (gestion clients, facturation, support)
- Réseaux internes
- Accès Internet haut débit
- Base de données client et données sensibles
- Services de stockage cloud

---

## ⚠️ Risk Assessment

### 📝 Risk Description

TechWave Solutions gère mal les **droits d'accès aux données sensibles** et manque de procédures de sécurité formalisées, ce qui expose l'entreprise à :
- Des violations de données
- Une non-conformité aux normes internationales (ex. **RGPD**)

### ✅ Control Best Practices

Selon la fonction **"Identifier"** du **NIST CSF** :
- Identification exhaustive des actifs
- Classification par **sensibilité**
- Évaluation claire de l'**impact potentiel**

### 📉 Risk Score

> **9 / 10** — Situation critique nécessitant une action **urgente**

### 💬 Additional Comments

- Perte de données client = **impact élevé**
- Risque accru de **sanctions financières** (RGPD, ISO 27001)

---

## 📋 Controls Assessment Checklist

| Control              | Status | Explanation                                                  |
|----------------------|--------|--------------------------------------------------------------|
| Least Privilege      | ❌     | Trop d'employés ont un accès aux données sensibles          |
| Disaster Recovery Plan | ❌   | Aucun plan documenté en cas de catastrophe informatique     |
| Firewall             | ✅     | Configuré et supervisé par l'équipe IT                      |
| Password Policies    | ❓     | Politiques existantes, mais exigences insuffisantes         |
| Antivirus            | ✅     | Solution antivirus active et à jour                         |
| Backups              | ❌     | Pas de stratégie claire de sauvegarde régulière            |
| Encryption           | ❌     | Données sensibles non systématiquement chiffrées           |
| IDS                  | ❌     | Absence de systèmes de détection d’intrusion efficace      |
| Physical Security    | ✅     | Accès sécurisé aux locaux avec badge                        |
| CCTV                 | ✅     | Surveillance vidéo fonctionnelle sur tous les sites        |
| Fire Detection       | ✅     | Détection incendie installée (plan d’évacuation à clarifier) |

---

## ✅ Compliance Checklist

### 📜 GDPR

| Best Practice                          | Status | Explanation                                |
|----------------------------------------|--------|--------------------------------------------|
| EU customer data is securely managed   | ❌     | Non-respect complet des exigences RGPD     |
| Privacy policies are clearly communicated | ✅  | Politiques disponibles sur le site web     |

### 🛡 ISO 27001

| Best Practice                        | Status | Explanation                                      |
|--------------------------------------|--------|--------------------------------------------------|
| Information security policy documented | ❌   | Absence de documentation formelle               |
| Regular risk assessments conducted    | ❓     | Évaluations réalisées de manière informelle     |
| Asset inventory regularly updated     | ❌     | Inventaire non mis à jour régulièrement         |

---

## 🛠 Recommendations

Pour renforcer sa posture de sécurité et assurer la conformité, TechWave Solutions doit :

- ✅ Appliquer le **principe du moindre privilège**
- ✅ Mettre en place un **plan de reprise après sinistre** testé régulièrement
- ✅ Renforcer et documenter les **politiques de mot de passe et d'accès**
- ✅ Implémenter un **chiffrement systématique** des données sensibles
- ✅ Intégrer des **systèmes efficaces de détection d'intrusion**
- ✅ Formaliser une **politique de sécurité conforme** (RGPD, ISO 27001)
- ✅ Mettre à jour régulièrement l’**inventaire des actifs**

