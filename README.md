# I report di CielOS

Qui CielOS mette da solo i report che produce: il collaudo notturno della VM, le segnalazioni di
«cielos segnala», la visita giornaliera del Medico. Non si scrive a mano: `cielreport` aggiunge il
file appena c'è, con un commit per report. L'elenco per i programmi è in [`indice.json`](indice.json).

**2** report · collaudo: 0 · segnalazioni: 0 · visite del PC: 2.

Ogni report comincia con una scheda (tipo, macchina, data, titolo, esito, versione). Dentro non ci
sono il nome dell'utente, il nome vero del PC né gli indirizzi MAC.

## Come si leggono

Dalla cartella dei file, da `cielreport elenco`, oppure su GitHub. I report più vecchi restano in
`rapporti/AAAA/MM/`: niente si cancella da solo. Il progetto è in
[Surgo-1/CielOS](https://github.com/Surgo-1/CielOS).

## Ultimi report

| Quando | Tipo | Macchina | Esito | Report |
|---|---|---|---|---|
| 21/10/2026 23:38 | visita | pc | 2 consigli | [apri](rapporti/2026/10/21-2338-visita-pc.md) |
| 21/10/2026 23:34 | visita | pc | 2 consigli | [apri](rapporti/2026/10/21-2334-visita-pc.md) |

## Chi li pubblica

`cielreport` (in `bin/`), con il permesso di GitHub della macchina: se `gh` non è collegato il report
resta sul PC e non si perde. La pubblicazione automatica si spegne con
`cielreport configura --spegni`.
