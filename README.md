# Gemma 4 - Alt Text Agent Skill (Social Ready) 🇮🇹

Un'estensione per gli agenti basati su **Gemma 4** tramite l'ecosistema **Google AI Edge Gallery**. Questa Skill trasforma il modello in un esperto di accessibilità digitale, ottimizzato per generare testi alternativi (Alt Text) in italiano, pronti per il copia-incolla immediato sui social media (LinkedIn, Bsky, Instagram, ecc.).

---

## 🚀 Caratteristiche principali

* **Output in Testo Puro**: Nessun formato JSON o parentesi graffe, il testo è pronto per il copia-incolla.
* **100% in Italiano**: Traduce e descrive automaticamente in italiano anche se l'immagine contiene testi o grafici in inglese.
* **Conformità WCAG**: Genera descrizioni concise (max 150 caratteri), oggettive e prive di ridondanze (evita "immagine di...").
* **Gestione Immagini Complesse**: Riconosce grafici e infografiche fornendo sia l'Alt Text breve sia una descrizione estesa dei dati.

---

## 🛠️ Come installarlo in Google AI Edge

Puoi importare questa Skill direttamente nell'applicazione Google AI Edge Gallery o nel tuo ambiente di sviluppo locale utilizzando l'URL Raw di GitHub.

### 1. Recupera l'URL Raw
1. Naviga all'interno di questa repository nella cartella `skills/alt-text-generator/`.
2. Clicca sul file `SKILL.md`.
3. In alto a destra, clicca sul pulsante **"Raw"**.
4. Copia l'URL completo dalla barra degli indirizzi del browser.

### 2. Importa la Skill nell'App
1. Apri la dashboard del tuo progetto in **Google AI Edge**.
2. Vai nella sezione **Agent Skills** (o *Custom Skills*).
3. Clicca su **Add / Import Skill** e seleziona **Import from URL**.
4. Incolla l'URL Raw precedentemente copiato e salva.

---

## 📖 Come utilizzarlo

Per evitare passaggi intermedi, puoi impostare questa Skill come **Default System Instruction** nelle impostazioni del modello Gemma 4.

Se invece preferisci usarla on-demand tramite il router delle competenze, ti basta:
1. Caricare l'immagine nella chat tramite l'interfaccia di sistema.
2. Digitare una delle seguenti frasi di attivazione (Trigger Phrases):
   * `alt text`
   * `genera alt text per questa immagine`
   * `descrizione accessibile`

---

## 📄 Struttura del Progetto

```text
gemma-alt-text-skill/
├── README.md                 # Questo file di documentazione
└── skills/
    └── alt-text-generator/
        └── SKILL.md          # Il file core con le istruzioni per Gemma 4