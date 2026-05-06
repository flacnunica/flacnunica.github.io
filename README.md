# Sito accademico di Fabio Angei

Questo repository contiene un sito accademico statico pensato per GitHub Pages. Non richiede build, installazioni o dipendenze: si modifica un file, si fa commit, e GitHub Pages pubblica direttamente.

## File da modificare

- `index.html`: testi visibili, progetti di ricerca, link e contatti.
- `styles.css`: colori, spaziatura, tipografia e layout.
- `assets/fabio-angei.png`: foto profilo usata nella versione corrente.
- `assets/cagliari-university.jpg`: immagine alternativa, al momento non usata.

## Pubblicazione con GitHub Pages

1. Crea un repository pubblico GitHub chiamato `flacnunica.github.io`.
2. Carica questi file nella radice del repository, oppure fai push da questa cartella locale.
3. Su GitHub apri `Settings` > `Pages`.
4. Imposta la sorgente su `Deploy from a branch`, branch `main`, folder `/root`.
5. Il sito sara' disponibile su `https://flacnunica.github.io/`.

Per un sito personale accademico, `flacnunica.github.io` e' la scelta piu pulita. Se invece usi un repository con un altro nome, GitHub Pages pubblichera' su `https://flacnunica.github.io/nome-repository/`.

## Dominio personalizzato

Compra solo il dominio, non l'hosting. L'hosting lo fornisce GitHub Pages.

Dopo l'acquisto del dominio:

1. Nel repository GitHub apri `Settings` > `Pages`.
2. Aggiungi il dominio personalizzato, per esempio `fabioangei.it` oppure `www.fabioangei.com`.
3. Nel pannello del registrar configura i DNS:
   - Dominio principale, per esempio `fabioangei.it`: crea record `A` verso gli IP di GitHub Pages.
   - Sottodominio `www`: crea un record `CNAME` verso `flacnunica.github.io`.
4. Torna in GitHub Pages e abilita `Enforce HTTPS` quando diventa disponibile.

Gli indirizzi IPv4 GitHub Pages indicati nella documentazione sono:

```text
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

## Opzioni dominio

Vedi `DOMAIN_OPTIONS.md` per le opzioni economiche e la raccomandazione.

## Indicizzazione Google

Il sito include:

- `robots.txt`, con link alla sitemap.
- `sitemap.xml`, con la homepage canonica.
- `rel="canonical"` su `https://fabioangei.it/`.
- Metadati Open Graph e Twitter.
- Dati strutturati JSON-LD per la pagina profilo.

In Google Search Console:

1. Crea o apri la proprieta' `fabioangei.it`.
2. Vai su `Sitemaps`.
3. Invia `sitemap.xml`.
4. Usa `Controllo URL` su `https://fabioangei.it/`.
5. Se la pagina e' idonea, clicca `Richiedi indicizzazione`.

## Credito immagine

Foto principale: trolvag, CC BY-SA 3.0, via Wikimedia Commons.
