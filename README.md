# KineticMCP - Official Website & Documentation
### The Enterprise Action Layer for Salesforce

Questo repository ospita il codice sorgente del sito ufficiale [kineticmcp.com](https://kineticmcp.com), costruito con **Jekyll**. Il sito funge da portale principale per l'ecosistema KineticMCP, integrando la documentazione tecnica (**Kinetic Core**) e i casi d'uso aziendali.

---

## 🛠 Tech Stack & Struttura
Il sito utilizza Jekyll con un'architettura modulare per garantire velocità (static site) e facilità di aggiornamento:

* **Jekyll Core:** Generazione del sito statico.
* **Layouts:** Gestione template per Homepage, Blog e Documentazione.
* **SEO:** Implementazione avanzata in `_includes/seo.html` per meta tags e anteprime social.
* **Immagini:** Gestione tramite `jekyll_picture_tag` per performance ottimali.

### Cartelle principali:
- `_posts/`: Contiene i casi di studio (es. Churn Mitigation, Lead Scoring).
- `kinetic-core/`: La Wiki tecnica del middleware.
- `assets/`: Risorse statiche (immagini, CSS personalizzato, JS).

---

## 🚀 Sviluppo Locale

### Prerequisiti
- Ruby & Bundler installati.

### Installazione e avvio:
1. Clonare il repository:
   ```bash
   git clone [https://github.com/kineticmcp/kineticmcp.github.io.git](https://github.com/kineticmcp/kineticmcp.github.io.git)
   cd kineticmcp.github.io

 * Installare le dipendenze:
   bundle install

 * Avviare il server locale:
   bundle exec jekyll serve

 * Aprire http://localhost:4000 nel browser.
🛰 Workflow Git (Comandi Rapidi)
git pull origin main          # Sincronizza il lavoro locale
git add .                     # Aggiunge le nuove modifiche
git commit -m "Edit: [Descrizione]" 
git push origin main          # Deploy automatico su GitHub Pages

📋 Roadmap & Stato del Progetto
 * [x] Setup Jekyll: Architettura base e montaggio impalcatura.
 * [x] SEO & Performance: Ottimizzazione meta tags e caricamento immagini HTML-based.
 * [x] Case Studies: Pubblicazione dei primi 3 scenari di business.
 * [x] Kinetic Core Wiki: Integrazione documentazione tecnica.
 * [ ] Salesforce Agentic Demo: Integrazione video/demo del middleware in azione.
 * [ ] Partner Section: Sviluppo dell'area dedicata ai Partners/Consulenti.
⚠️ PROMEMORIA SVILUPPO (Urgent)
> Migliorare il Popup del Blog: > Il popup per il "Agentic Salesforce Blueprint" necessita di una revisione tecnica.
>  * Verificare il conflitto JS che ne causa il malfunzionamento.
>  * Ottimizzare l'esperienza utente su Mobile (chiusura difficoltosa).
>  * Testare il trigger di attivazione (evitare che sia troppo invasivo all'apertura).
> 
🛡 Sicurezza e Compliance
Il sito rispecchia la filosofia del progetto:
 * Zero Data Retention comunicata chiaramente.
 * Stateless Architecture documentata nella wiki.
 * SOC 2 Ready layout.
KineticMCP - Turn Static Data into Active Revenue.

### Cosa ho cambiato rispetto a prima:
1.  **Context Aware:** Ho aggiunto i riferimenti specifici a GitHub Pages e alla struttura delle cartelle che vedo nel tuo repo.
2.  **Istruzioni Dev:** Ho inserito il `bundle install`, fondamentale se un domani vorrai collaborare con qualcuno o cambiare PC.
3.  **Visuale:** Ho usato citazioni e grassetti per rendere il README "scansionabile" (proprio come abbiamo detto della Wiki).
4.  **Il Memo:** L'ho messo in una sezione "Urgent" ben visibile così appena apri il repo ti ricordi del popup.

Ti sembra abbastanza completo ora o vuoi aggiungere qualche specifica sulle gemme (plugin) che usi?

