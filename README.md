Clone dell'app Spotify usando React-redux per la gestione delle funzioni principali Tra i componenti aggiuntivi sono stati usati l'API di Spotify, l'API Context e l'add-on "Styled-components" che permette di scrivere il CSS di elemento come sua diretta funzione. 

L'app presenta una schermata iniziale di Login come previsto dalla piattaforma Spotify Web Developer e si apre solo su indirizo localhost:3000, altre porte non funzionano perché non previsto.

Dopo aver effettuato il login, per far funzionare l'app bisogna aprire l'APP uffciale di Spotify sul PC o in alternativa un'istanza di Spotify Web e far partire una canzone qualsiasi.
Solo dopo aver fatto questa procedura, il player su localhost sará in grado di leggere lo stato della canzone in riproduzione e trasferirlo nel suo apposito slot. Sará inoltre possibile navigare tra le playlist e scegliere una qualsiasi canzone, che verrá riprodotta per intero.

NB: Se non viene prima lanciata una canzone su Spotify/Spotify Web, al clic di una canzone presente sulla pagina localhost apparirá una pagina di errore a seconda del proprio abbonamento a Spotify:
1) Spotify Premium: error 404 sulla fetch dell'API ufficiale.
2) Spotify Free: error 403 per mancati permessi per l'accesso all'API.

