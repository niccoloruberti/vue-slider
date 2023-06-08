CONSEGNA: Creare uno slider utilizzando Vue.

- Inserisco Vue nel codice Javascript salvando in una variabile la funzione createApp, presa dalla variabile globale Vue;
- Inizializzo un'instanza dell'applicazione Vue, invocando la funzione createApp;
- Invoco il metodo .mount() per connettere l'istanza al tag HTML con id #app e renderizzare l'app;
- Creo all'interno del data una variabile index che mi permette di far cambiare l'immagine principale;
- inserisco nel tag img un v-bind che prenda l'immagine in base al valore dell'indice;
- Creo due funzioni(prevImage e nextImage) per far incrementare o decrementare il valore di index per poter far comparire le diverse immagini e relative info come titolo e testo;
- aggiungo un evento di tipo click ai div con classe prev e next per chiamare le funzioni descritte al punto precedente;
- inserisco all'interno del div con classe "text" i dati corretti con il metodo dei baffi sempre andando a selezionare il valore dall'array tramite l'indice;