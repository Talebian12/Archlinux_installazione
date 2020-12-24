# Archlinux_installazione
Guida installazione di archlinux personalizzata



## Se vuoi modificare la guida

La guida è interamente scritta in markdown dalla <u>versione 1.6</u>

non ci dovrebbero essere particolari avvertimenti, solo seguite i template a fine del file. La sintassi markdown usata è quella supportata da Typora. i segni == contribuiscono a fare l'evidenziamento nel risultato pdf finale

## note rilascio 1.0
È uscita la versione 1.0 Talete, la prima versione di questa guida che mi sento dichiarare "matura".
__La primissima e importante novità è che ho abbandonato il file latex a vantaggio di un normalissimo odt__, modificabile con molte tipologie di suite per l'ufficio. Questa scelta sono sicuro che farà stizzire tantissimi utenti, ma latex non mi consentiva modifiche veloci al file da qualunque postazione, inoltre molti utenti lamentavano del fatto che con il copia e incolla alcuni caratteri sformattavano malissimo, quindi ho riscritto tutto. 
Il file latex è ancora nella cartella latex_old, chiunque volesse mantenerlo è libero di farlo. 
Prego a chiunque voglia suggerirmi modifiche, di non toccare la formattazione del file, si può discutere comunque su accostamenti colori/forme dei box, ma la decisione finale vorrei mi spettasse.

qui un riassunto di ciò che è stato introdotto/corretto:

* [add] aggiunta sezione per swap e ibernazione
* [fix] sistemata sezione pakku
* [fix] invertiti comandi per aggiornamento grub
* [add] aggiunta sezione lsd
* Comandone 
	* [fix] sostituito aurman con pakku
	* [fix] suddivise zone per tipologia di programmi
	* [add] aggiunto chrome
	* [fix] eliminato rar, in conflitto con unrar
	* [edit] sostituita la jdk proprietaria con quella open
* [fix] eliminato kde l10n it
* [add] aggiunto a neofetch il pacchetto pacman-contrib
* [add] aggiunta sezione per orario in dual boot con windows
* [add] aggiunte ( su richiesta di utenti) istruzioni per fdisk nella sezione dei dischi dell'installazione
* [fix/add/edit] altre piccole modifiche

## note rilascio 1.6 

è stata rilasciata la <u>guida completamente in markdown</u>. Per una maggiore semplicità nell'aggiornamento.

i todo verso 1.5.5 e 1.6 son stati spostati alle release 1.6.1 e 1.6.2

- [fix] nella creazione della penna usb c'era un errore nella creazione della partizione (`p` invece di `n`)
- [fix] nel comando di pacstrap c'era **iw** e non **iwd**
- [edit] powerlevel9k &rarr; powerlevel10k

## TODO -> verso la 1.6.1

- creare script che divida il markdown in file/cartelle in base al titolo

## TODO -> verso la 1.6.2

* creare stile apposito per percorsi di sistema come è stato fatto per codici inline e non
* inserire rfkill unblock/block nella sezione del net per recupero linea (unblock all/list all)
* rendere il documento più "impersonale"
* aggiungere plugin zsh
* aggiustare dipendenze neofetch, guardare da github

## TODO -> verso la 2.0
* guida dedicata per macbook
* guida lvm
* copertina documento da rifare, non è mia.

