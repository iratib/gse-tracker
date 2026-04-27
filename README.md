# 📱 GSE Tracker — Guide de Partage et Utilisation

## 🎯 Fichiers disponibles

### 1. **GSE_Tracker.html** (Application principale)
- Application de suivi matériel RAMP
- Compatible : Windows, Mac, Linux, Mobile
- Pas d'installation nécessaire
- **Action** : Double-cliquer pour ouvrir dans le navigateur

### 2. **QR_Share.html** (Page de partage)
- Génère un QR code scannable
- Affiche le lien d'accès
- **Action** : Double-cliquer pour voir le QR code

---

## 📥 Téléchargement & Partage

### Option 1 : Lien Direct
```
c:/Users/hp/Desktop/trackertest/files/GSE_Tracker.html
```
- Copier-coller dans l'Explorateur Windows pour accéder
- Ou scanner le QR code depuis **QR_Share.html**

### Option 2 : Téléchargement
1. Ouvrir le fichier `GSE_Tracker.html` dans le navigateur
2. Faire un clic-droit → **Enregistrer sous**
3. Choisir le dossier de destination

### Option 3 : Partage sur Mobile
#### Par Email
- Joindre le fichier `GSE_Tracker.html`
- Le destinataire l'ouvre dans son navigateur mobile

#### Par Telegram / WhatsApp / Drive
1. Uploader le fichier sur:
   - **Google Drive** : Partager le lien
   - **OneDrive** : Partager le lien
   - **Telegram** : Envoyer le fichier directement
   - **WhatsApp** : Envoyer le fichier (dépend du type d'appareil)

#### Par QR Code
1. Scanner le code depuis `QR_Share.html`
2. Le code encode le chemin du fichier

---

## 🖥️ Utilisation sur différentes plateformes

### Windows / Mac / Linux
```
1. Double-cliquer sur GSE_Tracker.html
2. OU faire clic-droit → Ouvrir avec → Navigateur web
3. L'application se lance automatiquement
```

### Mobile (iOS / Android)
```
1. Télécharger le fichier .html
2. Ouvrir avec Chrome, Firefox, Safari, ou Edge
3. L'application s'affiche en plein écran
```

### Serveur Local (Optionnel)
Si vous avez Python installé :
```bash
cd c:\Users\hp\Desktop\trackertest\files
python -m http.server 8000
```
Accès : `http://localhost:8000/GSE_Tracker.html`

---

## 🔗 Lien de Partage Rapide

**Chemin complet :**
```
c:\Users\hp\Desktop\trackertest\files\GSE_Tracker.html
```

**QR Code :** Ouvrir `QR_Share.html` et scanner

---

## ⚙️ Configuration

### Google Sheets
L'application se connecte à cette Google Sheet :
```
https://docs.google.com/spreadsheets/d/e/2PACX-1vSZvnaH1B9Il4UEd7JCiRi-UE0XZLaJJ4fK2AbA0aN9ZEscl4aO8rck0dMt9Yhol352QI6Gw2SIe6jF/pub?gid=0&single=true&output=csv
```

**Pour utiliser votre propre sheet :**
1. Remplacer l'URL dans le fichier `GSE_Tracker.html` (rechercher `CSV_URL`)
2. S'assurer que votre Google Sheets est **publié sur le web** (Fichier → Partager → Publier sur le web)

---

## 📊 Fonctionnalités

- ✅ Dashboard avec KPI en temps réel
- ✅ Inventaire avec filtres (Zone, État)
- ✅ Recherche par numéro engin ou désignation
- ✅ Historique par engin
- ✅ Statistiques (donut chart, zones)
- ✅ Parsing robuste CSV (BOM, multi-séparateurs)
- ✅ Normalisation flexible des colonnes

---

## 🛠️ Support

**Console (F12)** : Affiche les logs de debug pour vérifier la détection des colonnes CSV

**Erreur de connexion ?**
1. Vérifier que la Google Sheet est bien publié
2. Vérifier la connexion internet
3. Cliquer sur "Actualiser"

---

**Version :** 2.0 (Parsing robuste activé)  
**Dernière mise à jour :** 27 avril 2026
