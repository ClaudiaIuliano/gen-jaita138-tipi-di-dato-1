## Todo

Definire in file di testo o pdf o excel gli attributi con relativi tipi di dato per le seguenti realta'

### Database 1

**Gestione di una Biblioteca**:

- Libri
- Membri
- Prestiti

### Database 2

**Catalogo di un Ristorante**:

- Piatti
- Ingredienti
- Clienti

### Database 3

**Catalogo di un Negozio di Fiori**

- Fiori
- Fornitori
- Clienti





Gestione biblioteca:


| Libri   | Java    | Sql     |
| ------- | ------- | ------- |
| -Titolo | stringa | varchar |
| -Autore | stringa | varchar |
| -Genere | stringa | varchar |
| -Anno   | Int     | time    |
| -ISBN   | Int     | Int     |
| -prezzo | flat    | decimal |
|         |         |         |

| Membro        | Java   | Sql     |
| ------------- | ------ | ------- |
| -Nome         | string | varchar |
| -data nascita | date   | date    |
| -e-mail       | string | varchar |
| -telefono     | string | varchar |
| -indirizzo    | string | varchar |

| Prestiti              | java   | Sql     |
| --------------------- | ------ | ------- |
| data inizio prestito: | date   | date    |
| data fine             | date   | date    |
| utente                | string | varchar |

Ristorante:

| Piatti       | java   | sql     |
| ------------ | ------ | ------- |
| -nome piatto | string | varchar |
| -ingredienti | string | varchar |
| -prezzo      | flat   | decimal |

| Cliente   | java   | sql     |
| --------- | ------ | ------- |
| -nome     | string | varchar |
| -allergie | string | varchar |
|           |        |         |

Catalogo negozio di fiori:


| Fiori       | java   | sql     |
| ----------- | ------ | ------- |
| -nome fiore | string | varchar |
| -colore     | string | varchar |
| -prezzo     | flat   | decimal |

| Clienti    | java   | sql     |
| ---------- | ------ | ------- |
| -nome      | string | varchar |
| -telefono  | string | varchar |
| -email     | string | varchar |
| -indirizzo | string | varchar |

| Fornitori          | java   | sql     |
| ------------------ | ------ | ------- |
| -nome fornitore    | string | varchar |
| -note al fornitore | string | varchar |
| -telefono          | string | varchar |
| -mail              | strin  | varchar |
