Boolean - Web Development

2° Mese: JAVASCRIPT

Esercizio 4

Consegna: Scrivi un programma che stampi i numeri da 1 a 100, ma per i multipli di 3 stampi “Fizz” al posto del numero e per i multipli di 5 stampi Buzz. Per i numeri che sono sia multipli di 3 che di 5 stampi FizzBuzz.Prima di partire a scrivere codice poniamoci qualche domanda:
Come faccio a sapere se un numero è divisibile per? Abbiamo visto qualcosa di particolare che possiamo usare?

Numero push minimo: 4

Consigli del giorno:

    scriviamo sempre prima dei commenti in italiano per capire cosa vogliamo fare
    proviamo ad immaginare le operazioni che vogliamo far svolgere al nostro programma così come lo faremmo "a mano"

Buon lavoro e buon divertimento!

Ragionamento:

- Dichiaro una variabile "contatore" e la inizializzo all'interno di un ciclo che si ripete finche essa non arrivi a 100 incrementando di 1 ogni iterazione.
- inserisco un controllo (if) all'interno del ciclo che verifichi, in base al resto, quali numeri siano multipli di 3 o di 5.
- in base al risultato del controllo stampo il messaggio "Fizz" se "contatore % 3 = 0", stampo il messaggio "Buzz" se "contatore % 5 = 0", il messaggio "FizzBuzz" se "contatore % 3 = 0 && "contatore % 5 = 0" e, infine, stampo "contatore" in tutti gli altri casi.

