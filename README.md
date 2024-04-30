# Esercizio 1
Sviluppare un'applicazione Spring che rappresenta una calcolatrice che conserva una lista di numeri interi e ti permette di eseguire le quattro operazioni fondamentali su questi numeri in sequenza. 
Il programma deve rispettare le seguenti caratteristiche:
- Una richiesta PUT con formato "?number={n}" aggiunge il numero "n" alla lista
- Una richiesta GET che ritorna la lista di numeri inseriti fin'ora
- Una richiesta DELETE all'endpoint "/clear" svuota la lista
- Una richiesta GET all'endpoint "/sum" ritorna la somma dei numeri in lista
- Una richiesta GET all'endpoint "/sub" ritorna la sottrazione di tutti i numeri in lista
- Una richiesta GET all'endpoint "/prod" ritorna il prodotto di tutti i numeri in lista
- Una richiesta GET all'endpoint "/div" ritorna il quoziente di tutti i numeri in lista come double
  
