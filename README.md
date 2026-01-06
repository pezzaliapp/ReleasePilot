# ReleasePilot — PezzaliAPP (Offline)

**ReleasePilot** è una web app **offline-first** (un solo file HTML) per gestire i tuoi brani e preparare una release senza caos: scheda brano, checklist, lyrics EN/IT riga-per-riga, link e **AI Music Prompt** (prompt builder generico per generatori musicali AI).

- ✅ 100% offline (dati in `localStorage`)
- ✅ Nessun account, nessun upload, nessun tracking
- ✅ Backup/restore con JSON
- ✅ Interfaccia minimal, veloce, mobile-friendly

---

## Cosa trovi nell’interfaccia (1:1)

### Sidebar — Libreria brani
- Ricerca veloce: **titolo / tag / mood / BPM**
- Elenco brani con **release score (%)**
- Selezione brano per aprire l’editor

### Tab: **Cockpit**
- Titolo
- Artista / Progetto
- Data uscita
- BPM
- Tonalità
- Mood
- Tag
- ISRC (opzionale)
- Durata target
- Azioni: **Salva**, **Elimina brano**

### Tab: **Checklist**
Checklist per arrivare a “PRONTO” con calcolo automatico dello **score**:
- Cover 3000×3000 pronta
- Teaser 9:16 pronto
- Thumbnail YouTube pronta
- Descrizione YouTube (IT/EN)
- Caption IG + hashtags
- Post LinkedIn pronto
- Credits completi
- ISRC / metadati ok
- Upload / scheduling completato
- Commento fissato / CTA
- Stories pronte (1–3)
- Backup JSON fatto

### Tab: **Lyrics EN/IT**
- Editor doppio: **EN** e **IT** (una riga per volta)
- Anteprima “riga sotto riga”
- Mini-tools:
  - **Allinea righe (pad)**: aggiunge righe vuote per mantenere corrispondenza
  - **Scarica .txt EN+IT**: esporta un file testo pronto

### Tab: **AI Music Prompt ⭐**
Prompt builder a blocchi con contatore caratteri e controllo coerenza:
- Tempo / Groove
- Drums / Bass
- Harmony / Sound
- Vocals / Delivery
- Do / Don’t (regole)

Output:
- **Prompt finale (copiabile)**
- Caratteri: contatore + limite (500 / 1000 / 1500)
- **Consistency guard** (warning su incoerenze tipiche)
- Pulsante: **Copia prompt**

> Nota: il modulo è volutamente **agnostico** (non cita piattaforme specifiche).

### Tab: **Link & Note**
- Link DistroKid
- Link YouTube / VEVO
- Spotify
- Apple Music
- Note libere (mix, idee video, promo, ecc.)
- Azione: **Salva**

---

## Uso rapido

1. Scarica/clona la repo
2. Apri `index.htm` (o `index.html`) nel browser
3. Premi **+ Nuovo brano**
4. Compila i tab e usa la checklist come “rituale” di release
5. Fai **Export backup JSON** periodicamente

---

## Installazione locale (offline)

ReleasePilot è un file statico: funziona anche senza server.

- **Mac/Windows/Linux**: doppio click su `index.htm`
- **iPhone/iPad**: mettilo su una cartella accessibile (o GitHub Pages) e aggiungi a Home (opzionale)

---

## Backup & Restore

### Export
Header → **Export backup JSON**  
Scarichi un file tipo:
`ReleasePilot-backup-YYYY-MM-DD.json`

### Import
Header → **Import JSON**  
Seleziona un backup e ripristina brani e dati.

---

## Dati e privacy

- Dati salvati in `localStorage`
- Nessuna richiesta di rete
- Nessun analytics
- Nessun upload

---

## Struttura repo
ReleasePilot/
├─ index.htm
├─ README.md
└─ (opzionale) assets/

# ReleasePilot — PezzaliAPP (Offline)

**ReleasePilot** è una web app **offline-first** (un solo file HTML) per gestire i tuoi brani e preparare una release senza caos: scheda brano, checklist, lyrics EN/IT riga-per-riga, link e **AI Music Prompt** (prompt builder generico per generatori musicali AI).

- ✅ 100% offline (dati in `localStorage`)
- ✅ Nessun account, nessun upload, nessun tracking
- ✅ Backup/restore con JSON
- ✅ Interfaccia minimal, veloce, mobile-friendly

---

## Cosa trovi nell’interfaccia (1:1)

### Sidebar — Libreria brani
- Ricerca veloce: **titolo / tag / mood / BPM**
- Elenco brani con **release score (%)**
- Selezione brano per aprire l’editor

### Tab: **Cockpit**
- Titolo
- Artista / Progetto
- Data uscita
- BPM
- Tonalità
- Mood
- Tag
- ISRC (opzionale)
- Durata target
- Azioni: **Salva**, **Elimina brano**

### Tab: **Checklist**
Checklist per arrivare a “PRONTO” con calcolo automatico dello **score**:
- Cover 3000×3000 pronta
- Teaser 9:16 pronto
- Thumbnail YouTube pronta
- Descrizione YouTube (IT/EN)
- Caption IG + hashtags
- Post LinkedIn pronto
- Credits completi
- ISRC / metadati ok
- Upload / scheduling completato
- Commento fissato / CTA
- Stories pronte (1–3)
- Backup JSON fatto

### Tab: **Lyrics EN/IT**
- Editor doppio: **EN** e **IT** (una riga per volta)
- Anteprima “riga sotto riga”
- Mini-tools:
  - **Allinea righe (pad)**: aggiunge righe vuote per mantenere corrispondenza
  - **Scarica .txt EN+IT**: esporta un file testo pronto

### Tab: **AI Music Prompt ⭐**
Prompt builder a blocchi con contatore caratteri e controllo coerenza:
- Tempo / Groove
- Drums / Bass
- Harmony / Sound
- Vocals / Delivery
- Do / Don’t (regole)

Output:
- **Prompt finale (copiabile)**
- Caratteri: contatore + limite (500 / 1000 / 1500)
- **Consistency guard** (warning su incoerenze tipiche)
- Pulsante: **Copia prompt**

> Nota: il modulo è volutamente **agnostico** (non cita piattaforme specifiche).

### Tab: **Link & Note**
- Link DistroKid
- Link YouTube / VEVO
- Spotify
- Apple Music
- Note libere (mix, idee video, promo, ecc.)
- Azione: **Salva**

---

## Uso rapido

1. Scarica/clona la repo
2. Apri `index.htm` (o `index.html`) nel browser
3. Premi **+ Nuovo brano**
4. Compila i tab e usa la checklist come “rituale” di release
5. Fai **Export backup JSON** periodicamente

---

## Installazione locale (offline)

ReleasePilot è un file statico: funziona anche senza server.

- **Mac/Windows/Linux**: doppio click su `index.htm`
- **iPhone/iPad**: mettilo su una cartella accessibile (o GitHub Pages) e aggiungi a Home (opzionale)

---

## Backup & Restore

### Export
Header → **Export backup JSON**  
Scarichi un file tipo:
`ReleasePilot-backup-YYYY-MM-DD.json`

### Import
Header → **Import JSON**  
Seleziona un backup e ripristina brani e dati.

---

## Dati e privacy

- Dati salvati in `localStorage`
- Nessuna richiesta di rete
- Nessun analytics
- Nessun upload

---

## Struttura repo

ReleasePilot/
├─ index.htm
├─ README.md
└─ (opzionale) assets/

> Se pubblichi su GitHub Pages, puoi rinominare `index.htm` in `index.html`.

---

## Roadmap (idea)

- Generator Post (LinkedIn / IG / YouTube) con preset minimal PezzaliAPP
- Export “Release Pack” (zip con testi + link + checklist)
- Tagging avanzato e template personalizzati

---

## License

MIT

---

## Credits

ReleasePilot — **by PezzaliAPP**
