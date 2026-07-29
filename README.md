# 📖 Grimorio D&D 5E

Basta passarsi l'unico manuale al tavolo: tutti gli incantesimi della 5ª edizione, cercabili all'istante, da qualsiasi telefono, tablet o PC.

🔗 **[Apri il Grimorio](https://kattafa.github.io/Grimorio5e/)**

---

## Cosa contiene

Un elenco completo degli incantesimi del *System Reference Document 5.1*, con per ognuno:

- Nome e scuola di magia
- Livello
- Classi che possono lanciarlo
- Tempo di lancio (e se è un rituale)
- Gittata
- Componenti richiesti
- Durata (e se richiede concentrazione)
- Tiro salvezza richiesto (se presente)
- Descrizione completa

## Come si usa

### 🔍 Cerca un incantesimo
Scrivi nella barra di ricerca in alto. Puoi:
- Cercare per nome: `palla di fuoco`
- Cercare per classe: `mago`
- Cercare per livello: `3°`
- Cercare per scuola: `necromanzia`
- **Combinare più termini con uno spazio** — la ricerca mostra solo le righe che li contengono *tutti*. Esempio: `mago 3° fuoco` trova gli incantesimi di 3° livello del mago che contengono "fuoco".

> La ricerca non guarda dentro il testo della descrizione, solo nei campi tecnici (nome, livello, classe, tempo, gittata, componenti, durata, TS). Così eviti risultati "sporchi" causati da parole citate a caso nel testo.

### 🎛️ Filtri
- **Mostra solo i rituali** — spunta la casella per vedere solo gli incantesimi lanciabili come rituale.
- **Classe** — scegli una classe dal menu a tendina per vedere solo i suoi incantesimi.

I filtri si combinano anche con la ricerca testuale.

### ↕️ Ordina la tabella (da PC/tablet)
Clicca su un'intestazione di colonna (es. "Livello" o "Nome") per ordinare la tabella; clicca di nuovo per invertire l'ordine (▲/▼).

> Su schermi molto stretti (telefono) la tabella diventa una serie di schede verticali per restare leggibile: in quella modalità l'ordinamento per colonna non è disponibile, ma ricerca e filtri funzionano comunque normalmente.

### 📱 Da mobile
Tocca la barra di ricerca e digita: il grimorio si aggiorna in tempo reale a ogni lettera. Ogni incantesimo appare come una scheda con tutte le informazioni etichettate.

## Aggiornare i dati

Gli incantesimi sono tutti dentro il file `index.html`, in un array JavaScript chiamato `spells`. Per aggiungere o correggere un incantesimo:

1. Apri il file con un editor di testo
2. Trova la riga dell'incantesimo (o aggiungine una nuova) nel formato:
   ```
   ["Nome", "Livello° Scuola", "Classe1, Classe2", "Tempo di lancio", "Gittata", "Componenti", "Durata", "TS o Nessuno", "Descrizione"],
   ```
3. Salva e ricarica il file su GitHub (Add file → Upload files → Commit)

## Licenza e crediti

Questo strumento include materiale tratto dal *System Reference Document 5.1* ("SRD 5.1") di Wizards of the Coast LLC, disponibile su [dnd.wizards.com](https://dnd.wizards.com/resources/systems-reference-document), distribuito con licenza [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/legalcode).

---

*Buone avventure, e che il d20 sia sempre con voi.* 🎲
