# My Gemma Edge Skills 📱🤖

Una raccolta di agent skill personalizzati e ottimizzati per l'ecosistema **Google AI Edge** (tramite modelli Gemma 4), progettati per essere eseguiti al 100% in locale sul dispositivo, garantendo zero latenza e massima privacy.

## 🚀 Skill Disponibili

Le skill sono organizzate all'interno della cartella `skills/`:

| Nome Skill | Categoria | Descrizione | Stato |
| :--- | :--- | :--- | :--- |
| [**Alt-Text Generator**](./skills/alt-text-generator/SKILL.md) | Accessibility | Genera descrizioni accurate e accessibili (Alt-Text) per le immagini in italiano. | ✅ Pronto |
| [**Privacy Advisor**](./skills/privacy-advisor/SKILL.md) | Security & Privacy | Analizza on-demand le foto alla ricerca di rischi per la privacy (password, PII, volti, targhe). | ✅ Pronto |

## 🛠️ Architettura e Filosofia

Tutte le skill contenute in questo repository seguono questi principi fondamentali:
1. **On-Device Execution:** Sfruttano i modelli locali Gemma 4 (es. versioni E2B/E4B ottimizzate per mobile tramite LiteRT).
2. **Privacy by Design:** Nessun dato, immagine o testo analizzato lascia mai lo smartphone o viene inviato a server cloud esterni.
3. **Conversational UX:** Progettate per essere invocate on-demand tramite interfacce chat o menu di condivisione nativi del sistema operativo.

## 📂 Struttura del Repository

```text
.
└── skills/
    ├── alt-text-generator/
    │   └── SKILL.md          # Configurazione prompt per l'Alt-Text
    └── privacy-advisor/
        └── SKILL.md          # Configurazione prompt per l'analisi privacy