# Progetto-javascript-advanced-AntonioCuoco
## Progetto per incentivare la lettura di libri creato utilizzando le api openLibrary con javascript 
link al sito: https://progetto-antoniocuoco-javascript.netlify.app/

## Spiegazione progetto
![Cattura](https://user-images.githubusercontent.com/30431200/215320551-55498b28-54b8-4954-bf21-22bae3395795.PNG)

Il progetto prevede che l'input di tipo search messo nella hero section prenda il valore da noi inserito in input,in questo caso sarà il genere dei libri e ci restituisce tramite una chiamata api tutti i libri del genere che abbiamo scelto, per esempio se scriviamo fantasy, la chiamata api che verrà effettuata sarà di questo tipo: 'https://openlibrary.org/subjects/fantasy.json' e restituira la cover, il titolo e gli autori/l'autore di tutti i libri sempre sfruttando la chiamata api al link dal quale prenderà i valori e successivamente tramite il bottone leggi la descrizione si andrà a recuperare la descrizione tramite una seconda chiamata api.
