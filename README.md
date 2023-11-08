# 5CIA-Progetto-2-Lanini-Client

Creare due progetti maven (uno per il server e uno per il client) e salvarli su repository git.
I repo git non deveno avere i file compilati (cartella target)
---
Realizzare un client/server tcp
Il server si avvia e genera un numero random tra 1 e 100 che il client deve provare ad indovinare.
Definire un protocollo di comunicazione (es. 1->numero troppo piccolo, 2->numero troppo grande, 3->numero indovinato)
---
Esempio di scambio messaggi sul socket:

client -> 12
server -> 1
client -> 87
server -> 2
client -> 22
server -> 1
client -> 31
server -> 3
server -> 4
 ---
Esempio di output sul terminale del client:

Connessione effettuata

Inserisci il numero:
12
Numero troppo piccolo

Inserisci il numero:
87
Numero troppo grande

Inserisci il numero:
22
Numero troppo piccolo

Inserisci il numero:
31
HAI INDOVINATO IN 4 tentativi
