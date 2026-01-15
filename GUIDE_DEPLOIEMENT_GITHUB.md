# GUIDE DÉPLOIEMENT GITHUB PAGES
## Cours IFCA/PAC - Mise en ligne

**Date :** 15 janvier 2026  
**Fichier à déployer :** Cours_IFCA_PAC_ENRICHI.html  
**URL cible :** https://votre-compte.github.io/cours-ifca-pac/

---

## 🚀 **MÉTHODE RAPIDE (5 minutes)**

### Étape 1 : Créer le dépôt GitHub

1. **Aller sur GitHub** : https://github.com/new
2. **Remplir le formulaire :**
   - Repository name : `cours-ifca-pac`
   - Description : `Formation Prévention des risques professionnels - IFCA/PAC - GRETA Var`
   - Public (cocher)
   - ✅ Add a README file
3. **Cliquer sur "Create repository"**

---

### Étape 2 : Uploader le fichier

1. **Dans votre dépôt** → Cliquer sur "Add file" → "Upload files"
2. **Glisser-déposer** le fichier `Cours_IFCA_PAC_ENRICHI.html`
3. **Renommer en** `index.html` (important pour GitHub Pages)
4. **Commit message :** "Ajout cours IFCA/PAC complet"
5. **Cliquer sur "Commit changes"**

---

### Étape 3 : Activer GitHub Pages

1. **Aller dans "Settings"** (onglet en haut du dépôt)
2. **Menu gauche** → Cliquer sur "Pages"
3. **Source** → Sélectionner "Deploy from a branch"
4. **Branch** → Sélectionner "main" + "/" (root)
5. **Cliquer sur "Save"**

**⏱️ Attendre 2-3 minutes** (déploiement en cours)

---

### Étape 4 : Accéder au cours en ligne

**URL :** `https://votre-compte-github.github.io/cours-ifca-pac/`

Exemple : `https://greta-var.github.io/cours-ifca-pac/`

✅ **Le cours est maintenant accessible en ligne !**

---

## 📦 **STRUCTURE RECOMMANDÉE (Optionnelle)**

Si vous voulez une meilleure organisation :

```
cours-ifca-pac/
├── index.html              ← Cours principal (renommer Cours_IFCA_PAC_ENRICHI.html)
├── README.md               ← Description du cours
├── docs/                   ← Documentation (optionnel)
│   ├── AUDIT_CONFORMITE_REGLEMENTAIRE.md
│   ├── ENRICHISSEMENTS_ANNEXES.md
│   └── VALIDATION_BOUTONS_COMPLET.md
└── assets/                 ← Ressources (si besoin futur)
    ├── images/
    └── pdf/
```

**Pour créer cette structure :**
1. Créer dossiers "docs" et "assets" dans GitHub
2. Uploader les fichiers markdown dans "docs"
3. Le fichier `index.html` reste à la racine

---

## 🔒 **OPTION : DÉPÔT PRIVÉ (Formation interne)**

Si vous voulez limiter l'accès :

### Méthode 1 : Dépôt privé GitHub (gratuit)
1. Lors de la création → Cocher "Private"
2. Activer GitHub Pages quand même (fonctionne en privé)
3. **Limites :** 
   - URL reste publique si trouvée
   - Pas de protection par mot de passe natif

### Méthode 2 : Protection par mot de passe (externe)
**Utiliser Netlify (gratuit) :**
1. Créer compte sur https://www.netlify.com/
2. "New site from Git" → Connecter GitHub
3. Sélectionner le dépôt `cours-ifca-pac`
4. Deploy settings : 
   - Branch : main
   - Publish directory : `/`
5. **Site settings** → "Access control" → Activer "Password protection"
6. Définir un mot de passe
7. URL type : `https://cours-ifca-pac.netlify.app/`

**Avantages Netlify :**
- ✅ Protection par mot de passe
- ✅ HTTPS automatique
- ✅ Déploiement automatique à chaque commit
- ✅ Statistiques de visite

---

## 🎨 **PERSONNALISATION README.md**

Créer un beau README pour votre dépôt :

```markdown
# Formation Prévention des Risques Professionnels
## IFCA / PAC - GRETA du Var / GIP FIPAN

[![Statut](https://img.shields.io/badge/statut-prod-success)](https://votre-compte.github.io/cours-ifca-pac/)
[![Conformité](https://img.shields.io/badge/conformit%C3%A9-100%25-brightgreen)](docs/AUDIT_CONFORMITE_REGLEMENTAIRE.md)
[![Licence](https://img.shields.io/badge/licence-Formation-blue)]()

---

## 📚 Présentation

Support de formation complet (5 jours / 35h) sur la prévention des risques professionnels dans les métiers de l'installation frigorifique et climatisation.

**Conforme aux référentiels :**
- ✅ CAP IFCA (Compétence C2)
- ✅ Amiante SS4 (Arrêté 23/02/2012)
- ✅ Code du travail (DUERP, prévention)
- ✅ Code environnement (déchets, BSD)

---

## 🚀 Accès au cours

**📖 Lien direct :** [Accéder au cours en ligne](https://votre-compte.github.io/cours-ifca-pac/)

---

## 📋 Contenu

### Programme (5 jours)
- **Jour 1** : EVRP & DUERP – Méthode robuste
- **Jour 2** : Maîtrise des risques & Coactivité
- **Jour 3** : Déchets / Électricité / Chimie
- **Jour 4** : Amiante (Information SS4)
- **Jour 5** : Ergonomie & TMS

### Annexes imprimables
1. EVRP (Évaluation des risques)
2. Plan d'actions prévention (6 exemples concrets)
3. Déchets : tri & suivi (DND/DD + BSD)
4. Amiante : procédure STOP + vocabulaire technique
5. TMS : analyse ergonomique (RULA/REBA/Borg)

---

## 📊 Conformité réglementaire

✅ **Audit complet réalisé** : [Voir rapport d'audit](docs/AUDIT_CONFORMITE_REGLEMENTAIRE.md)

**Score conformité : 100%**
- Contenu pédagogique : 5/5
- Structure pédagogique : 2/2
- Traçabilité : 2/2

---

## 👥 Utilisation

**Public cible :**
- Apprenants CAP IFCA
- Techniciens PAC/frigoristes
- Formateurs prévention risques
- Entreprises BTP/Froid/Clim

**Modalités :**
- En ligne (navigateur)
- Hors ligne (télécharger la page)
- Impression (optimisé PDF)

---

## 📖 Documentation

- [Enrichissements annexes](docs/ENRICHISSEMENTS_ANNEXES.md)
- [Validation boutons](docs/VALIDATION_BOUTONS_COMPLET.md)
- [Audit conformité](docs/AUDIT_CONFORMITE_REGLEMENTAIRE.md)

---

## 🏢 Organisme

**GRETA du Var / GIP FIPAN**  
Académie de Nice  
Contact : benoit.deflandre@ac-nice.fr

---

## 📜 Licence

© 2026 GRETA du Var / GIP FIPAN - Tous droits réservés  
Usage : Formation professionnelle uniquement
```

---

## ⚙️ **DÉPLOIEMENT AUTOMATIQUE (Avancé)**

### Avec GitHub Actions (CI/CD)

Créer `.github/workflows/deploy.yml` :

```yaml
name: Deploy to GitHub Pages

on:
  push:
    branches: [ main ]

jobs:
  deploy:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      
      - name: Deploy to GitHub Pages
        uses: peaceiris/actions-gh-pages@v3
        with:
          github_token: ${{ secrets.GITHUB_TOKEN }}
          publish_dir: ./
          publish_branch: gh-pages
```

**Avantage :** Déploiement automatique à chaque commit sur `main`

---

## 🔗 **PARTAGE & DIFFUSION**

### QR Code pour accès mobile

**Générer un QR Code :**
1. Aller sur https://www.qr-code-generator.com/
2. Coller l'URL : `https://votre-compte.github.io/cours-ifca-pac/`
3. Télécharger le QR Code
4. Imprimer sur support formation

### Lien court (optionnel)

**Utiliser bit.ly ou TinyURL :**
- URL longue : `https://votre-compte.github.io/cours-ifca-pac/`
- URL courte : `https://bit.ly/cours-ifca-pac`

Plus facile à communiquer aux apprenants !

---

## 📊 **STATISTIQUES VISITE (Optionnel)**

### Avec Google Analytics

1. **Créer compte** Google Analytics
2. **Obtenir le code tracking** (format : `G-XXXXXXXXXX`)
3. **Éditer** `index.html` et ajouter avant `</head>` :

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-XXXXXXXXXX');
</script>
```

**Remplacer** `G-XXXXXXXXXX` par votre ID

**Données disponibles :**
- Nombre de visiteurs
- Temps passé sur le cours
- Pages les plus consultées
- Origine géographique

---

## 🛠️ **MAINTENANCE & MISES À JOUR**

### Mettre à jour le cours

**Méthode simple (via interface GitHub) :**
1. Aller sur le dépôt
2. Cliquer sur `index.html`
3. Cliquer sur l'icône crayon (Edit)
4. Faire vos modifications
5. "Commit changes" en bas

**Le site se met à jour automatiquement en 1-2 minutes**

---

### Mettre à jour via Git (ligne de commande)

```bash
# Cloner le dépôt (première fois uniquement)
git clone https://github.com/votre-compte/cours-ifca-pac.git
cd cours-ifca-pac

# Modifier index.html localement
# Puis envoyer les modifications

git add index.html
git commit -m "Mise à jour contenu Jour 3"
git push origin main
```

---

## 🔧 **DÉPANNAGE**

### Problème : Page blanche après déploiement

**Solution :**
1. Vérifier que le fichier s'appelle bien `index.html` (pas `Cours_IFCA_PAC_ENRICHI.html`)
2. Vérifier dans Settings > Pages que "Source" = "Deploy from a branch"
3. Attendre 5 minutes (cache GitHub)
4. Vider le cache navigateur (Ctrl+Shift+R)

---

### Problème : URL ne fonctionne pas

**Vérifier :**
1. URL exacte : `https://VOTRE-COMPTE.github.io/REPO-NAME/`
   - ❌ `https://github.com/votre-compte/cours-ifca-pac/`
   - ✅ `https://votre-compte.github.io/cours-ifca-pac/`
2. Le dépôt doit être **Public** (ou GitHub Pro pour privé)
3. GitHub Pages activé dans Settings

---

### Problème : Modifications non visibles

**Solution :**
1. Attendre 2-5 minutes (déploiement)
2. Vider cache navigateur : 
   - Chrome/Edge : Ctrl+Shift+R (Windows) / Cmd+Shift+R (Mac)
   - Firefox : Ctrl+F5
3. Tester en navigation privée

---

## 📱 **ACCÈS MOBILE OPTIMISÉ**

Le cours est **100% responsive** et fonctionne parfaitement sur :
- ✅ Smartphones (iPhone, Android)
- ✅ Tablettes (iPad, Samsung)
- ✅ Desktop (Windows, Mac, Linux)

**Aucune application à installer** : simple navigateur web suffit

---

## 🌐 **DOMAINE PERSONNALISÉ (Optionnel)**

Si vous avez un domaine type `formation.greta-var.fr` :

### Configuration DNS

**Chez votre registrar (OVH, Gandi, etc.) :**
1. Ajouter un enregistrement CNAME :
   - Nom : `formation` (ou `cours-ifca`)
   - Cible : `votre-compte.github.io`

**Dans GitHub :**
1. Settings > Pages
2. "Custom domain" : `formation.greta-var.fr`
3. ✅ "Enforce HTTPS"
4. Save

**Attendre 24-48h** (propagation DNS)

---

## 📧 **NOTIFICATIONS MAJ**

### Recevoir un email à chaque mise à jour

1. Sur le dépôt GitHub → Cliquer "Watch" (en haut à droite)
2. Sélectionner "All Activity"
3. Vous recevrez un email à chaque commit

---

## 🎯 **CHECKLIST DÉPLOIEMENT**

Avant de partager l'URL aux apprenants :

- [ ] Fichier renommé en `index.html`
- [ ] GitHub Pages activé (Settings > Pages)
- [ ] URL testée et fonctionnelle
- [ ] Test sur mobile (responsive OK)
- [ ] Test impression (Ctrl+P / PDF OK)
- [ ] Tous les liens cliquables
- [ ] Boutons "Charger exemple" fonctionnent
- [ ] Boutons "Imprimer annexe" fonctionnent
- [ ] README.md créé et informatif
- [ ] QR Code généré (optionnel)
- [ ] URL courte créée (optionnel)

---

## 📞 **SUPPORT**

**Questions techniques GitHub :**
- Documentation : https://docs.github.com/pages
- Forum : https://github.community/

**Questions contenu formation :**
- Contact : benoit.deflandre@ac-nice.fr
- GRETA du Var / GIP FIPAN

---

## 🎓 **UTILISATION EN FORMATION**

### Scénarios pédagogiques

**Présentiel :**
- Vidéoprojecteur : afficher le cours depuis l'URL
- Apprenants : accès sur tablette/smartphone (QR Code)
- Travaux annexes : imprimer/remplir directement

**Distanciel :**
- Partager URL dans invitation visio
- Apprenants naviguent en autonomie
- Formateur : partage écran pour démonstration

**Hybride :**
- Consultation avant/après séance (classe inversée)
- Exercices annexes en asynchrone
- Révisions à domicile

---

## ✅ **AVANTAGES GITHUB PAGES**

**Pourquoi GitHub Pages est idéal pour ce cours :**

✅ **Gratuit** : 0€/mois, bande passante illimitée  
✅ **Rapide** : CDN mondial, chargement < 2s  
✅ **Fiable** : Disponibilité 99.9%, hébergé par GitHub  
✅ **HTTPS** : Sécurisé automatiquement  
✅ **Responsive** : Fonctionne tous devices  
✅ **Pas de pub** : Aucune publicité  
✅ **Versioning** : Historique complet des modifications  
✅ **Collaboratif** : Plusieurs contributeurs possibles  
✅ **Offline** : Téléchargeable (Ctrl+S)  

---

## 🚀 **EXEMPLE COMPLET**

**Dépôt GitHub déjà prêt :**
```
https://github.com/greta-var/cours-ifca-pac
```

**URL de consultation :**
```
https://greta-var.github.io/cours-ifca-pac/
```

**QR Code :**
```
[Générer sur qr-code-generator.com]
```

**Lien court :**
```
https://bit.ly/greta-ifca-pac
```

---

**C'est prêt ! Votre cours est maintenant accessible à tous vos apprenants en ligne. 🎉**
