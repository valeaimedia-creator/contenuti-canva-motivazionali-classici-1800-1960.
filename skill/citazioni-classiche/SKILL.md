---
name: citazioni-classiche
description: Cerca nei libri classici pubblicati tra il 1800 e il 1960 citazioni motivazionali sulla vita e sull'essere umano, le verifica sulle fonti e le raccoglie in un documento con testo originale, traduzione italiana, autore, opera e contesto. Usala ogni volta che l'utente chiede citazioni, frasi, aforismi o passaggi ispirazionali/motivazionali tratti da romanzi, saggi, lettere o poesie dell'Ottocento e del primo Novecento, anche se non nomina date o "classici" (es. "frasi motivazionali da grandi scrittori", "una citazione di Tolstoj sul coraggio", "aforismi letterari sulla resilienza per i miei post").
---

# Citazioni classiche (1800–1960)

Lo scopo è dare all'utente citazioni **autentiche** e **utilizzabili** tratte dalla letteratura del 1800–1960, che parlino della vita, del senso, del coraggio, della fatica, dell'amore, della condizione umana — con un tono che possa motivare o far riflettere.

Il valore di questa skill sta tutto nell'affidabilità: il web è pieno di frasi attribuite a Dostoevskij, Hemingway o Nietzsche che non hanno mai scritto. Una citazione falsa usata in un post o in un discorso fa fare brutta figura all'utente. Per questo ogni citazione va verificata prima di essere consegnata.

## Impostazioni predefinite

- **Quante**: 5–7 citazioni, salvo diversa richiesta.
- **Lingua**: testo originale + traduzione italiana. Se l'opera è italiana, basta l'originale.
- **Formato**: un documento (vedi "Consegna").
- **Periodo**: opere pubblicate tra il 1800 e il 1960. La data che conta è la prima pubblicazione dell'opera (per lettere e diari, la data di scrittura).

## Flusso di lavoro

### 1. Capire cosa serve
Dalla richiesta ricava: tema (es. resilienza, ricominciare, solitudine, scopo, gentilezza), eventuale uso (post social, discorso, regalo, studio), eventuali autori o paesi preferiti. Se il tema manca, scegli un ventaglio vario su "vita ed essere umano" invece di chiedere: è meglio consegnare e lasciare che l'utente raffini.

Se l'utente porta una citazione specifica e chiede "altre simili", verifica prima quella, poi cerca altre citazioni **sullo stesso tema** (motivazione, senso della vita, condizione umana) **di autori diversi**: "simili" si riferisce al contenuto, non all'autore. Resta sullo stesso autore solo se l'utente lo chiede esplicitamente ("altre di Dostoevskij").

### 2. Scegliere i candidati
Parti da autori e opere adatti al tema — `references/autori.md` ha uno spunto per temi, ma non limitarti a quello. Punta alla varietà: paesi diversi, generi diversi (romanzo, saggio, lettera, poesia), qualche nome meno abusato accanto ai grandi. Evita le 3–4 frasi che girano ovunque, a meno che l'utente non le chieda: chi cerca citazioni nei classici di solito vuole scoprire qualcosa.

### 3. Verificare ogni citazione (passo obbligato)
Per ogni candidata cerca riscontro sul web prima di includerla. Fonti buone, in ordine:
1. Testo integrale dell'opera: Project Gutenberg, Liber Liber, Wikisource, Internet Archive.
2. Wikiquote (controlla le sezioni "attribuite" / "misattributed" / "disputed": servono a escludere).
3. Edizioni critiche o articoli che citano capitolo/pagina.

Sii efficiente: per ogni citazione basta **una** fonte affidabile che mostri il passo nell'opera (meglio due solo se la prima è dubbia). Molti siti (Wikisource, Gutenberg via shell, alcune Wikiquote) possono essere bloccati o non caricarsi: se una pagina non si apre al primo tentativo, non riprovarla con altri metodi — passa subito alla fonte successiva (Liber Liber, Internet Archive, Standard Ebooks, siti di testi integrali, edizioni accademiche). Se dopo 3–4 tentativi una citazione non si lascia verificare, scartala e scegline un'altra: ci sono molte citazioni valide, non vale la pena insistere su una sola. L'obiettivo è consegnare in pochi minuti, non esaurire il web.

Regole:
- Se trovi il passo nel testo dell'opera, annota capitolo/parte/lettera. ✅ Verificata.
- Se è solo su siti di aforismi senza fonte, o Wikiquote la dà come attribuita/falsa, **scartala** e scegline un'altra. Se l'utente aveva chiesto proprio quella frase, diglielo chiaramente: "questa frase non risulta in nessuna opera di X; la versione autentica più vicina è…".
- Se il passo esiste ma la versione popolare è parafrasata, riporta la versione autentica e segnala la differenza.
- Non inventare mai capitolo o pagina: se non li hai trovati, scrivi solo l'opera.

### 4. Tradurre
- Se esiste una traduzione italiana di pubblico dominio trovata durante la verifica, puoi usarla citandola.
- Altrimenti traduci tu e indica "traduzione libera". Una traduzione fedele ma scorrevole: la citazione deve restare leggibile e incisiva in italiano.
- Per opere russe, tedesche ecc. l'"originale" è nella lingua originale; se riesci a verificarlo solo in una traduzione inglese, dillo.

### 5. Diritti d'autore (breve ma importante)
Opere di autori morti da più di 70 anni sono di pubblico dominio in Italia/UE: si possono usare liberamente. Per autori morti da meno di 70 anni (es. Hemingway, Camus, Steinbeck, Montale) l'opera è ancora protetta: una citazione breve con autore e titolo è normalmente ammessa, ma tienila corta (una o due frasi) e segnala nel documento "opera ancora protetta da diritto d'autore" — utile se l'utente vuole usarla commercialmente (libri, merchandise, pubblicità).

### 6. Scrivere il contesto
Per ogni citazione 1–2 frasi: chi parla, in che momento dell'opera, perché la frase pesa. Il contesto è ciò che distingue questa raccolta da un sito di aforismi, e spesso cambia il senso (una frase "motivazionale" può essere detta da un personaggio disperato o ironico: se è così, dillo).

## Consegna

Crea un **documento** (il tipo Docs/documento disponibile nella sessione; se non c'è, un file .docx tramite la skill docx). Struttura:

```
# Citazioni dai classici — <tema>
<data>

Breve introduzione (2–3 frasi): tema e criterio di scelta.

## 1. «<citazione in italiano>»
> <testo originale>
**<Autore>**, *<Opera>* (<anno>), <capitolo/parte se verificato>
Traduzione: <libera / di chi>
Contesto: <1–2 frasi>
Stato: ✅ verificata su <fonte> · <pubblico dominio | opera protetta>

## 2. …

## Fonti
- [<titolo>](<url>) per ogni verifica
```

Nella risposta in chat basta una riga che dica cosa contiene il documento e, se hai scartato citazioni false che l'utente aveva in mente, una riga su quelle.

## Esempio di voce

**Richiesta**: "citazioni sul ricominciare dopo un fallimento"

> ## 1. «Bisogna avere ancora un caos dentro di sé per partorire una stella danzante.»
> > Man muss noch Chaos in sich haben, um einen tanzenden Stern gebären zu können.
> **Friedrich Nietzsche**, *Così parlò Zarathustra* (1883), Prologo, §5
> Traduzione: libera
> Contesto: Zarathustra parla alla folla dell'"ultimo uomo", comodo e senza slanci; il disordine interiore è presentato come condizione per creare qualcosa di nuovo.
> Stato: ✅ verificata su Projekt Gutenberg-DE · pubblico dominio
