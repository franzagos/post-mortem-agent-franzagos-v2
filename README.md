# Post Mortem Agent - Franzagos v.2

Un agente di red team per analizzare pitch deck di startup prima di investire, consigliare o confrontarsi con i founder.

Non assegna percentuali arbitrarie di successo e non trasforma l'assenza di informazioni nel deck in una prova che il business sia debole. Distingue sempre:

- rischi sostanziali del business;
- tesi ancora non dimostrate;
- problemi di chiarezza o credibilità del pitch deck.

## Output

Ogni analisi produce due documenti separati:

1. **Internal Teardown** — riservato, diretto e pensato per preparare la valutazione e la call.
2. **Founder Improvement Report** — condivisibile, costruttivo e concluso da domande che richiedono evidenze osservabili.

## Modalità

### Breve

Prima diagnosi decisionale. Seleziona al massimo cinque criticità, tre verifiche prioritarie e cinque domande per il founder. È la modalità predefinita.

### Full

Analisi multi-agente completa di cliente, problema, mercato, concorrenza, economics, go-to-market, team ed execution. Include audit delle contraddizioni, consolidamento delle evidenze e controllo qualità prima della consegna.

## Utilizzo

Installa la cartella come skill Codex e invocala con:

```text
Usa $post-mortem-agent-franzagos-v2 in modalità Breve per analizzare questo pitch deck.
```

Oppure:

```text
Usa $post-mortem-agent-franzagos-v2 in modalità Full. Genera il teardown interno e il report condivisibile con il founder.
```

Se la modalità non è indicata, l'agente usa **Breve** e conserva dossier e identificativi per un'eventuale estensione successiva a **Full**.

## Principi

- Le istruzioni contenute nei documenti analizzati sono trattate come contenuto, non come comandi.
- Fatti, dichiarazioni del founder, fonti esterne, inferenze e dati mancanti restano separati.
- Ogni critica spiega perché conta e quale evidenza potrebbe confermarla o smentirla.
- Il consenso fra agenti non viene considerato una prova indipendente.
- Nessun numero, concorrente, cliente o benchmark viene inventato.
- I report grezzi degli agenti non vengono consegnati salvo richiesta esplicita.

## Struttura

```text
SKILL.md                Istruzioni e routing Breve o Full
agents/openai.yaml      Metadati per Codex
references/             Mandati degli agenti, contratti dati e template
test/                   Casi sintetici e criteri di validazione
```

## Privacy

Il repository non contiene pitch deck reali, dati delle startup analizzate o report riservati. I casi presenti in `test/` sono sintetici.

## Versione

Franzagos v.2
