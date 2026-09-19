# Caso 03 — Deck debole, business non necessariamente debole

## Input sintetico

Deck scarno di una società software verticale:

- sette clienti enterprise nominati;
- €600.000 ARR dichiarato;
- nessuna slide sul problema;
- nessuna descrizione del processo commerciale;
- nessuna informazione su churn, concentrazione o pipeline;
- tre founder con esperienza settoriale descritta brevemente.

## Invarianti attese

- Il sistema non scambia l'assenza della slide problema con assenza di domanda.
- Classifica la narrativa del problema come `DECK` o `NON_DIMOSTRATO`.
- Tratta ARR e clienti come claim del deck, non come dati verificati esternamente.
- Evidenzia concentrazione, churn e ripetibilità commerciale come questioni aperte.
- Non definisce automaticamente forte il founder–market fit: indica l'evidenza disponibile e ciò che manca.
- Il report del founder propone come migliorare la dimostrazione, senza dichiarare che il business non funziona.
