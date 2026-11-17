# Verbale n. 1

**Data:** 17 novembre 2026

## 1. Ruoli assegnati

| Membro | Ruolo |
|---|---|
| Jaspreet Singh | Responsabile |
| Yaroslav Bilan | Git & QA Specialist + Lead JS Developer |
| Daniel Gliniecki | CSS Designer + mediatore del gruppo |

## 2. Cadenza e giorni dei briefing

- Stand-up di 15 minuti.
- Giorni: **ogni martedì** (giorno di laboratorio) e **ogni sabato**.

## 3. Flusso di lavoro Git: GitHub Flow

### Branch
- `main` è l'unico branch principale del progetto, sempre funzionante. Nessun push viene effettuato direttamente su `main`.
- Per ogni nuovo lavoro si crea un nuovo branch partendo da una copia di `main`, e si lavora lì senza toccare `main`. Finito il lavoro, il branch torna in `main` con una Pull Request.
- Branch che useremo: `main`, `readme`, `verbale1`, `strutturainiziale`, `strutturahtml`, `stilekaivo`, `catalogo`, `filtri`, `dettaglioprodotto`, `carrello`, `checkout`.
- Dopo il merge il branch viene cancellato: il lavoro è già dentro `main`, quindi non si perde niente, e così non restano branch vecchi e inutili.

### Commit
- Commit atomici con prefisso standard: `feat:`, `fix:`, `style:`, `docs:`, `refactor:`.
- Esempio: `feat: aggiunta filtro prezzo`.

### Pull Request
- Ogni funzionalità o fix passa da una Pull Request con titolo chiaro e breve descrizione di cosa cambia.
- Serve almeno 1 approvazione di un altro componente del gruppo, mai dell'autore della Pull Request.
- Chi rivede controlla che il codice funzioni e che non rompa il resto.
- Il merge avviene solo dopo l'approvazione, a cura dell'autore della Pull Request.
- I conflitti di merge li risolve l'autore della Pull Request, con l'aiuto di Yaroslav.

## 4. Nome del gruppo di lavoro (agenzia)

**JDYP** (Jaspreet Daniel Yaroslav Protocol).

## 5. Repository GitHub

- Repository creato: `https://github.com/glinieckidaniel/PROGETTO-KAIVO`
- Collaboratori aggiunti: Jaspreet Singh, Yaroslav Bilan e la prof.ssa Villani.
