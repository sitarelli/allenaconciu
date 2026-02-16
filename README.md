# 💪 Scheda di Allenamento - App Web PWA

App web interattiva per gestire la scheda di allenamento con i pesi a casa.

## ✨ Caratteristiche

- ✅ **Checkbox** per spuntare esercizi completati
- ⏱️ **Timer integrato** per riposi e plank
- 💾 **Salvataggio automatico** dei progressi in locale
- 📱 **Ottimizzata per mobile** (iPhone/Android)
- 🔌 **Funziona offline** dopo il primo caricamento
- 🏠 **Installabile** come app sulla schermata Home

## 🚀 Istruzioni per il Deployment su GitHub Pages

### Step 1: Crea un Repository su GitHub

1. Vai su [github.com](https://github.com) e fai login
2. Clicca sul pulsante **"+"** in alto a destra → **"New repository"**
3. Dai un nome al repository (es. `scheda-allenamento`)
4. Seleziona **"Public"**
5. **NON** selezionare "Add a README file"
6. Clicca **"Create repository"**

### Step 2: Carica i File

Hai due opzioni:

#### Opzione A: Upload via Browser (più semplice)

1. Nella pagina del repository appena creato, clicca **"uploading an existing file"**
2. Trascina tutti i file di questa cartella nella finestra del browser:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `README.md`
   - `icon-192.png`
   - `icon-512.png`
3. Scrivi un messaggio tipo "Initial commit"
4. Clicca **"Commit changes"**

#### Opzione B: Via Terminale (se hai familiarità con Git)

```bash
cd /percorso/alla/cartella/workout-app

git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/TUO-USERNAME/scheda-allenamento.git
git push -u origin main
```

### Step 3: Attiva GitHub Pages

1. Nel tuo repository, vai su **Settings** (in alto)
2. Nel menu laterale, clicca su **Pages**
3. In **"Source"**, seleziona **"Deploy from a branch"**
4. In **"Branch"**, seleziona **"main"** e cartella **"/ (root)"**
5. Clicca **"Save"**

### Step 4: Ottieni il Link dell'App

1. Aspetta 1-2 minuti
2. Ricarica la pagina Settings > Pages
3. Vedrai un box verde con il link: **`https://TUO-USERNAME.github.io/scheda-allenamento`**
4. Clicca sul link per aprire l'app! 🎉

## 📱 Come Installare l'App su iPhone

1. Apri il link con **Safari** (non Chrome!)
2. Tocca il pulsante **"Condividi"** (quadrato con freccia verso l'alto)
3. Scorri e tocca **"Aggiungi a schermata Home"**
4. Dai un nome all'app (es. "Il Mio Workout")
5. Tocca **"Aggiungi"**

Ora hai un'icona sulla schermata Home come un'app vera! 🎊

## 🔧 Come Aggiornare l'App

Se vuoi modificare qualcosa:

1. Vai su GitHub nel tuo repository
2. Clicca sul file da modificare (es. `index.html`)
3. Clicca sull'icona della matita (Edit)
4. Fai le modifiche
5. Clicca **"Commit changes"**
6. Aspetta 1-2 minuti e l'app si aggiornerà automaticamente!

## 💡 Consigli d'Uso

- **Prima volta**: Assicurati di avere connessione internet
- **Timer**: Usa il timer per i riposi tra le serie (default 60 secondi)
- **Progressi**: I tuoi progressi sono salvati nel telefono, non nel cloud
- **Reset**: Usa il pulsante "Reset" per ricominciare una sessione
- **Offline**: Dopo il primo caricamento funziona anche senza internet!

## 📝 Struttura Settimanale

- **Lunedì**: Parte superiore (schiena, spalle, braccia) + mobilità
- **Martedì**: Cardio (Balla e Snella)
- **Mercoledì**: Riposo o mobilità leggera
- **Giovedì**: Parte inferiore (gambe, glutei) + core + mobilità
- **Venerdì**: Cardio (Balla e Snella)
- **Weekend**: Riposo attivo (stretching, camminata)

## 🎯 Obiettivo

Contrasto osteopenia/osteoporosi attraverso allenamento con carichi progressivi.

## 📞 Supporto

Se hai problemi con il deployment, controlla:
- Che il repository sia **Public**
- Che GitHub Pages sia attivato su branch **main**
- Che i file siano nella cartella root (non in sottocartelle)

---

**Buon allenamento! 💪**
