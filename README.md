# Hellenic Train — UX Research, Usability Testing & UI Redesign

Case study di Interaction Design e User Experience focalizzato sull'analisi dell'usabilità e la riprogettazione del flusso transazionale del portale ferroviario ufficiale greco (**Hellenic Train**).

---

## Metodologia di Ricerca

Il processo di valutazione ha integrato tre metodologie complementari per identificare e quantificare i problemi di fruizione:

1. **Valutazione Euristica (Nielsen)**:
   - Ispezione esperta su Homepage, Pagina Risultati e Selezione Posto.
   - Violazioni primarie identificate: *Visibilità dello stato del sistema (#1)*, *Corrispondenza sistema-mondo reale (#2)*, *Coerenza e standard (#4)*, *Riconoscimento più che memorizzazione (#6)* ed *Estetica e design minimalista (#8)*.
2. **Cognitive Walkthrough**:
   - Scomposizione analitica di 3 task critici: Registrazione utente, Ricerca/Prenotazione A/R e Contatto assistenza.
   - Rilevazione dei punti di rottura nei flussi cognitivi (comandi poco visibili, etichette ambigue come *"Issue your ticket"*, feedback post-selezione mancanti).
3. **Test di Usabilità con Utenti (Thinking Aloud)**:
   - Sessioni controllate su 5 partecipanti segmentati per fasce d'età (Studenti 18–24, Lavoratori 40–60, Over 60) e alfabetizzazione digitale.
   - Raccolta di metriche quantitative (*Success rate*, tempo medio per task, numero di errori) e qualitative (*protocollo Think-Aloud concorrente*, questionari di soddisfazione con voti medi da 4.6/10 a 6/10).

---

## Risultati e Macro-Criticità Emerse

- **Gerarchia Visiva Inefficace**: Il modulo di ricerca viaggio sulla home competeva visivamente con banner secondari e pulsanti dal copy poco intuitivo.
- **Assenza di Feedback e Orientamento**: Mancanza di indicatori di avanzamento (stepper) nel checkout e assenza di conferme visive istantanee alla selezione dei posti.
- **Carico Cognitivo Elevato**: Mappa posti fitta, uniforme e priva di distinzione netta tra corridoi e sedili, con filtri di ricerca nascosti.

---

## Soluzione Progettuale (Figma Redesign)

La proposta di redesign su **Figma** risolve le criticità attraverso:
- **Homepage**: Box di ricerca centrale e dominante su card bianca a contrasto, con CTA primaria esplicita (*"ACQUISTA BIGLIETTO"*) e riorganizzazione della navigazione secondaria.
- **Filtri & Risultati**: Sidebar dedicata con filtri avanzati per orari, durata, prezzo e cambi; riepilogo prezzi persistente e stepper visivo del processo (*Risultati → Posto → Pagamento*).
- **Selezione Posto Semplificata**: Griglia delle carrozze riprogettata con ampi spazi bianchi per i corridoi, legenda cromatica ad alto contrasto (Occupato / Disponibile / Selezionato) e contatore posti in tempo reale.

---

## Contenuto del Repository

- `PROGETTO-HellenicTrain.pdf`: Documento completo di ricerca, tabelle dei test di usabilità, trascrizioni qualitative e schermate comparative.
