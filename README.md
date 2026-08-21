# Public Shift Report CI

Repository pubblica dedicata esclusivamente all'esecuzione di GitHub Actions per la validazione di Shift Report.

## Regole

- Nessun dato operativo di Shift Report deve essere salvato o committato qui.
- Nessuna cartella `DB/`, export PDF, cache, backup, handle o snapshot operativa.
- Il codice della repository privata viene scaricato soltanto nel workspace effimero del runner GitHub Actions tramite credenziale read-only.
- Nessun artifact del workspace privato viene pubblicato o conservato.
- Il workspace della repository privata viene rimosso nello step finale `always()`.

## Source authority

La source authority resta `Sidious92/Shift-Report-New`.

Branch di validazione corrente: `stabilization/non-blocking-reports`.

Questa repository non è una copia, un fork o una source authority del progetto.
