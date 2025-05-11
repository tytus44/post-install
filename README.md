# post-install

NeRO WINDOWS POST-INSTALL Script (V1.5)
Lo script NeRO WINDOWS POST-INSTALL V1.5 è progettato per automatizzare una serie di operazioni di post-installazione e ottimizzazione su Windows, facilitando la configurazione del sistema e l'installazione di applicazioni e risorse comuni. Di seguito sono elencate le principali funzionalità e operazioni svolte dallo script:

Funzionalità principali:
Elevazione privilegiata:

Verifica e, se necessario, esegue lo script con privilegi di amministratore.

Creazione di un punto di ripristino:

Crea un punto di ripristino di sistema per consentire un eventuale ritorno alle condizioni iniziali dopo l'esecuzione dello script.

Gestione percorsi e cartelle:

Imposta i percorsi delle risorse utilizzate dallo script.

Crea cartelle necessarie per il log e altre risorse.

Copia dei file utente e risorse:

Copia immagini utente e sfondi nelle directory di sistema appropriate.

Installazione e configurazione di risorse:

Installa fonts e cursori personalizzati.

Configura il Windows Terminal (impostazioni settings.json).

Gestisce i permessi per i temi di Windows, rimuovendo temi predefiniti e applicando nuovi temi.

Installazione di Microsoft Office:

Esegue l'installazione di Office 365 utilizzando un file di configurazione locale.

Installazione di applicazioni tramite Winget:

Installa e aggiorna applicazioni tramite Winget, inclusi software essenziali come Microsoft DirectX, VCRedist, e applicazioni dal Microsoft Store.

Ottimizzazione del sistema:

Modifica le impostazioni di Windows per migliorare le prestazioni e la privacy, come la disabilitazione della schermata di blocco, la gestione delle ottimizzazioni di Windows Update, e altre configurazioni di sistema.

Riavvio automatico del sistema:

Riavvia il sistema al termine dell'esecuzione per applicare tutte le modifiche.

Gestione degli errori:
Ogni fase dello script include una gestione degli errori che interrompe l'esecuzione e scrive un log dettagliato in caso di problemi.

Il log include informazioni su ogni operazione, con la possibilità di tracciare facilmente eventuali problemi tramite il file di log generato (postinstall.log).

Requisiti:
Il script deve essere eseguito con privilegi amministrativi.

Il sistema deve supportare PowerShell e Winget.

Log:
Il file di log viene creato automaticamente nella stessa cartella dello script (postinstall.log).

Il log contiene dettagli su ogni operazione, con colorazione per messaggi di tipo INFO, OK ed ERRORE.

