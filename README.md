
1. Lanciare ambiente docker con Laravel sail
2. lanciare il comando composer update
3. lanciare comando php artisan migrate
4. Tutti gli utenti hanno come password: password
5. Nel seeder UserSeeder c'è la lista con gli utenti e i relativi ruoli
6. Usare l'endpoint auth/login con i dati di email e password dell'utente corrispondente per ricevere il BearerToken da inserire nel header delle richieste POST successive

invito workspace postman per vedere endpoint e funzionamento:
https://app.getpostman.com/join-team?invite_code=883c890642b32fb5d804f5fb7ee9dc4d&target_code=472b61fb7c7fac5e6101bf93b87a2850




Note:

Non avendo sviluppato nessuna UI, gli endpoint API per la modifica dei dati prevedono una ricerca del progetto e task per nome. Dove si volesse prevedere una UI la ricerca andrebbe fatta per ID.
npm install opzionale (installa solo axios e vite che non sono usati in questo progetto)

Tempo di coding: 6:40 ore

Lorenzo Bernini
