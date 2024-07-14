Ciao ragazzi,
esercizio di oggi: *Social Posts*
nome repo: **js-social-posts
Descrizione**
Ricreiamo un feed social aggiungendo al layout di base fornito, il nostro script JS in cui:
*Milestone 1* - Prendendo come riferimento il layout di esempio presente nell'html, stampiamo i post del nostro feed attraverso javascript.
*Milestone 2* - Se clicchiamo sul tasto "Mi Piace" cambiamo il colore al testo del bottone e incrementiamo il counter dei likes relativo.
Salviamo in un secondo array gli id dei post ai quali abbiamo messo il like.
Numero push minimo: 10/12
P.S. Occhio al nome della repo! Ricordatevi che deve essere js-social-posts!
***BONUS*
1. Formattare le date in formato italiano (gg/mm/aaaa)
2. Gestire l'assenza dell'immagine profilo con un elemento di fallback che contiene le iniziali dell'utente (es. Luca Formicola > LF).
3. Al click su un pulsante "Mi Piace" di un post, se abbiamo già cliccato dobbiamo decrementare il contatore e cambiare il colore del bottone.
*Consigli del giorno:*
Ragioniamo come sempre a step.
Prima scriviamo nei commenti la logica in italiano e poi traduciamo in codice.
console.log() è nostro amico.
Quando un pezzo di codice funziona, chiediamoci se possiamo scomporlo in funzioni più piccole.
Buon lavoro!

soluzione
1.recupero tramite id la variabile dentro cui stamperò i post 
2.creo un ciclo
3.applico la destrutturazione per assegnare ad una variabile i le proprietà degli oggetti che mi servono
concateno con il metodo innerhtml la variabile dentro cui stamperò i post con il codice html
4.sostituisco gli elementi che saranno visibili nel post con le proprieta degli oggetti dell'array
5.recupero il tasto mi piace tramite id e lo assegno ad una variabile
6.creo un array che conterrà gli id dei post a cui ho messo mi piace
7.creo un evento click
8.creo una condizione che controlla se l'id non è presente nel nuovo array
9.se l'id non è presente allora lo pusho dentro l'array
10.assegno alla variabile che contiene il tasto mi piace la classe "like-button--liked"
11.aumento il contatore di 1
