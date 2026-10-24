# Contenuti Canva motivazionali — classici 1800–1960

Un flusso di lavoro per creare contenuti motivazionali per i social a partire da **citazioni autentiche** della letteratura classica (opere pubblicate tra il 1800 e il 1960). Il flusso usa Claude e Canva.

Il punto centrale è l'affidabilità. In rete circolano moltissime frasi attribuite a Dostoevskij, Nietzsche o Hugo che questi autori non hanno mai scritto. Per questo ogni citazione viene verificata sul testo dell'opera prima di finire in un post.

## Come funziona

1. **Ricerca e verifica.** La skill `citazioni-classiche` sceglie un tema (ad esempio luce, mattino, ricominciare). Poi seleziona le citazioni candidate e verifica ognuna su una fonte affidabile: Project Gutenberg, Liber Liber, Wikisource, Internet Archive o Wikiquote. Le citazioni senza riscontro vengono scartate.
2. **Documento.** I risultati vengono raccolti in un documento. Per ogni citazione ci sono il testo originale, la traduzione italiana, l'autore, l'opera, l'anno, il contesto, la fonte di verifica e lo stato dei diritti d'autore.
3. **Post Canva.** La citazione scelta diventa un post Instagram su Canva.

## Contenuto del repository

```
skill/
  citazioni-classiche/
    SKILL.md              # istruzioni della skill per Claude
    references/autori.md  # spunti di autori e opere per tema, attribuzioni false note
esempi-output/
  citazioni-luce-mattino-ricominciare.pdf   # esempio di documento generato
  post-instagram-motivazionale-milano.png   # esempio di post Canva
```

## Esempi di output

- **Documento delle citazioni:** [`esempi-output/citazioni-luce-mattino-ricominciare.pdf`](esempi-output/citazioni-luce-mattino-ricominciare.pdf). Tema "Luce, mattino e ricominciare" (24 ottobre 2026). Contiene 8 candidate: 7 verificate e 1 scartata perché senza fonte. Include anche una tabella di confronto per tono e meteo.
- **Post Canva:** "Post Instagram motivazionale per Milano" (1080×1440), con la citazione di Thoreau scelta nel documento. [Vedi il design su Canva](https://www.canva.com/d/1R6ex0p8HkwI-bP)

<p align="center">
  <img src="esempi-output/post-instagram-motivazionale-milano.png" alt="Post Instagram con una citazione di Thoreau da Walden su un'alba sopra Milano" width="420">
</p>

## Usare la skill

Copia la cartella `skill/citazioni-classiche` tra le skill di Claude, ad esempio caricandola come skill personalizzata su claude.ai. Poi chiedi qualcosa come:

> «Trovami 5 citazioni dai classici sul ricominciare per i miei post»

## Diritti d'autore

Le opere di autori morti da più di 70 anni sono di pubblico dominio in Italia e nell'UE. Per le opere ancora protette (ad esempio Camus), la skill riporta solo citazioni brevi con autore e titolo e le segnala come "opera protetta".
