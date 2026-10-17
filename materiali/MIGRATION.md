# Unificazione: registro delle decisioni

## Origine

- `BitBuilders-main(1).zip`: sito in `docs/`, loghi, sei foto del team, documentazione HCI e link al prototipo React.
- `sorteat_website-main.zip`: landing statica anteriore, HTML/CSS duplicati fra root e `docs/`, stessa coppia di loghi, link storico a un prototipo Figma, README con informazioni sulla realizzazione del sito.

## Interventi

1. Preso il sito BitBuilders come **unica base visiva**; preservati contenuti, navigazione per fasi e foto.
2. Rimossi i doppioni HTML/CSS e PDF identici senza perdere informazioni uniche. Il sito vive soltanto sotto `docs/`.
3. Integrato il link storico Figma nella raccolta risorse; è distinto dal prototipo React.
4. Normalizzati i nomi dei PDF; i file sono copiati byte-per-byte senza modificarne i contenuti.
5. Collegati tutti i materiali alle sei fasi dal sito e dal README.
6. Corretti title, heading accessibile, descrizione, link relativi, relazione fra valutazione condotta su StrandU e valutazione di Sorteat ricevuta da EcoDevs.
7. Inseriti dati di ricerca/usabilità supportati dalla documentazione e una nota sui limiti del prototipo.
8. Conservata e resa più chiara l'attribuzione: progetto del team BitBuilders, sito statico attribuito a Mariia nel README di origine.

## Fuori ambito

- Il codice high-fidelity React non è in nessuno dei due ZIP e non viene inventato o copiato da internet.
- Non sono inclusi moduli di consenso, file `.DS_Store`, placeholder `prova` o link vuoti.
- Non sono state verificate le autorizzazioni alla pubblicazione delle foto e dei documenti.
- Il nuovo progetto non è stato pubblicato o caricato automaticamente su GitHub.

## Criterio di manutenzione

Modifica `docs/index.html` e `docs/style.css` direttamente; questi sono i soli file del sito. Aggiungi nuovi PDF sotto `docs/pdf/` senza crearne copie nelle cartelle delle consegne. Mantieni il README e i link sincronizzati con il sito.
