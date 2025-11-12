# Politique de Confidentialité / Privacy Policy

Dernière mise à jour / Last updated: 12 Nov 2025

---
## FR – Politique de Confidentialité

### 1. Introduction
L'application **Qadhyat Vendor** ("l'Application") permet aux vendeurs de gérer leurs produits, services, commandes et rapports financiers. Cette politique décrit comment nous collectons, utilisons, stockons et protégeons vos données.

### 2. Données collectées
Nous pouvons collecter ou traiter les catégories de données suivantes lorsque vous utilisez l'Application:
- **Images / Photos (CAMERA)**: prises via votre appareil pour illustrer des produits, documents ou pour scanner des codes (ex: QR).
- **Fichiers exportés**: rapports PDF générés localement (earnings / sales) et enregistrés sur votre appareil.
- **Notifications / Identifiants techniques**: jetons de notifications poussoirs pour délivrer des notifications (Firebase Cloud Messaging).
- **Données d'utilisation**: métadonnées (dates de création de commandes, agrégations pour rapports). 

Nous ne collectons pas intentionnellement des données sensibles (santé, religion, biométrie) par le biais de l'Application.

### 3. Finalités du traitement
- Affichage et gestion du catalogue (produits / services / packages).
- Génération et export de rapports financiers (ventes, revenus).
- Traitement de commandes (statuts, historique, suivi).
- Envoi de notifications transactionnelles (changement de statut, rappels).
- Amélioration technique et débogage (journalisation limitée côté serveur).

### 4. Permission CAMERA
La permission `android.permission.CAMERA` est utilisée uniquement pour:
- Capturer des images de produits/services.
- Scanner des QR codes ou codes-barres (si la fonctionnalité est activée).
Aucune photo n'est publiée automatiquement; l'envoi se fait uniquement lorsque vous confirmez une action (ex: ajout de produit).

### 5. Partage des données
Vos données ne sont **pas vendues** à des tiers. Elles peuvent être partagées uniquement avec:
- Fournisseurs techniques (hébergement, CDN, services push) pour assurer le fonctionnement.
- Autorités légales si la loi l'exige.

### 6. Conservation
Les données opérationnelles (produits, commandes, rapports agrégés) sont conservées aussi longtemps que nécessaire pour fournir le service ou pour répondre à des obligations légales. Les images peuvent être supprimées sur demande ou lors de la suppression d'un produit.

### 7. Sécurité
Nous appliquons des mesures raisonnables: transmission chiffrée (HTTPS/TLS), contrôles d'accès basés sur rôles/permissions, surveillance d'erreurs (ex: Crashlytics). Aucune mesure n'offre une sécurité absolue; veuillez protéger vos identifiants.

### 8. Vos droits
Selon votre juridiction, vous pouvez demander: accès, rectification, suppression, limitation. Pour toute demande: contactez-nous à l'adresse ci-dessous.

### 9. Politique enfants
L'Application est destinée à un usage professionnel / commercial et non aux enfants.

### 10. Services tiers
- Firebase (Auth, Messaging, Crashlytics, Firestore)
- Stockage de fichiers selon l'infrastructure (ex: Object Storage chiffré)
Chacun possède sa propre politique de confidentialité.

### 11. Modifications
Nous pouvons mettre à jour cette politique. La date de révision est indiquée en haut. Les modifications significatives seront notifiées via l'Application ou par e-mail (si disponible).

### 12. Contact
Support / Privacy: qadhyat.tn@gmail.com.

---
## EN – Privacy Policy

### 1. Introduction
The **Qadhyat Vendor** application ("the App") enables vendors to manage products, services, orders, and financial reports. This policy explains how we collect, use, store, and protect your data.

### 2. Data Collected
We may collect or process the following categories:
- **Images / Photos (CAMERA)**: captured to illustrate products or scan codes (e.g., QR).
- **Exported files**: locally generated PDF reports (earnings / sales) saved on your device.
- **Notification tokens**: push tokens (Firebase Cloud Messaging) for transactional notifications.
- **Usage data**: metadata (order timestamps, aggregated financial metrics).

We do **not** intentionally collect sensitive personal data (health, religion, biometric) through the App.

### 3. Purposes
- Display and management of catalog (products / services / packages).
- Generation & export of financial reports (sales, earnings).
- Order processing (statuses, history, tracking).
- Transactional notifications (status changes, reminders).
- Technical improvement & debugging (limited server logging).

### 4. CAMERA Permission
The `android.permission.CAMERA` permission is used only to:
- Capture product/service images.
- Scan QR codes or barcodes (when feature is enabled).
No photo is auto-published; upload occurs only after user confirmation.

### 5. Data Sharing
We do **not sell** your data. Data may be shared only with:
- Technical service providers (hosting, CDN, push services) necessary for functionality.
- Legal authorities if required by law.

### 6. Retention
Operational data (products, orders, aggregate reports) are retained as long as needed to provide the service or meet legal obligations. Images can be deleted upon request or product removal.

### 7. Security
Measures include encrypted transport (HTTPS/TLS), role/permission based access, error monitoring (Crashlytics). No method is 100% secure; protect your credentials.

### 8. Your Rights
Subject to local law you may request: access, correction, deletion, restriction. Contact us at the address below.

### 9. Children
The App targets professional / commercial use, not children.

### 10. Third-Party Services
- Firebase (Auth, Messaging, Crashlytics, Firestore)
- File/object storage (encrypted where applicable)
Each has its own privacy policy.

### 11. Changes
We may update this policy. Revision date is shown at the top. Material changes may be announced via the App or email.

### 12. Contact
Support / Privacy: **support@qadhyat.example** (replace with real email).

---
## Data Safety (Résumé / Summary)
| Catégorie / Category | Collecte / Collected | Partage / Shared | Usage / Purpose |
|----------------------|----------------------|------------------|-----------------|
| Images (CAMERA)      | Oui / Yes            | Non / No         | Product media, scans |
| Notifications token  | Oui / Yes            | Non / No         | Push notifications |
| Orders & reports     | Oui / Yes            | Non / No         | Core functionality |
| Crash logs           | Oui / Yes (aggregated)| Fournisseurs techniques / Technical providers | Diagnostics |

_Aucune vente de données. Pas de publicité ciblée._

---
## Implémentation technique (Annexe / Appendix)
- Stockage persistant côté serveur: identifiants de commande, produits, métriques agrégées.
- Pas de partage vers réseaux sociaux automatique.
- Export PDF: généré en local, peut être conservé sur l'appareil.

---
## Limitations
Cette politique ne couvre pas les sites ou services externes vers lesquels vous pourriez être redirigé.

---
Fin du document.
