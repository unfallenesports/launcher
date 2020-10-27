## Template con pulsante
<pre><code>title ^^ Nome evento ^^^
date ^^ Giorni/Mesi/Anno ^ Ore:Minuti ^^^
button ^^ Questo è il testo del pulsante ^ https://link.pulsante.com ^^^
description ^^
  Modificami! ^
  Usa il circonflesso per andare a capo. ^
  L'ultima riga non necessita di circonflesso.
</pre></code>

## Template senza pulsante
<pre><code>title ^^ Nome evento ^^^
date ^^ Giorni/Mesi/Anno ^ Ore:Minuti ^^^
description ^^
  Modificami! ^
  Usa il circonflesso per andare a capo. ^
  L'ultima riga non necessita di circonflesso.
</pre></code>

## Template vuoto
<pre><code>title ^^ ^^^
date ^^ ^ ^^^
description ^^ ^^^
</code></pre>

---

### ATTENZIONE: Il primo evento è il film.
### ATTENZIONE: poster.jpg NON deve essere eliminato.
### ATTENZIONE: poster.jpg deve essere categoricamente di formato JPEG.
### ATTENZIONE: poster.jpg deve avere dimensioni 150x225 pixel.

---

## Regole
<table>
  <tr>
    <th>^^^^</th>
    <td>Suddivide i blocchi di elementi</td>
  </tr>
  <tr>
    <th>^^^</th>
    <td>Suddivide gli elementi (variabili)</td>
  </tr>
  <tr>
    <th>^^</th>
    <td>Assegna il/i valore/i all'elemento</td>
  </tr>
  <tr>
    <th>^</th>
    <td>Suddivide i valori dell'elemento</td>
  </tr>
</table>
<table>
  <tr>
    <th>Elemento</th>
    <th>Descrizione</th>
    <th>Priorità</th>
  </tr>
  <tr>
    <td>title</td>
    <td>Elemento che contiene il nome dell'evento</td>
    <td>Obbligatorio</td>
  </tr>
  <tr>
    <td>date</td>
    <td>
      Elemento che contiene la data e l'ora dell'inizio dell'evento.<br>
      Necessita di 2 valori: la data e l'ora.<br>
      Esempio valore: <code>01/01/2010 ^ 12:00</code>
    </td>
    <td>Obbligatorio</td>
  </tr>
  <tr>
    <td>button</td>
    <td>
      Elemento che contiene le informazione del pulsante dell'evento.<br>
      Se questo elemento non viene dichiarato nel blocco, il pulsante non viene mostrato.<br>
      Necessita di 2 valori: il testo del pulsante e l'URL che verrà aperto al click.<br>
      Esempio valore: <code>Clicca qui ^ https://www.google.com</code>
    </td>
    <td>Opzionale</td>
  </tr>
  <tr>
    <td>description</td>
    <td>
      Elemento che contiene la descrizione dell'evento.<br>
      Il numero di valori può variare a partire da 1.<br>
      <code>^</code> può essere utilizzato per andare a capo
    </td>
    <td>Obbligatorio</td>
  </tr>
</table>
