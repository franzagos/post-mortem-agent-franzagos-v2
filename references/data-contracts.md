# Contratti dati

## Tipi di evidenza

- `D` — contenuto esplicito del materiale, con riferimento disponibile: file/slide, file/pagina, file/sezione, input/paragrafo o input/bullet.
- `F` — fonte esterna verificata, con URL e data.
- `I` — inferenza analitica, con ragionamento.
- `M` — informazione mancante.
- `R` — risposta successiva del founder, con data.

Un'inferenza non può essere promossa a fatto senza nuova evidenza.

## Identificatori

- Claim: `C001`, `C002`…
- Assunzione: `A001`, `A002`…
- Evidenza: `E001`, `E002`…
- Rischio provvisorio dell'agente: `[agente]-R[progressivo]`, per esempio `A04-R01`.
- Rischio canonico dopo il consolidamento: `R001`, `R002`…
- Contraddizione: `X001`, `X002`…
- Miglioramento: `M001`, `M002`…
- Domanda: `Q001`, `Q002`…

Gli identificatori restano stabili nelle revisioni successive.

Gli Agenti 02–07 usano soltanto ID provvisori con namespace. L'Agente 08 assegna gli ID canonici e produce una tabella di mapping. Questo evita collisioni durante l'esecuzione parallela.

## Registro dei claim

| ID | Claim | Area | Tipo evidenza | Riferimento | Stato | Confidenza | Note |
|---|---|---|---|---|---|---|---|

`Stato` ∈ {supportato, parzialmente supportato, non supportato, contraddetto, non verificabile}.

## Registro delle assunzioni

| ID | Assunzione | Origine | Criticità se falsa | Evidenza disponibile | Stato |
|---|---|---|---|---|---|

`Stato` ∈ {validata, parzialmente validata, non validata, falsificata, ignota}.

## Registro dei rischi

| ID | Rischio | Categoria | Collegamenti | Evidenza | Gravità | Urgenza | Reversibilità | Confidenza |
|---|---|---|---|---|---|---|---|---|

Non calcolare un punteggio numerico unico. Usa:

- Gravità: bloccante, alta, media, bassa.
- Urgenza: ora, prima del prossimo investimento, da monitorare.
- Reversibilità: alta, parziale, bassa.
- Confidenza: alta, media, bassa.

La gravità descrive il danno potenziale; la confidenza descrive la solidità della valutazione. Non confonderle.

## Classificazione della criticità

Ogni criticità finale deve avere un solo tipo primario:

- `BUSINESS` — fragilità sostanziale supportata da evidenze.
- `NON_DIMOSTRATO` — potrebbe essere solida, ma il deck non lo prova.
- `DECK` — problema di comunicazione, struttura o chiarezza.

Se coinvolge più tipi, indica quelli secondari ma non cancellare la distinzione.

## Domande finali

| ID | Priorità | Domanda | Perché cambia il giudizio | Evidenza richiesta | Rischi collegati |
|---|---|---|---|---|---|

Una domanda è ammessa solo se la risposta può confermare, ridurre, riclassificare o eliminare almeno un rischio materiale.

## Calcoli

Ogni calcolo riporta:

- formula;
- valori di origine e relativi riferimenti;
- compatibilità di periodo, segmento, valuta e definizione;
- stato `calcolabile`, `indicativo` o `non calcolabile`;
- limite interpretativo.

Un risultato indicativo non può essere descritto come dato certo.
