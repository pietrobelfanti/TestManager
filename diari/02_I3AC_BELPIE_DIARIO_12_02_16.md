# DIARIO
### LUOGO
Trevano
### DATA
02.12.2016
## LAVORI SVOLTI
10.05 - 11.00: Nicola ha creato il webserver mentre io ho svolto delle ricerche sull'utilizzo di mysql in php.

11.00 - 12.20: Abbiamo creato il database 'testmanager' connesso al webserver e abbiamo creato anche le sue tabelle 'users' e 'admin'. 

13.15 - 15.30: Abbiamo creato la pagina di login e provato a fare delle query di prova in php ma abbiamo riscontrato dei problemi nella connessione al database(spiegati nella apposita sezione) in seguito risolti.


## PROBLEMI RISCONTRATI E SOLUZIONI
Inizialmente, quando dovevamo connetterci alla pagina index del webserver, dava l'errore "Accesso negato nella visualizzazione della pagina".
Abbiamo risolto questo errore con il comando "chmod -R 755/var/www/html" che da i permessi di lettura alla cartella dove era presente il file "index.html"
<br>

Successivamente, non riuscivamo a connetterci al database da php perché avevamo messo la password dell'utente SQL sbagliata.
Dopo esserci connessi correttamente le query di prova funzionavano.

## PUNTO DELLA SITUAZIONE RISPETTO ALLA PIANIFICAZIONE
In linea
## PROGRAMMA DI MASSIMA PER LA PROSSIMA GIORNATA
Fine pagina di login e inizio pagina di registrazione
