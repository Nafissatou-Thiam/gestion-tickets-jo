# 🇸🇳 JO Sénégal — Dakar 2026
## Application Complète de Billetterie Olympique

---

## 📁 Structure du Dossier

```
dakar2026/
├── README.md                    ← Ce fichier
├── index.html                   ← Page d'accueil / Lanceur
│
├── client/
│   └── index.html               ← Application Client (achat billets)
│
├── admin/
│   └── index.html               ← Dashboard Admin (gestion)
│
├── data/
│   └── db.json                  ← Base de données (événements, tickets, users)
│
└── images/                      ← Toutes les images
    ├── jo2026.jpg               (Logo JO Dakar 2026)
    ├── anneaux.jpg              (Anneaux olympiques)
    ├── lutte.jpg                (Lutte sénégalaise Laamb)
    ├── tennis.jpg               (Tennis)
    ├── football.jpg             (Football)
    ├── natation.jpg             (Natation)
    ├── monument.jpg             (Monument Renaissance Africaine)
    ├── senegal_flag.jpg         (Drapeau Sénégal)
    ├── ville.jpg                (Vue de Dakar)
    ├── sport0.jpg               (Athlétisme)
    ├── sport1.jpg               (Sport 1)
    └── sport2.jpg               (Sport 2 / Aviron)
```

---

## 🚀 Comment ouvrir l'application

1. **Ouvrir `index.html`** (à la racine du dossier) dans votre navigateur
2. Ou ouvrir directement :
   - `client/index.html` → Achat de billets (vue client)
   - `admin/index.html` → Tableau de bord administrateur

---

## 🎟️ Application Client (`client/index.html`)

### Fonctionnalités :
- **Authentification** : Connexion / Inscription
- **Catalogue** des épreuves avec filtres par sport
- **Recherche** en temps réel
- **Détail épreuve** : zones, prix, disponibilités
- **Panier** avec drawer latéral
- **Checkout** sécurisé avec récapitulatif
- **Mes Billets** : historique des achats avec références
- **Mon Compte** : profil, statistiques personnelles

### Compte de démonstration :
- Email : `client@jo2026.sn`
- Mot de passe : `••••••` (n'importe quoi)

---

## 🛠️ Dashboard Admin (`admin/index.html`)

### Fonctionnalités :
- **Tableau de bord** : KPIs en temps réel (tickets vendus, revenus, capacité)
- **Gestion des Événements** : création, suppression, filtres par sport
- **Gestion des Tickets** : CRUD complet, changement de statut, recherche
- **Réservations** : suivi des réservations avec statuts
- **Capacité** : tableau avec barres de progression par événement

---

## 🗄️ Base de Données (`data/db.json`)

Contient :
- **8 événements** olympiques avec zones et prix
- **12 tickets** avec clients et statuts
- **6 réservations** 
- **3 utilisateurs** (1 admin + 2 clients)
- **Statistiques** globales

---

## 🎨 Design

- Couleurs du drapeau sénégalais : Vert 🟩 · Jaune 🟨 · Rouge 🟥
- Police : Playfair Display (titres) + Outfit (texte)
- Thème clair pour le client, thème sombre pour l'admin
- Responsive mobile
