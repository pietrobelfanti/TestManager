# DIARIO
### LUOGO
Trevano
### DATA
16.12.2016
## LAVORI SVOLTI
10.05 - 12.20: Ho risolto il problema per il quale, nella scorsa lezione, non riuscivo a inserire i dati nel database da php. La soluzione è spiegata nell'apposito capitolo.
			   Ho iniziato a perfezionare la pagina di registrazione gestendo i controlli su ogni input, ad esempio, costringendo l'utente a utilizzare una password con almeno una maiuscola e un numero.		   
13.15 - 14.45: Ho finito di perfezionare la pagina di registrazione, facendo anche delle funzioni javascript (ad esempio, il nome utente --> nome.cognome appare automaticamente dopo aver inserito nome e cognome)
15.00 - 15.30: Ho iniziazto a cercare su internet il modo per inviare la mail di conferma della registrazione.

Nicola, che era a casa ammalato, ha iniziato a creare la pagina del calendario.

## PROBLEMI RISCONTRATI E SOLUZIONI
La soluzione al problema della lezione precedente, è stato risolto in un modo davvero semplice. Il problema stava nella query, l'istruzione "INSERT" era stata scritta "Insert" 
e quindi non veniva accettata. 

COME ERA LA QUERY PRIMA (NON FUNZIONANTE):
$sql = "Insert into users(Nome, Cognome, Email, Password, Nome_utente, Classe, Tipo) 
					VALUES('$myname','$mysurname', '$myemail','$mypassword','$myusername','$myclass' ,'Allievo')";
					
COME È LA QUERY ORA (FUNZIONANTE):
$sql = "INSERT into users(Nome, Cognome, Email, Password, Nome_utente, Classe, Tipo) 
					VALUES('$myname','$mysurname', '$myemail','$mypassword','$myusername','$myclass' ,'Allievo')";

## PUNTO DELLA SITUAZIONE RISPETTO ALLA PIANIFICAZIONE
In linea
## PROGRAMMA DI MASSIMA PER LA PROSSIMA GIORNATA
Fine pagina contenente il calendario.
