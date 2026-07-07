---
layout: default
title: Railway Lineare
---

# Railway Lineare

Descrizione della sezione lineare del sistema MCPD.

# Railway Lineare a Condensatori Switchati

## Funzione
La Railway lineare è il sistema che:
- trasporta il plasma estratto dalla tenaglia,
- lo accelera progressivamente,
- lo mantiene centrato,
- prepara il flusso per lo stadio ciclotrone + RF.

È la “spina dorsale” del MCPD.

---

## Struttura

La Railway è composta da una sequenza di segmenti, ognuno formato da:

- Coppia di rotaie elettrostatiche
- Condensatore dedicato (Cᵢ)
- Switch elettronico (Sᵢ)
- Resistenza di shaping (Rᵢ)
- Sensori di corrente e stabilità

Ogni segmento è indipendente e controllato da una logica di timing.

---

## Principio di Funzionamento

### 1. Carica dei condensatori
Tutti i condensatori Cᵢ vengono caricati in parallelo alla tensione V₀.

### 2. Scarica sequenziale
Gli switch Sᵢ vengono attivati con un ritardo Δt programmato:
S1 → S2 → S3 → ... → Sn

Ogni scarica genera:
- un impulso elettrostatico,
- un gradiente di campo,
- un avanzamento dell’onda.

### 3. Onda viaggiante
La sequenza di scariche crea una **onda di campo che si muove lungo la Railway**.

Il plasma viene:
- agganciato,
- accelerato,
- centrato,
- stabilizzato.

### 4. Intermittenze
La logica di controllo introduce micro‑interruzioni programmabili:

- per evitare risonanze indesiderate,
- per modulare la velocità dell’onda,
- per sincronizzare la Railway con il gate RF/ciclotrone.

---

## Posizione nella catena MCPD

La Railway lineare si trova **tra:**

- **Punto 3:** Testa di tenaglia  
- **Punto 4:** Gate RF/Ciclotrone

Ed è essenziale per:
- trasferire il plasma dal toroide allo stadio energetico,
- evitare ritorni,
- garantire stabilità prima dell’ingresso nel ciclotrone.

---

## Nota tecnica

La Railway è continua:
- parte dalla tenaglia,
- attraversa tutto il tubo lineare,
- arriva fino alla camera di compressione MCPC,
- mantenendo centratura e stabilità del plasma in ogni stadio.

È uno degli elementi più innovativi dell’intero MCPD.
