# GIT - Working with Remotes
* **I** repository sono versioni del tuo progetto che sono ospitate su internet
* **L**a programmazione con altri programmatori implica la gestione di questi rempository remoti e il push e il pull di dati

Fondamentale è saper **sincronizzare il nostro lavoro locale con un repository remoto**

*comandi principali:*

`git remote -v` --> visualizza i server remoti collegati al nostro repository
## Aggiungere o rimuovere un repository remoto
`git remote add <nome> <url>`
## Caricare il lavoro locale su repository remoto
`git push remote <ramo-locale>`
## Aggiornare la copia locale del repository, allinenadola con la versione remota
`git pull remote <ramo-locale>`
