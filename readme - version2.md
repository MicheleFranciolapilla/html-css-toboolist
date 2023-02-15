 # ESERCIZIO CON UTILIZZO DI PSEUDO SELETTORI *-- VERSIONE 2 --*

- **Perche' una seconda versione?**
  - Si e' scelto di sviluppare una seconda versione per poter usare piu' estesamente gli pseudo selettori css.
- **Ambiti di modifica:**
  - La modifica ha interessato le liste presenti in ciascuna sezione del main.
- **In quali files sono state adottate le modifiche?**
  - Le modifiche hanno riguardato i files ***index.html*** e ***style.css***. I nuovi files sono stati nominati ***index - version2.html*** e ***style - version2.css*** ed hanno mantenuto le loro posizioni di origine.
- **Differenze in output tra le due versioni:**
  - Nessuna differenza. I due output sono praticamente indistinguibili, *nome pagina a parte*



### VANTAGGI INTRODOTTI DALLA VERSIONE 2:



- **Lato HTML:**
  - Maggior leggibilita' e pulizia del codice nelle `<section>` , `<ul>`, `<li>`
  - Rimozione delle classi di colorazione delle "pilloline"
  - Rimozione degli `<span>` dall'interno dei `<li>`
  - Rimozione dello `<strong>` dal tag `<ul>` con conseguente coerenza nell'indice di indirizzamento all'interno del **.css**
  - Il numero di classi utilizzate e' passato dalle **8** della *Version 1* alle **2** della *Version 2*
  - Il numero di id utilizzati e' passato da **2** a **3**. Peraltro, tutti gli id (eliminabili in una ipotetica versione 3), in entrambe le versioni, non richiedono alcuno sviluppo nel foglio di stile, essendo utilizzati solo ai fini dell'indirizzamento degli elementi nelle liste.
- **Lato CSS:**
  - Avendo eliminato il tag `<strong>` si ha una maggiore coerenza nell'indirizzamento dei singoli `<li>` e nell'attribuzione del `font-weight` ad `<ul>`
  - Si sono potuti utilizzare, sia lo pseudo selettore `::before` (usato anche nella version 1) che il `::after` (non usato nella version 1), oltre ad un maggior utilizzo (ai fini della pratica) degli altri pseudo selettori `:first-child`,`:last-child`,`:nth-child`



