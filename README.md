# compito-docker-compose
Docker-compose e Dockerfile con applicazione a tre livelli:

FE (html, javascript), BE (JAVA), DB (MySql).



FASE 1:

scrivere una pagina html che consuma un servizio rest (GET);

scrivere un applicazione spring boot che espone un endpoint rest (GET);

containerizzare BE e FE;

per il container FE utilizzare l'immagine FROM nginx;

generare un docker-compose che avvii entrambi i container.



FASE 2 (opzionale):

avviare un container mysql;

creare una tabella (libri [id,nome]);

collegare l'applicazione BE al database;

esporre due endpoint:

- scrittura di un libro;

- lettura di tutti i libri.

Il FE deve poter consumare i due endpoint appena generati.
