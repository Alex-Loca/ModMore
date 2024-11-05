# ModMore
## Descrizione
ModMore è una piattaforma per la gestione e distribuzione di mod per videogiochi. La piattaforma si distingue per la sua universalità, accogliendo contenuti per qualsiasi videogioco, sia esso supportato ufficialmente o meno e permette ai creatori di rimanere in contatto con la loro community. Per i giochi supportati, ModMore offre un sistema di installazione automatizzato che semplifica drasticamente l'esperienza utente.

## Tagline
Il tuo hub universale per le mod dei videogiochi: Scopri, Condividi, Gioca

## Target
Videogiocatori PC interessati ad avere contenuti aggiuntivi per i propri giochi, creatori di contenuti per videogiochi (modder)

## Problema risolto
- Mancanza di una piattaforma unica per qualsiasi videogioco
- Piattaforme esistenti possibilmente poco sicure perchè non sottopongono i contenuti caricati sotto opportuni controlli
- Difficoltà di installazione di mod per alcuni videogiochi
- Mancanza di un sistema di aggiornamenti automatici
- Necessità dei creatori di parlare dei propri contenuti tramite post

## Competitor
- Steam Workshop: integrato all'interno di Steam, è utilizzato come piattaforma di distribuzione di mod per videogiochi che le supportano ufficialmente
- CurseForge: parte dell'ecosistema Overwolf, utilizzato per una stretta cerchia di giochi, soprattutto per Minecraft
- Nexus Mods: accoglie soprattutto mod per giochi di ruolo (RPG)
- Overtake: concentrato sui simulatori di guida

## Tecnologie
- Svelte: framework JavaScript per il frontend per la realizzazione dell'interfaccia utente
- Electron: framework per la realizzazione di app ibride desktop
- Django: framework di Python per la realizzazione di backend di applicazioni
- Django-Ninja: framework di Python per la realizzazione di API RESTful
- MySQL: DBMS per il salvataggio dei dati
- Cloudfare: CDN per la distribuzione agevolata dei dati agli utenti

## Requisiti
### Requisiti funzionali
#### Diagramma dei casi d'uso degli utenti
![Diagramma UML dei casi d'uso utente](https://yuml.me/848f45dc.svg)
#### Diagramma dei casi d'uso degli amministratori
![Diagramma UML dei casi d'uso admin](https://yuml.me/a33256ed.svg)

#### Gestione Utenti
- Registrazione nuovo utente
- Login utente
- Modifica profilo utente
- Visualizzazione profilo

#### Gestione Contenuti
- Caricamento mod
- Download mod
- Creazione post blog
- Ricerca contenuti
- Gestione versioni mod
- Installazione automatica mod per giochi supportati
- Installazione aggiornamenti automatici
- Categorizzazione contenuti

#### Amministrazione
- Gestione utenti
- Moderazione contenuti
- Approvazione sicurezza mod
- Gestione segnalazioni
- Monitoraggio sistema

#### Community
- Recensioni su mod
- Commenti su blog post
- Sistema di follow creator
- Sistema di notifiche

### Requisiti non funzionali
#### Performance
- Tempo di risposta massimo per pagine web: 2 secondi
- Tempo di risposta massimo per ricerche: 3 secondi
- Supporto simultaneo di almeno 1000 utenti in download
- Velocità di download scalabile basata sulla connessione utente

#### Sicurezza
- Autenticazione a due fattori
- Scansione antivirus automatica dei contenuti caricati
- Protezione contro attacchi DDoS
- Backup giornalieri dei dati

#### Usabilità
- Interfaccia responsive per il sito web
- Supporto multilingua
- Compatibilità cross-browser per sito web
- Interfaccia desktop nativa per principali sistemi operativi

#### Affidabilità
- Uptime del sistema 99.9%
- Recupero automatico da errori di sistema
- Sistema di logging completo

### Requisiti di dominio
#### Gestione Mod
- Supporto per multipli formati di mod
- Gestione dipendenze tra mod
- Compatibilità con sistemi di modding esistenti

#### Integrazione Giochi
- API per integrazione con launcher di gioco
- Sistema di rilevamento giochi installati
- Gestione conflitti tra mod
- Supporto per diverse strutture di directory dei giochi
- Installazioni automatiche custom-made per ogni gioco supportato

#### Conformità alle norme
- Rispetto GDPR
- Rispetto DMCA
- Gestione diritti d'autore
- Termini di servizio e licenze d'uso