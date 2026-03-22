# Agent Rules — birthdayparadox

> Il paradosso del compleanno è un risultato controintuitivo della probabilità:     in un gruppo di appena 23 persone, c'è oltre il 50% di probabilità che almeno due persone condividano lo stesso giorno di compleanno.

## Codice
- Nomi descrittivi, no abbreviazioni crittiche
- Docstring su ogni funzione pubblica
- Type hints in Python, Javadoc in Java
- Nessun magic number senza costante nominata

## Testing
- Unit test obbligatori per ogni funzione pubblica
- Nessuna modifica senza test di regressione

## Sicurezza
- Zero segreti nel codice — usa variabili d'ambiente
- Nessuna chiave API, password o token in chiaro

## Git
- Conventional Commits: feat:, fix:, docs:, refactor:, test:, chore:
- Commit atomici, un concetto per commit
- Nessun file generato o .env nel repository

## Lingua
- Commenti e docstring in italiano
- Messaggi di commit in inglese
