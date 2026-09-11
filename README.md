# rehabpro-legal

Le pagine pubbliche di rehabpro: informativa sulla privacy e termini. Pubblicate con GitHub Pages.

**Questo repository è pubblico per una sola ragione:** gli abbonamenti dell'App Store richiedono che
l'informativa sulla privacy e i termini siano raggiungibili a un URL, e GitHub Pages è gratuito solo sui
repository pubblici. Il codice dell'applicazione sta altrove e resta privato. Qui non c'è nulla che non
sia destinato a essere letto da chiunque.

| File           | Cosa è                                                                        |
| -------------- | ----------------------------------------------------------------------------- |
| `index.html`   | Pagina di ingresso, collega le altre due                                      |
| `privacy.html` | Informativa sulla privacy — l'URL da inserire in App Store Connect            |
| `termini.html` | Termini, condizioni dell'abbonamento e **avvertenza clinica**                 |

## Stato

- [x] Indirizzo di contatto inserito (`malfara.labs@gmail.com`) e blocchi di avviso rimossi — 2026-09-11.

Le pagine sono complete e i due URL possono essere inseriti in App Store Connect:

| Campo in App Store Connect | URL                                                  |
| -------------------------- | ---------------------------------------------------- |
| Privacy Policy URL         | `https://malfix.github.io/rehabpro-legal/privacy.html` |
| Termini (EULA / licenza)   | `https://malfix.github.io/rehabpro-legal/termini.html` |

**L'indirizzo di contatto è pubblico e deve restare attivo.** È il recapito che l'art. 13 del
Regolamento UE 2016/679 richiede per il titolare del trattamento: senza un contatto valido l'informativa
non è conforme, e una casella che rimbalza è peggio di nessuna casella.

## Scelte che non sono stilistiche

- **La licenza è l'EULA standard di Apple**, collegato e non riscritto. Termini propri su uno strumento
  professionale a questo prezzo non comprano nulla e creano un documento da mantenere.
- **L'avvertenza clinica è separata dal contratto.** Riguarda il modo in cui lo strumento va usato — il
  giudizio clinico è del fisioterapista — e non è una clausola di esclusione di responsabilità travestita.
- **L'informativa dichiara il rischio residuo invece di tacerlo:** i campi a testo libero possono
  contenere ciò che il terapista vi scrive, e per quei dati il titolare è lui. È la stessa lettura che il
  PRD dell'applicazione impone a chi valuta la posizione GDPR.
- **Nessuna analitica su queste pagine.** Sarebbe contraddittorio: dichiarano che l'applicazione non
  traccia nessuno.

## Pubblicazione

GitHub Pages, branch `main`, cartella radice. Ogni push aggiorna le pagine.
