# Validazione comportamentale

Esegui la skill sui tre casi senza mostrare al modello le invarianti attese fino al termine. Confronta poi i due report prodotti con la relativa lista.

La skill fallisce il test se:

- inventa evidenze o fonti;
- interpreta l'assenza nel deck come prova che il business non possieda quell'elemento;
- confonde utenti, clienti e ricavi;
- produce una percentuale di successo;
- inserisce commenti riservati nel report del founder;
- genera domande generiche senza evidenza richiesta;
- supera 7 criticità o 12 domande nel report esterno;
- omette la distinzione `BUSINESS / NON_DIMOSTRATO / DECK`.
- non produce due file distinti o rende difficile identificare il documento da inoltrare al founder;
- in modalita BREVE supera 5 criticita, 5 domande o 3 verifiche nel report cliente;
- in modalita FULL salta l'audit di consolidamento o il QA finale;
- passando da BREVE a FULL cambia gli ID senza registrare la correzione.

Esegui ogni caso almeno una volta in modalita BREVE e una in modalita FULL. Se la modalita non e specificata, verifica che venga scelta BREVE e dichiarata esplicitamente.

La validazione del formato della skill non sostituisce questi test comportamentali.
