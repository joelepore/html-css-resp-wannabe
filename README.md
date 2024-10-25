## Descrizione:
Usando le CSS media queries, trasforma il repo ‘html-responsive-wannabe’ in una versione navigabile quando la larghezza dello schermo diventa:
- tablet: dai 768px in giù
- mobile: dai 480px in giù

L’html e il css presenti non possono essere modificati, possiamo solo aggiungere regole per modificare l’aspetto nelle due risoluzioni indicate.

### Bonus:
Sopra i 768px e fino ai 1160px il layout è un po’ troppo “rigido”! Come mai? :thinking_face:

Aggiungiamo una media query per sistemare il layout e non far comparire la scrollbar orizzontale.

### Consigli:
Apriamo le slide e usiamole come guida per il lavoro, aggiungiamo sempre solo un pezzettino alla volta.

Per poter vedere correttamente un sito responsive è necessaria l’aggiunta del tag:

<meta name=“viewport” content=“width=device-width, initial-scale=1.0”>

:warning: Fate attenzione: a volte l’inspector di Chrome può dare qualche problema con le mediaquery, controllate il lavoro anche con l’inspector di Firefox :laptop_parrot:

Buon lavoro e buon w/e :muscle:

## Svolgimento
1. Inserisco il tag meta:vp nell'head dell'html per far funzionare le media query
2. Con approccio desktop first, scrivo le media query per tablet e mobile, senza modificare html e css
3. Scrivo la media query bonus per sistemare il layout fino ai 1160 px