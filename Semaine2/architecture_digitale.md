# ⚙️ Architecture Digitale & Flux Logistique (Semaine 2)

Pour maximiser l'impact de nos chambres froides à **Broukou**, nous avons conçu un écosystème numérique complet qui relie la conservation physique à la vente réelle.

### 🗺️ Conception du Parcours (Whimsical)
Nous avons utilisé **Whimsical** pour modéliser le trajet logistique du produit :
1. **Récolte** par l'agriculteur à Broukou.
2. **Dépôt** et enregistrement dans la chambre froide AGRICold-TG.
3. **Mise en ligne** automatique du stock.
4. **Achat/Mise en relation** avec les clients de la région de la Kara.

### 📱 Interface Utilisateur (Readdy)
Développement de la plateforme **Readdy** :
- Interface simplifiée pour les agriculteurs.
- Catalogue de produits frais disponibles en temps réel pour les acheteurs (étudiants, commerçants).
- Système de mise en relation directe pour réduire les intermédiaires.

### 🗄️ Gestion des Données (Airtable & Make)
Le "cerveau" de notre solution repose sur l'interconnexion No-Code :
- **Airtable** : Notre base de données centrale (Inventaire des stocks, base de données producteurs, suivi des températures).
- **Make** : Le moteur d'automatisation. Il assure le flux d'informations en temps réel entre l'application Readdy et notre base Airtable sans intervention manuelle.

> **Note technique** : Cette stack a été choisie pour sa rapidité de déploiement et sa facilité de maintenance en milieu rural.
