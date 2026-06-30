# 💰 Portafoglio — Tracciatore Spese

Piccola app (una sola pagina, nessuna dipendenza) per capire **quanto puoi davvero spendere ogni mese**.

## Come funziona

Ogni mese inserisci:

- **Entrate** — Stipendio 1, Stipendio 2 e quante altre voci vuoi
- **Spese fisse** — Mutuo, Finanziamento, ecc. (voci libere, aggiungibili/rimovibili)
- **Spese variabili** — Bollette, ecc. (voci libere)
- **Spese impreviste** — manutenzione auto, dentista, riparazioni… (voci libere)
- **Obiettivo risparmio** — es. 1000 €
- **Fondo imprevisti** — accantonamento mensile per i futuri imprevisti (opzionale)
- **Riserva sui conti** — percentuale delle entrate che deve sempre restare sui conti (default 5%), **oltre** all'obiettivo risparmio

Il risultato mostra quanto resta **per le altre spese** (mangiare, svago, ecc.):

```
Disponibile = Entrate − Spese fisse − Spese variabili − Spese impreviste − Fondo imprevisti − Obiettivo risparmio − (5% delle entrate)
```

### Esempio

| Voce | Importo |
|---|---|
| Stipendio 1 | 1.800 € |
| Stipendio 2 | 2.000 € |
| Spese fisse | 1.000 € |
| Spese variabili | 720 € |
| Obiettivo risparmio | 1.000 € |
| Riserva 5% (di 3.800 €) | 190 € |
| **Disponibile** | **890 €** |

## Caratteristiche

- ✅ Voci di spesa illimitate e personalizzabili (fisse, variabili, impreviste)
- ✅ Fondo imprevisti con saldo accumulato (accantonamenti − spese impreviste)
- ✅ Dati separati per ogni mese
- ✅ **Storico** con statistiche, grafico dell'andamento e dettaglio mese per mese
- ✅ Copia spese e obiettivi dal mese precedente
- ✅ Backup ed eventuale ripristino dei dati in un file JSON
- ✅ Salvataggio automatico sul dispositivo (`localStorage`, nessun server)
- ✅ Stima della spesa giornaliera disponibile
- ✅ Copia rapida del riepilogo
- ✅ Funziona anche offline

## Uso

Apri `index.html` in un browser. Tutto qui — nessuna installazione.
