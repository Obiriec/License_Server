// =======================================================================================
// ✅ GANN SWINGS ZIG-ZAG (by Fury Team)
// 📅 Versione: 1.2.1 – Versione avanzata con analisi pattern e dashboard
// 📌 Descrizione: Indicatore Zig-Zag strutturale basato su swing validi (3 candele)
// 🔧 Creato per l'analisi visiva dei punti di swing secondo il metodo originale di Gann
// 👨‍💻 Autore: Armando Brecciaroli per conto del Fury Team
// =======================================================================================
/*
         * ===============================================================================
         * 📝 CHANGELOG GANN SWINGS ZIG-ZAG (by Fury Team)
         * ===============================================================================
         * 
         * v1.0.0 (2024-01-15):
         * - Prima release pubblica dell'indicatore
         * - Implementazione base del metodo ZigZag per punti di swing
         * - Supporto per visualizzazione di High e Low significativi
         * 
         * v1.0.5 (2024-02-10):
         * - Migliorata la precisione di calcolo dei punti di swing
         * - Aggiunta opzione per visualizzare distanza in pips tra swings
         * - Corretti bug nella visualizzazione grafica
         * 
         * v1.1.0 (2024-03-20):
         * - Aggiunto sistema di conferma dei punti di swing (con parametro numero barre)
         * - Implementato filtro di volatilità basato su ATR
         * - Ottimizzazioni di performance generali
         * 
         * v1.1.5 (2024-04-15):
         * - Aggiunto sistema di pulizia automatica dei vecchi punti per ottimizzare memoria
         * - Migliorato algoritmo di detection dei swing points
         * - Aggiunte etichette personalizzabili con informazioni precise
         * 
         * v1.1.7 (2024-05-01):
         * - Ottimizzazione della gestione della memoria
         * - Risolti problemi con timeframe molto brevi
         * - Migliorata la precisione del rilevamento nei mercati volatili
         * 
         * v1.1.8 (2024-05-22): 
         * - Integrato sistema di licenza base
         * - Aggiunto supporto per verifiche online/offline
         * - Migliorata la gestione degli errori
         * 
         * v1.1.9 (2024-05-23):
         * - Migrazione al sistema di licenza avanzato compatibile con Profit Sentinel
         * - Implementato controllo aggiornamenti avanzato con changelog
         * - Risolti problemi di compatibilità con cTrader 4.5
         * - Ottimizzato posizionamento notifiche su schermo
         *
         * v1.2.0 (2025-05-23):
         * - Ottimizzazione delle prestazioni con tracking degli indici già calcolati
         * - Sistema avanzato di gestione oggetti grafici con cleanup automatico
         * - Aggiunto sistema di alert per nuovi swing points 
         * - Implementata persistenza dei punti di swing con salvataggio/caricamento
         * - Aggiunta modalità debug avanzata con logging dettagliato
         * - Posizionamento intelligente delle etichette per evitare sovrapposizioni
         * - Implementato riconoscimento pattern di prezzo comuni sui punti di swing
         * - Aggiunta dashboard statistiche con metriche sui movimenti di prezzo
         * - Supporto per tema chiaro/scuro e personalizzazione visiva
         * - Nuova funzione di esportazione dati in formato CSV
         * - Algoritmo sperimentale di previsione swing points
         *
         * v1.2.1 (2025-05-26):
         * - Risolto problema con l'esecuzione della scansione storica su alcuni indici
         * - Corretta la gestione del parametro ShowOnlyHistoricalMode
         * - Migliorata l'inizializzazione delle variabili nella scansione storica
         * - Ottimizzata la gestione della memoria per le sessioni prolungate
         * - Risolti problemi di stabilità su timeframe molto lunghi
         * - Migliorata l'interazione tra la modalità storica e quella in tempo reale
         */
// =======================================================================================
