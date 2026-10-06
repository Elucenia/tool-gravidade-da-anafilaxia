<!-- ELUCENIA technical documentation · gravidade-da-anafilaxia · it · no clinical/professional/rights approval -->

# Gravità dell’anafilassi (Brown)

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/gravidade-da-anafilaxia)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Cute e sottocute: eritema generalizzato, orticaria, edema periorbitario o angioedema

`pele`

### Respiratorio: dispnea, stridore, sibili, costrizione toracica o alla gola

`resp`

### Gastrointestinale: nausea, vomito, dolore addominale

`gi`

### Presincope (capogiro) o sudorazione

`cardio`

### Ipossiemia (SpO₂ ≤ 92%) o cianosi

`hipoxia`

### Ipotensione (pressione arteriosa sistolica \< 90 mmHg nell’adulto)

`hipotensao`

### Compromissione neurologica: confusione, collasso, perdita di coscienza o incontinenza

`neuro`

## Edizione del metodo

Brown 2004: 3 gradi, reperto più grave; SpO₂≤92/PAS\<90/neurologico

## Formula documentata

Grado definito dal reperto più grave:

Grado 1 (lieve): solo cute e sottocute.

Grado 2 (moderato): coinvolgimento respiratorio, cardiovascolare o gastrointestinale.

Grado 3 (grave): ipossiemia (SpO₂ ≤ 92% o cianosi), ipotensione (PAS \< 90 mmHg) o compromissione neurologica.

## Limiti e popolazione

La classificazione Brown è stata studiata retrospettivamente nelle reazioni di ipersensibilità sistemica in pronto soccorso. La gravità non è una definizione diagnostica completa né una regola terapeutica autonoma. Soglie numeriche e definizioni della versione devono essere verificate nel metodo completo; segni e condizioni di applicazione non possono essere sostituiti dal solo totale.

## Riferimenti

- [Brown SGA. Clinical features and severity grading of anaphylaxis. J Allergy Clin Immunol, 2004.](https://doi.org/10.1016/j.jaci.2004.04.029)

- [Cardona V et al. World Allergy Organization Anaphylaxis Guidance 2020. World Allergy Organ J, 2020.](https://doi.org/10.1016/j.waojou.2020.100472)

## Riprodurre i test tecnici

Esegua node test.cjs nella cartella principale di questo repository per ripetere i casi sintetici registrati. Gli input, i risultati attesi e le tolleranze originali sono conservati. I test tecnici non costituiscono validazione clinica.

```sh
node test.cjs
```

tool.json contiene le fonti, l’edizione e l’ambito della revisione. examples.json conserva gli input e i risultati attesi dei casi sintetici; results.json registra i risultati ottenuti.

[Scheda e riferimenti](../tool.json) · [Codice JavaScript](../calculator.js) · [Casi di riferimento](../examples.json) · [results.json](../results.json)

## Revisione e condizioni d’uso

Non è stata effettuata una revisione clinica indipendente.

Questa interfaccia è una traduzione realizzata dagli autori, non un’edizione ufficiale o certificata. Non sono state eseguite la revisione clinica indipendente, la revisione linguistica professionale né la verifica delle autorizzazioni relative ai diritti sugli strumenti.

Risultato della formula o classificazione. Interpretazione, condotta e applicabilità dipendono dalla valutazione professionale e dalla fonte selezionata.

## Licenza e attribuzione

Apache-2.0 si applica solo al codice di ELUCENIA. I diritti su strumenti, pubblicazioni, traduzioni e dati restano ai rispettivi titolari. Conservi LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Risultati documentati

Le informazioni seguenti conservano gli output del metodo per esempi sintetici. Non costituiscono una validazione clinica indipendente.

### 1

Grado 1 (lieve): reazione generalizzata limitata alla cute e al sottocutaneo

Osservare la progressione: i sintomi cutanei possono precedere il coinvolgimento di altri sistemi.


### 2

Grado 2 (moderato): interessamento respiratorio, cardiovascolare o gastrointestinale senza ipossiemia, ipotensione o compromissione neurologica

Adrenalina intramuscolare 0,01 mg/kg (massimo 0,5 mg nell’adulto, 0,3 mg nel bambino) nella faccia anterolaterale della coscia, senza ritardo; ripetere in 5 a 15 minuti se necessario.


### 3

Grado 2 (moderato): interessamento respiratorio, cardiovascolare o gastrointestinale senza ipossiemia, ipotensione o compromissione neurologica

Adrenalina intramuscolare 0,01 mg/kg (massimo 0,5 mg nell’adulto, 0,3 mg nel bambino) nella faccia anterolaterale della coscia, senza ritardo; ripetere in 5 a 15 minuti se necessario.


### 4

Grado 3 (grave): ipossiemia, ipotensione o compromissione neurologica

Adrenalina intramuscolare 0,01 mg/kg (massimo 0,5 mg nell’adulto, 0,3 mg nel bambino) nella faccia anterolaterale della coscia, senza ritardo; ripetere in 5 a 15 minuti se necessario.

