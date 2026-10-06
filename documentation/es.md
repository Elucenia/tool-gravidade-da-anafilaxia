<!-- ELUCENIA technical documentation · gravidade-da-anafilaxia · es · no clinical/professional/rights approval -->

# Gravedad de la anafilaxia (Brown)

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/gravidade-da-anafilaxia)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Piel y tejido subcutáneo: eritema generalizado, urticaria, edema periorbitario o angioedema

`pele`

### Respiratorio: disnea, estridor, sibilancias, opresión torácica o de garganta

`resp`

### Gastrointestinal: náuseas, vómitos, dolor abdominal

`gi`

### Presíncope (mareo) o sudoración

`cardio`

### Hipoxemia (SpO₂ ≤ 92%) o cianosis

`hipoxia`

### Hipotensión (presión arterial sistólica \< 90 mmHg en adultos)

`hipotensao`

### Afectación neurológica: confusión, colapso, pérdida de conciencia o incontinencia

`neuro`

## Edición del método

Brown 2004: 3 grados, hallazgo más grave; SpO₂≤92/PAS\<90/neurológico

## Fórmula documentada

Grado por hallazgo más grave:

Grado 1 (leve): solo piel y subcutáneo.

Grado 2 (moderado): afectación respiratoria, cardiovascular o gastrointestinal.

Grado 3 (grave): hipoxemia (SpO₂ ≤ 92% o cianosis), hipotensión (PAS \< 90 mmHg) o compromiso neurológico.

## Límites y población

La clasificación Brown se estudió retrospectivamente en reacciones de hipersensibilidad sistémica en urgencias. La gravedad no es una definición diagnóstica completa ni una regla terapéutica aislada. Los umbrales numéricos y las definiciones de la versión deben comprobarse en el método completo; los signos y las condiciones de aplicación no pueden sustituirse únicamente por el total.

## Referencias

- [Brown SGA. Clinical features and severity grading of anaphylaxis. J Allergy Clin Immunol, 2004.](https://doi.org/10.1016/j.jaci.2004.04.029)

- [Cardona V et al. World Allergy Organization Anaphylaxis Guidance 2020. World Allergy Organ J, 2020.](https://doi.org/10.1016/j.waojou.2020.100472)

## Reproducir las pruebas técnicas

Ejecute node test.cjs en el directorio raíz de este repositorio para repetir los casos sintéticos registrados. Se conservan las entradas, los resultados esperados y las tolerancias originales. Las pruebas técnicas no constituyen validación clínica.

```sh
node test.cjs
```

tool.json contiene las fuentes, la edición y el alcance de la revisión. examples.json conserva las entradas y los resultados esperados de los casos sintéticos; results.json registra los resultados obtenidos.

[Ficha y referencias](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referencia](../examples.json) · [results.json](../results.json)

## Revisión y condiciones de uso

No se ha realizado una revisión clínica independiente.

Esta interfaz es una traducción de elaboración propia, no una edición oficial o certificada. No se han realizado la revisión clínica independiente, la revisión lingüística profesional ni la autorización de derechos de los instrumentos.

Resultado de la fórmula o clasificación. La interpretación, la conducta y la aplicabilidad dependen de la evaluación profesional y de la fuente seleccionada.

## Licencia y atribución

Apache-2.0 se aplica únicamente al código de ELUCENIA. Los derechos de los instrumentos, publicaciones, traducciones y datos permanecen en manos de sus respectivos titulares. Conserve LICENSE y NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Resultados documentados

La información siguiente conserva las salidas del método para ejemplos sintéticos. No constituye una validación clínica independiente.

### 1

Grado 1 (leve): reacción generalizada restringida a la piel y al tejido subcutáneo

Observe la progresión: los síntomas cutáneos pueden preceder la afectación de otros sistemas.


### 2

Grado 2 (moderada): afectación respiratoria, cardiovascular o gastrointestinal sin hipoxemia, hipotensión ni compromiso neurológico

Adrenalina intramuscular 0,01 mg/kg (máximo 0,5 mg en el adulto, 0,3 mg en el niño) en la cara anterolateral del muslo, sin demora; repetir en 5 a 15 minutos si es necesario.


### 3

Grado 2 (moderada): afectación respiratoria, cardiovascular o gastrointestinal sin hipoxemia, hipotensión ni compromiso neurológico

Adrenalina intramuscular 0,01 mg/kg (máximo 0,5 mg en el adulto, 0,3 mg en el niño) en la cara anterolateral del muslo, sin demora; repetir en 5 a 15 minutos si es necesario.


### 4

Grado 3 (grave): hipoxemia, hipotensión o compromiso neurológico

Adrenalina intramuscular 0,01 mg/kg (máximo 0,5 mg en el adulto, 0,3 mg en el niño) en la cara anterolateral del muslo, sin demora; repetir en 5 a 15 minutos si es necesario.

