# Verifica Informatica
## Bozzi Francesco 5a-i 29/10/2026
1. index.html
2. programmazione.html
3. prenota.html
4. contatti.html


## COMANDI USATI

1. git init | serve a far creare la cartella .git all'interno della directory che si vuole usare come repository
2. git config user.name | si configura il nome
3. git config user.email | si configura l'email
4. git add . | aggiunge i file modificati in una memoria locale
5. git commit -m "testoascelta" | il commit prende i file modificati e gli associa un commento a scelta e lo aggiunge in questo caso al branch main
6. gh auth login | permette di accedere col proprio account github nella quale verra caricata la repository
7. gh repo create nomerepo --public --source=. --remote=origin --push | crea una repository nella account github dove in nomerepo si mette il nome della repo che si vuole creare in questo caso la imposta come pubblica 
8. git push | carica il commit nella repository online