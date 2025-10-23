# 📦 ISTRUZIONI CARICAMENTO SITO ENNESG

## 📁 Struttura Repository GitHub

Carica i file nel repository **enne-SG/EnneSG** con questa struttura:

```
EnneSG/
├── index.html
├── assets/
│   ├── ennesg-logo-main.svg
│   ├── ennesg-logo-horizontal.svg
│   └── ennesg-icon.svg
├── sistemi-iso/
│   └── index.html
├── dlgs-81-08/
│   └── index.html
└── area-aziende/
    └── index.html
```

---

## 🚀 PASSO 1: Prepara i File

### File Scaricati:
1. ✅ `index.html` → Homepage principale
2. ✅ `ennesg-logo-main.svg` → Logo completo
3. ✅ `ennesg-logo-horizontal.svg` → Logo compatto
4. ✅ `ennesg-icon.svg` → Icona favicon
5. ✅ `sistemi-iso-index.html` → Pagina Sistemi ISO
6. ✅ `dlgs-81-08-index.html` → Pagina Sicurezza
7. ✅ `area-aziende-index.html` → Pagina Area Aziende

---

## 🔧 PASSO 2: Carica su GitHub

### 1️⃣ Vai al Repository
Apri: https://github.com/enne-SG/EnneSG

### 2️⃣ Carica la Homepage
1. Clicca "Add file" → "Upload files"
2. Carica `index.html`
3. Commit message: "Add homepage"
4. Clicca "Commit changes"

### 3️⃣ Crea Cartella Assets
1. Clicca "Add file" → "Create new file"
2. Nel campo nome scrivi: `assets/README.md`
3. Scrivi: `# Loghi EnneSG`
4. Commit: "Create assets folder"

### 4️⃣ Carica i Loghi
1. Entra nella cartella `assets/`
2. Clicca "Add file" → "Upload files"
3. Carica tutti e 3 i file SVG:
   - `ennesg-logo-main.svg`
   - `ennesg-logo-horizontal.svg`
   - `ennesg-icon.svg`
4. Commit: "Add brand logos"

### 5️⃣ Crea Cartella Sistemi-ISO
1. Torna alla root del repository
2. Clicca "Add file" → "Create new file"
3. Scrivi: `sistemi-iso/index.html`
4. Copia-incolla il contenuto di `sistemi-iso-index.html`
5. Commit: "Add sistemi-iso page"

### 6️⃣ Crea Cartella DLgs-81-08
1. Torna alla root del repository
2. Clicca "Add file" → "Create new file"
3. Scrivi: `dlgs-81-08/index.html`
4. Copia-incolla il contenuto di `dlgs-81-08-index.html`
5. Commit: "Add dlgs-81-08 page"

### 7️⃣ Crea Cartella Area-Aziende
1. Torna alla root del repository
2. Clicca "Add file" → "Create new file"
3. Scrivi: `area-aziende/index.html`
4. Copia-incolla il contenuto di `area-aziende-index.html`
5. Commit: "Add area-aziende page"

---

## 🌐 PASSO 3: Attiva GitHub Pages

1. Vai su **Settings** del repository
2. Menu laterale → Clicca **Pages**
3. Sotto "Source" seleziona:
   - **Branch:** `main` (o `master`)
   - **Folder:** `/ (root)`
4. Clicca **Save**
5. Attendi 2-3 minuti

---

## ✅ PASSO 4: Verifica il Sito

Il sito sarà disponibile a:
**https://enne-sg.github.io/EnneSG/**

### Link Pagine:
- 🏠 Homepage: `https://enne-sg.github.io/EnneSG/`
- ⚙️ Sistemi ISO: `https://enne-sg.github.io/EnneSG/sistemi-iso/`
- 🛡️ Sicurezza: `https://enne-sg.github.io/EnneSG/dlgs-81-08/`
- 🏢 Area Aziende: `https://enne-sg.github.io/EnneSG/area-aziende/`

---

## 📝 PERSONALIZZAZIONI

### Modificare Contatti nella Homepage:

Apri `index.html` e cerca questa sezione (circa linea 560):

```html
<div class="footer-section">
    <h3>Contatti</h3>
    <p>📧 <strong>Email:</strong><br>info@ennesg.it</p>
    <p>📱 <strong>Telefono:</strong><br>[Inserisci numero]</p>
    <p>🌐 <strong>Web:</strong><br>www.ennesg.it</p>
    <p>📍 <strong>Sede:</strong><br>[Inserisci indirizzo]</p>
</div>
```

Sostituisci i dati tra parentesi quadre con le tue informazioni.

---

## 🔗 COLLEGARE I CORSI

I tuoi corsi (PES/PAV, Amianto, ecc.) sono in repository separati e restano così.

**Puoi linkarli dalla homepage aggiungendo:**

Nella sezione "Additional Services Details" (circa linea 360), aggiungi:

```html
<div class="service-item">
    <h4>⚡ Corsi Online</h4>
    <ul>
        <li><a href="https://enne-sg.github.io/corso-pespav/" target="_blank">PES/PAV CEI 11-27</a></li>
        <li><a href="https://enne-sg.github.io/corso-amianto/" target="_blank">Corso Amianto</a></li>
        <li>[Aggiungi altri corsi]</li>
    </ul>
</div>
```

---

## 📂 GESTIONE AZIENDE

Per ogni azienda cliente, crea un **repository separato**:

```
enne-SG/azienda-abc/
├── audit/
│   └── iso19011-checklist.html
└── procedure/
    └── procedura-xyz.pdf
```

Puoi linkarlo dall'Area Aziende o dare il link diretto al cliente.

---

## ⚠️ PROBLEMI COMUNI

### Il sito non si carica?
- Attendi 3-5 minuti dopo aver attivato Pages
- Verifica che GitHub Pages sia attivo in Settings → Pages
- Controlla che il branch sia `main` o `master`

### Le immagini non si vedono?
- Verifica che i file SVG siano nella cartella `assets/`
- Controlla che i nomi file siano esatti (maiuscole/minuscole)
- Path corretto: `assets/ennesg-logo-main.svg`

### I link tra pagine non funzionano?
- Verifica la struttura delle cartelle
- I link usano path relativi (`../assets/...`)

---

## 🎨 STRUTTURA FINALE

```
✅ https://enne-sg.github.io/EnneSG/
   ├── Homepage completa con tutti i servizi
   ├── /sistemi-iso/ → Consulenza ISO dettagliata
   ├── /dlgs-81-08/ → Sicurezza lavoro completa
   └── /area-aziende/ → Portal clienti audit ISO 19011

✅ Repository Corsi (separati)
   ├── corso-pespav
   ├── corso-amianto
   └── [altri corsi]

✅ Repository Aziende (separati)
   ├── azienda-001
   ├── azienda-002
   └── [altre aziende]
```

---

## 📞 SUPPORTO

Se hai bisogno di aiuto:
1. Screenshot dell'errore
2. Link al repository
3. Descrizione del problema

---

## 🎯 PROSSIMI PASSI

Dopo aver caricato tutto, posso creare:
- 📄 Sottopagine specifiche ISO (9001, 14001, 45001, 27001)
- 🎓 Indice corsi con link ai repository
- 📝 Template audit ISO 19011 funzionanti
- 📧 Form contatti con backend
- 🔐 Sistema login area aziende

---

**Tutto pronto! Inizia a caricare e il tuo sito sarà online! 🚀**

---

**Creato da EnneSG - Nicolò Sistemi di Gestione**
