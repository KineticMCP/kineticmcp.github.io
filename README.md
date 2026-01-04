Ecco il testo completo del README aggiornato. L'ho ripulito dai vecchi riferimenti obsoleti e ho inserito il promemoria per il popup in una sezione dedicata alle attività prioritarie, così lo avrai sempre sott'occhio nel repository.
# KineticMCP - The Enterprise Action Layer for Salesforce

**KineticMCP** è l'architettura middleware basata su **MCP (Model Context Protocol)** che trasforma Salesforce in un sistema operativo cognitivo per agenti AI. Questo repository gestisce il core del sito e la documentazione tecnica del progetto.

---

## 🚀 Comandi Rapidi per lo Sviluppo

### Jekyll (Locale)
Per avviare l'anteprima del sito in locale:
```bash
bundle exec jekyll serve

Accessibile su: http://localhost:4000
Git Workflow
git pull origin main          # Sincronizza repository
git add .                     # Prepara modifiche
git commit -m "Descrizione"   # Crea commit
git push -u origin main       # Carica online

🏗️ Architettura & Stato del Progetto
✅ Completato
 * Infrastruttura: Setup Jekyll, SEO dinamica e meta tags (_includes/seo.html).
 * Visual: Heroes con caricamento immagini ottimizzato via HTML.
 * Content: Clonazione contenuti e implementazione della Wiki "Kinetic Core".
 * Blog: Inserimento dei primi 3 casi di studio (Lead Scoring, Contracts, Churn).
🔜 Prossimi Passi (Priorità)
 * Middleware Integration: Finalizzazione del modulo di comunicazione Salesforce.
 * Business Demo: Produzione video dimostrativo per la Homepage.
 * Partnership Program: Creazione della sezione dedicata ai Partner.
 * Automazione: Script di deploy e minify per la produzione.
⚠️ MEMO CRITICO - DA SISTEMARE
 * [ ] Ottimizzazione Popup Blog: Il popup "Agentic Salesforce Blueprint" presenta anomalie nel funzionamento. Verificare il trigger di attivazione (delay/scroll) e assicurarsi che sia facilmente chiudibile, specialmente su dispositivi mobile, per non disturbare la lettura dei casi di studio.
🛠 Configurazione Git (Remote Setup)
In caso di riconfigurazione del server remoto:
# Verifica directory
pwd

# Inizializzazione (se necessario)
git init

# Aggiunta remote
git remote add origin [https://kiwi.kineticmcp.com/antonio/kinetic-mcp.git](https://kiwi.kineticmcp.com/antonio/kinetic-mcp.git)

# Verifica
git remote -v

# Primo Push
git add .
git commit -m "Initial commit"
git push -u origin main

© 2026 KineticMCP Team - Progetto Enterprise Action Layer.

Posso aiutarti a scrivere il testo del **"Blueprint"** che l'utente riceverà una volta compilato il popup, così da avere anche quel contenuto pronto?

