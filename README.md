🚗Automotive Search Trends Analysis (2004 – Presente)

Progetto realizzato durante il corso Data Analytics di Boolean  
Un'analisi esplorativa sull'evoluzione dell'interesse di ricerca globale verso i principali marchi automobilistici europei rispetto ai nuovi competitor dell'elettrico (Tesla e BYD).


🎯 Obiettivo del Progetto
L'esercizio nasce con l'obiettivo di estrarre, pulire e visualizzare serie storiche da Google Trends utilizzando Google Fogli. 

Per rendere l'analisi più significativa, il confronto è stato ampliato su un orizzonte temporale pluriennale (dal 2004 ad oggi), mettendo a paragone storici brand europei (Volkswagen, Audi, Opel) con i principali protagonisti della transizione elettrica (Tesla, BYD), al fine di osservare come la crisi dell'industria automobilistica tradizionale si rifletta nell'interesse degli utenti online.


🛠️ Strumenti e Metodologia
 Fonte Dati: Google Trends (dati mensili sull'interesse di ricerca nel tempo e distribuzione geografica per Paese).
 Tool di Analisi: Google Fogli (Google Sheets).
 Tecniche utilizzate:
   Aggregazione temporale: Utilizzo di Tabelle Pivot e funzioni `MEDIA` per trasformare i dati mensili in medie annuali (YoY), eliminando la stagionalità per evidenziare il trend di lungo periodo.
   Normalizzazione geografica: Calcolo della media equipesata (non ponderata) per Paese, assegnando lo stesso peso a ciascuno Stato indipendentemente dalla popolazione.
   Analisi della Dominance Territoriale: Utilizzo di formule nidificate (`MAX`, `CONFRONTA`, `CONTA.SE`) per identificare il marchio leader in ogni nazione e calcolarne la quota di leadership geografica.

---

## 📊 Principali Risultati (Key Findings)

1. Contrazione dei marchi europei: Nel corso degli ultimi anni si osserva una progressiva e costante erosione dell'indice di interesse verso i produttori europei tradizionali (in particolare Volkswagen e Opel), segnale di una perdita di centralità mediatica e di mercato.
2. Ascesa dei player EV: Tesla consolida una forte presenza globale, mentre BYD mostra una rapida crescita nell'indice di interesse internazionale, erodendo quote di attenzione ai marchi occidentali.

<img width="797" height="520" alt="image" src="https://github.com/user-attachments/assets/a9fd886f-dcf2-4c14-98da-5d9c16b55bdf" />



---

## ⚠️ Note Metodologiche e Limitazioni dello Studio
Per una corretta lettura dei risultati, è fondamentale tenere presenti due aspetti:
 Indice di Interesse vs Dati Finanziari: I dati di Google Trends rappresentano un indice relativo di popolarità delle ricerche (normalizzato su scala 0–100) e non costituiscono metriche finanziarie, volumi di vendita o immatricolazioni reali.
 Assenza del Mercato Cinese: Poiché Google non opera nella Cina continentale (dove il motore di ricerca dominante è Baidu), i dati relativi a BYD e agli altri marchi riflettono esclusivamente la loro risonanza ed espansione nei mercati occidentali e internazionali, sottostimando il volume reale complessivo del brand asiatico.

---

## 🔗 Link Utili
 [Visualizza il Foglio Google con dati e grafici](#https://docs.google.com/spreadsheets/d/e/2PACX-1vQg-CKyJNJ2WFty1nqPPjQeUXWqObsDHPIluBgISFWx4P3b2KYoLQbNPlKWZA69Kf7xOt-1XoMtAnNS/pubhtml#gid=1922203689) 
