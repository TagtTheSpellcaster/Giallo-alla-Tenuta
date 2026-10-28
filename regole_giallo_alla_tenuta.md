# Giallo alla Tenuta — Regole del gioco

Versione del gioco: v0.41. Gioco in stile Cluedo, per un giocatore umano contro 5 avversari controllati dal computer (bot). Per i comandi e l'uso dell'interfaccia vedi il documento *Istruzioni di gioco*.

## Il caso

Ludovico Salvaterra, padrone della Tenuta e collezionista di segreti, aveva invitato per il fine settimana sei ospiti. Stamattina all'alba la governante lo ha trovato senza vita: il corpo era stato spostato e non si trova nella stanza in cui è morto. La tempesta ha interrotto la strada e il telefono, e la polizia non arriverà prima di sera. L'assassino è uno dei sei ospiti, e ciascuno aveva un buon motivo per volere Salvaterra fuori dai piedi. Il giocatore è l'investigatore che Salvaterra aveva convocato in segreto: e deve scoprire chi, con quale arma e in quale stanza, prima dei cinque colleghi controllati dal computer.

## 1. Obiettivo

Un delitto è stato commesso nella tenuta. La soluzione, nascosta in una busta, è composta da tre carte:

- **chi** ha commesso il delitto (un personaggio);
- **con quale arma**;
- **in quale stanza**.

Vince il primo detective che formula un'**accusa corretta**. Chi sbaglia l'accusa è eliminato. Se tutti i detective vengono eliminati, nessuno vince e il caso resta irrisolto.

## 2. Componenti

### Personaggi (6)

Ambasciatore Ambra, Baronessa Bianchi, Colonnello Corallo, Dottoressa Domino, Generale Grigio, Visconte Viola.

Sono sempre tutti presenti sul tabellone. Il giocatore sceglie il proprio personaggio nel menu iniziale; gli altri cinque sono bot.

### Armi (6)

Stiletto, Attizzatoio, Veleno, Cavo, Statuetta, Chiave inglese.

### Stanze (9)

Biliardo, Salone, Cucina, Veranda, Serra, Ingresso, Studio, Biblioteca, Sala da Pranzo.

Tutte le stanze hanno le stesse regole: ciascuna può essere la stanza del delitto e in ciascuna si può ipotizzare e accusare.

### Carte

21 carte in tutto: 6 personaggi, 6 armi, 9 stanze.

## 3. Preparazione

1. **Pedine.** Ogni personaggio parte da una posizione fissa sul bordo del tabellone. Le sei posizioni sono sempre le stesse e sono tutte alla stessa distanza (5 caselle di corridoio) dalla porta più vicina.
2. **Armi.** Le 6 armi sono collocate in 6 stanze diverse, scelte a caso.
3. **Busta.** Una carta personaggio, una carta arma e una carta stanza, scelte a caso, finiscono nella busta del caso. Nessuno le vede. La busta resta chiusa e visibile nell'interfaccia fino alla fine della partita.
4. **Distribuzione.** Le restanti 18 carte sono mescolate e distribuite a turno ai 6 giocatori: ogni giocatore ha 3 carte.
5. **Taccuino.** Il gioco mostra le proprie carte e le segna automaticamente nel taccuino come escluse dalla busta. Il taccuino serve ad annotare a mano le proprie deduzioni.

## 4. Ordine dei turni

- Comincia sempre **Ambasciatore Ambra**, chiunque sia il giocatore umano.
- Si gioca poi nell'ordine dell'elenco dei personaggi: Ambra, Bianchi, Corallo, Domino, Grigio, Viola, e di nuovo Ambra.
- I giocatori eliminati vengono saltati.

## 5. Il turno

In un turno si può, nell'ordine: muoversi, formulare un'ipotesi, terminare il turno. L'accusa si può fare in qualunque momento del proprio turno (vedi sezione 8).

### 5.1 Movimento

Il giocatore può scegliere **una** di queste opzioni:

- **Tirare i dadi**: si lanciano due dadi a sei facce e la pedina si sposta di **al massimo** il totale ottenuto (da 2 a 12 caselle). Non c'è obbligo di usare tutti i passi.
- **Usare un passaggio segreto** (solo se si inizia il turno in una stanza collegata, vedi 5.3). Non si può usare dopo aver tirato i dadi.
- **Non muoversi.** Si termina il turno senza spostarsi.

Regole di movimento:

- Si muove solo in orizzontale e in verticale, mai in diagonale.
- Non si passa due volte sulla stessa casella nello stesso turno.
- Una casella di **corridoio** occupata da un'altra pedina in gioco non si può occupare né attraversare.
- Le **stanze** non hanno limiti di occupazione: più pedine possono stare nella stessa stanza.
- I **muri** disegnati sulla mappa non si attraversano.
- Un giocatore eliminato lascia la pedina sul tabellone, ma questa non blocca più i corridoi.

### 5.2 Porte e stanze

- Ogni stanza ha **una sola porta**, larga una casella, corrispondente al riquadro illuminato sulla mappa. Le porte non illuminate (ad esempio quelle laterali in legno) sono solo decorative.
- Si entra in una stanza **solo dalla sua porta**, e **entrare in una stanza termina il movimento**, anche se restano passi. La pedina si ferma sulla casella della porta ed è considerata nella stanza.
- Non si può "muoversi" restando nella stessa stanza: le caselle della stanza in cui ci si trova non sono mete valide.
- Se la pedina si trova all'interno di una stanza (perché vi è stata spostata da un'ipotesi), esce dalla porta della stanza: i passi per raggiungere la porta, contati in linea retta orizzontale più verticale, fanno parte del tiro.

### 5.3 Passaggi segreti

Due coppie di stanze d'angolo sono collegate da un passaggio segreto:

| Stanza | Collegata a |
|---|---|
| Biliardo | Sala da Pranzo |
| Cucina | Studio |

Se si inizia il turno in una di queste stanze e non si sono ancora tirati i dadi, si può usare il passaggio: la pedina si sposta nella stanza collegata e il movimento termina. Dopo il passaggio si può formulare un'ipotesi.

### 5.4 Ipotesi

Si può formulare un'ipotesi quando la pedina si trova in una stanza, e solo se:

- si è **appena entrati** nella stanza in questo turno (con i dadi o con il passaggio segreto), oppure
- si è stati **spostati nella stanza dall'ipotesi di un altro giocatore** (vedi sotto).

L'ipotesi riguarda **sempre la stanza in cui ci si trova**. Il giocatore sceglie un personaggio e un'arma.

Effetti:

1. L'arma indicata viene **spostata** nella stanza.
2. Il personaggio indicato viene **spostato** nella stanza (se non c'è già). Né l'arma né il personaggio tornano poi automaticamente al posto di prima.
3. Se il personaggio spostato è un altro giocatore, può formulare a sua volta un'ipotesi all'inizio del proprio turno **senza muoversi**. In alternativa può tirare i dadi e muoversi normalmente. Se ipotizza senza muoversi, il suo movimento in quel turno è concluso.
4. Formulare un'ipotesi conclude la fase di movimento del turno.

#### Smentita

1. Si procede nell'ordine dei turni, partendo dal giocatore successivo a chi ha ipotizzato.
2. Il primo giocatore che possiede almeno una delle tre carte nominate (personaggio, arma, stanza) la mostra a chi ha ipotizzato. Se ne ha più di una, la carta mostrata è scelta a caso dal gioco.
3. Gli altri giocatori non vedono la carta, ma vengono a sapere chi ha smentito e chi non ha potuto farlo.
4. Se nessuno può smentire, non succede nulla: l'informazione è comunque utile.
5. **I giocatori eliminati continuano a smentire** con le proprie carte.
6. Le carte di chi ha ipotizzato non vengono mai usate per smentirlo.
7. Quando è il giocatore umano a ipotizzare, vede chi ha smentito e con quale carta (o che nessuno ha potuto smentire); la carta ricevuta viene segnata nel taccuino come esclusa dalla busta.
8. Quando a ipotizzare è un bot e a smentire è il giocatore umano, il gioco gli indica chi chiede la smentita e quale carta mostra (la sceglie il gioco).

### 5.5 Fine del turno

Il giocatore umano termina il turno quando ha finito; i turni dei bot terminano da soli.

## 6. L'accusa

- Si può formulare **solo durante il proprio turno**, anche prima di muoversi, e **senza trovarsi nella stanza nominata**.
- Si indicano personaggio, arma e stanza.
- Ogni giocatore ha **una sola accusa per tutta la partita**.
- Se **tutte e tre** le carte corrispondono alla busta, il giocatore **vince** e la partita termina. La busta viene aperta e le tre carte vengono mostrate.
- Se **anche una sola** carta è diversa, l'accusa è sbagliata:
  - il giocatore è **eliminato**: non gioca più turni e non può più vincere;
  - la sua pedina resta sul tabellone, mostrata attenuata;
  - **continua a mostrare le proprie carte** per smentire le ipotesi degli altri;
  - la soluzione **non** viene rivelata e la partita prosegue.
- Se **tutti** i detective sono eliminati, la partita finisce senza vincitori e la busta viene aperta per mostrare la soluzione.

## 7. Differenze dal gioco da tavolo

- Non sono presenti le carte Indizio né il dado con il simbolo della lente.
- Si muove di **al massimo** il tiro dei dadi, e il tiro è la somma di due dadi normali.
- Restare in una stanza non consente di ipotizzare di nuovo, se non si è stati spostati lì da un altro giocatore.
- Chi smentisce non sceglie la carta da mostrare: la sceglie il gioco a caso.
- La pedina di un giocatore eliminato non blocca i corridoi.
- Comincia sempre il primo personaggio dell'elenco, non quello scelto dal giocatore.
