# Project Work #2 – Sistemi Informativi & Business Intelligence
*(Corso: Sistemi Informativi & Business Intelligence – Analisi di Serie Storiche)*

Questo project-work si focalizza sulla analisi delle serie storiche sulla base di diversi domini ed applicazioni reali (energia, mobilità, ambiente, clima, ecc.).

Per ogni dataset sono riportati:
* una breve descrizione dei dati;
* i comandi per il download (wget) e un link alla versione mirror su Kaggle;
* una descrizione della struttura dei dati e delle variabili principali;
* la definizione della/e variabile/i target;
* una lista di compiti suggeriti, lasciando libertà sulla scelta dei modelli statistici o di machine learning.

### Compito generale dello studente:
1. **Caricare e pulire il dataset scelto** (concordato/assegnato dal docente);
2. **Effettuare un’analisi esplorativa** della serie storica (grafici, trend, stagionalità, correlazioni, qualità dei dati);
3. **Eseguire l’opportuno preprocessing** e costruire uno o più modelli predittivi per la serie storica (modelli a scelta dello studente);
    > **N.B.** specifici dataset potrebbero prevedere particolari modelli da utilizzare.
4. **Valutare le prestazioni dei modelli** con metriche adeguate (es. MAE, RMSE) e confronto con baseline semplici;
    > **N.B.** Instanziare una baseline semplice e valutare le performance di modelli più performanti.
5. **Presentare un breve report (Slides)** che colleghi i risultati a un contesto decisionale o di supporto alle decisioni.

---

## Dataset 1 – Metro Interstate Traffic Volume
**Dominio:** Trasporti / Traffico

### Download
**Sorgente originale (wget):**
```bash
wget -O metro_interstate_traffic_volume.zip "[https://archive.ics.uci.edu/static/public/492/metro%2Binterstate%2Btraffic%2Bvolume.zip](https://archive.ics.uci.edu/static/public/492/metro%2Binterstate%2Btraffic%2Bvolume.zip)"
unzip metro_interstate_traffic_volume.zip