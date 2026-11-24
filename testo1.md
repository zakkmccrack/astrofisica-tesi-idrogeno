# Inizio preparazione Orale

**Argomenti principali:** idrogeno neutro, molecolare e ionizzato; riga a 21 cm (principale).

**Collegamenti con il corso:** idrogeno, riga a 21 cm, formazione stellare, formazione delle galassie, quantistica (serie e livelli energetici), curve di rotazione delle galassie, luminosità stellare, sequenza principale, nucleosintesi.

## L'atomo di idrogeno

L'idrogeno è l'elemento più semplice, abbondante e antico. Il protone compare a t $\approx 1 \mu s$ dopo il Big Bang; a t = 20 min l'abbondanza chimica primordiale era 76% H, 24% He, con tracce di Li e Be.

È formato da un nucleo di carica positiva e da un elettrone che gli orbita attorno. Ha numero atomico Z = 1, mentre il numero di massa A dipende dal numero di neutroni (isotopo). Gli isotopi stabili sono due:

- prozio, A = 1, 99.985%
- deuterio, A = 2, 0.015%

Fino all'inizio del '900 si pensava che lo spazio interstellare fosse vuoto. Nel 1904 Hartmann, osservando δ Orionis (binaria spettroscopica), notò che le righe del CaII (e NaI) restavano ferme, senza lo spostamento Doppler periodico delle righe stellari, e avevano velocità radiali diverse da quelle della stella. Non potevano quindi appartenere alla stella osservata. Nel 1930 Trumpler scoprì la polvere interstellare e si iniziò a parlare di ISM (interstellar medium), insieme di gas e polveri che riempie lo spazio tra le stelle. L'ISM è per $\approx 99$% gas e $\approx 1$% polveri; del gas, $\approx 90$% è idrogeno. L'idrogeno si presenta come ionizzato (HII), neutro (HI), molecolare ($H_2$). Ogni forma ha un proprio meccanismo di emissione e una propria firma osservativa.

### Struttura atomica, fisica dell'atomo, modello quantistico

Bohr, con l'obiettivo di spiegare la stabilità degli atomi, propose questo modello:

- Gli elettroni ruotano attorno al nucleo solo su orbite precise, stazionarie, sulle quali non emettono energia.
- Su queste orbite il moto segue la meccanica classica (che non vale nei passaggi tra orbite).
- Le orbite stazionarie hanno momento angolare quantizzato:

$$ Lₙ = n\hbar= \frac{n·h}{2\pi}, n = 1, 2, 3, … $$

- Si assorbe o emette energia solo passando da un'orbita a un'altra, e il fotone ha energia uguale alla differenza: $h\nu = |E_i − E_f|$. Se $E_i − E_f > 0$ c'è emissione, se $< 0$ assorbimento.

Il modello nasce anche dagli studi di Balmer (1885) sull'emissione dell'idrogeno: lo spettro non è continuo ma discreto, a frequenze precise. Alcune righe seguono la serie

$$\nu = cR(\frac{1}{4} − \frac{1}{n^2}), n = 3, 4, 5, … (Balmer) $$

con $R = 109677.576 cm^{-1}$ la costante di Rydberg. Furono poi scoperte altre serie:

- Lyman:  $\nu = cR(1 − \frac{1}{n^2}), n = 2, 3, 4, …$
- Paschen: $\nu = cR(\frac{1}{9} − \frac{1}{n^2}), n = 4, 5, 6, …$
- Brackett: $\nu = cR(\frac{1}{16} − \frac{1}{n^2}), n = 5, 6, 7, …$
- Pfund: $\nu = cR(\frac{1}{25} − \frac{1}{n^2}), n = 6, 7, 8, …$

Rydberg e Ritz le riassunsero in un'unica formula:

$$ \nu_{mn} = cR(\frac{1}{m^2} − \frac{1}{n^2}), m = 1, 2, 3, …, n = m+1, m+2, … $$

Un elettrone sull'n-esima orbita ha energia $Eₙ = −\frac{13.6}{n^2}eV$. Questi $E_n$ sono gli autovalori dell'operatore hamiltoniano nell'equazione di Schrödinger $\hat{H}\psi(r,\theta,\varphi) = E\psi(r,\theta,\varphi)$, la cui soluzione è:

$$ \psi_{nlm}(r,\theta,\varphi) = [\frac{R_{nl}(r)}{r}]·Y_l^m(\theta,\varphi) $$

- $\frac{R_{nl}(r)}{r}$: parte radiale, descrive la probabilità di trovare l'elettrone in funzione della distanza dal nucleo.
- $Y_l^m(\theta,\varphi)$: parte angolare (armoniche sferiche), dipende da l e m, che determinano forma e orientazione spaziale degli orbitali.

Vincoli sui numeri quantici, per n fissato: $0 ≤ l ≤ n−1 e −l ≤ m ≤ +l$.
Per ogni l ci sono $2l+1$ stati degeneri (stessa energia); per ogni n ce ne sono $n^2$ ($2n^2$ con lo spin). L'energia è

$$ E_n = −[\frac{m_e}{2\hbar^2}·(\frac{e^2}{4\pi\varepsilon _0})^2]· \frac{1}{n^2} $$

Le transizioni elettroniche descrivono il passaggio tra stati $E_m$ ed $E_n$.
Einstein identificò tre processi $(m > n, E_m > E_n)$:

- **Emissione spontanea:** l'elettrone in Eₘ si diseccita ed emette un fotone $h\nu = E_m − E_n$. Il coefficiente $A_{mn} [s^{-1}]$ è la probabilità per unità di tempo; il tempo di vita medio è $t = 1/A_{mn}$.
- **Emissione stimolata:** un fotone incidente induce la diseccitazione, con emissione di un fotone di pari energia e fase. Coefficiente $B_{mn} \rho_{mn} [s^{-1}]$, con $\rho$ densità di energia per radiazione.
- **Assorbimento:** l'elettrone passa da $E_n$ a $E_m$ assorbendo un fotone $h\nu = E_m − E_n$. Coefficiente $B_{nm} \rho_{mn}$.

Regole di selezione (approssimazione di dipolo elettrico):
$$ \Delta l = \pm 1, \Delta m = 0, \pm1, \Delta n\neq0 $$
(e $\Delta m_s = 0$ per lo spin). Le transizioni che le violano sono "proibite" ma non impossibili: hanno coefficienti A molto bassi.

L'elettrone si comporta come un dipolo magnetico perchè ha un momento angolare intrinseco (spin, $s = \frac{1}{2}$, $m_s = \pm\frac{1}{2}$). Questo porta alla struttura fine (accoppiamento spin-orbita più correzioni relativistiche) e, per l'interazione col momento magnetico del protone, alla struttura iperfine. Nello stato fondamentale l'iperfine toglie la degenerazione: spin paralleli = tripletto (energia maggiore), spin antiparalleli = singoletto (energia minore, più favorito). La differenza è

$$ \Delta E = (\frac{4}{3})·g_p·(\frac{m_e}{m_p})·α^4·m_ec^2 \approx 5.88·10^{-6} eV $$
che corrisponde a un fotone con $$ \nu = \frac{\Delta E}{h} = 1420 MHz $$ cioè $$ \lambda \approx 21 cm $$

## Mezzo interstellare

Come detto in precedenza, l'idrogeno si trova in tre diverse forme nell'universo, per questo è utile fare una classificazione in base al tipo. Abbiamo Idrogeno Neutro HI, Ionizzato HII, Molecolare $H_2$. Il mezzo interstellare (ISM) può essere diviso in 4 categorie in distinte:

- **HIM** (Hot Ionized Medium) Caretterizzato dalla presenza di Idrogeno Ionizato HII a temperature elevate $T = 10^6-10^7 \text{K}$ con densità tipiche $n_H = 10^{-1}-10^{-3}$ cm $^{-3}$. Queste regioni si trovano nelle galassie ellittiche o nel bulge delle galassie a spirale. Le temperature sono conseguenza di esplosioni di supernove. Si possono osservare anche processi di ricombinazione.
- **WIM** (Warm Ionized Medium) Vi è ancora Idrogeno Ionizzato HII e temperature di circa $T = 10^4 \text{K}$ e densità $ n_H = 1-10^{-3}$ cm $^{-3}$. Si trovano in zone limitrofe a stelle massicce e calde, come stelle del tipo O e B. Queste stelle emettono moltissimo nell'UV, quinid sono in grado di Ionizzare l'idrogeno. Sono presenti anche intorno ai nuclei galattici.
- **WNM** (Warm Neutral Medium) Caratterizzato dalla presenza di Idrogeno Neutro HI a temperature di circa $T = 10^2-10^4 \text{K}$ con densità $n_H = 0.1-1$ cm $^{-3}$. Queste zone si trovano tutt'intorno alle galassie e vengono rilevate principalmente grazie all'emissione dell'idrogeno neutro a 1420MHz.
- **CNM** (Cold Neutral Medium) Composto da Idrogeno Neutro, polveri, molecole e principalmente idrogeno molecolare $H_2$. $T = 10-10^3 \text{K}$ con densità $n_H = 1-10$ cm $^{-3}$

### Idrogeno Neutro

Nella nostra galassia la forma dominante in cui l'idrogeno si presenta è quella neutra (HI).

- Neutro $M_{HI}$~$4 * 10^9 M_\odot$
- Molecolare $M_{H_2}$~$10^9 M_\odot$
- Ionizzato $M_{HII}$~$10^8 M_\odot$
- Componente stellare $M_{*}$~$5 * 10^{10} M_\odot$

La distribuzione dell'HI non è isotropica, ma si concentra sui bracci a spirale

#### La riga a 21cm

La riga a 21cm oppure 1.4GHz in frequenza è il metodo più importante per osservare HI.
Come detto in precedenza, un fotone a lunghezza d'onda $\lambda \approx 21cm$ viene emesso quando avviene un'inversione di spin all'interno dell'atomo di idrogeno, quando si passa da uno stato di tripletto (eccitato) ad uno stato di singoletto. Questa transizione avviene per emissione spontanea ed il suo coefficiente di Einstein è $A_H = 2.87 ×10^{−15}s^{−1}$. Questa transizione è proibita ed il tempo di vita medio dell'elettrone in stato eccitato risulta essere $\tau  = \frac{1}{A_H}∼10^7 anni.$
Gli atomi HI si trovano nello stato di tripletto dopo aver subito una collisione con un altro HI; a questo punto possono tornare nello stato fondamentale liberandosi di questa energia in eccesso tramite un'altra collisione oppure emettendo radiazione a 21cm.
Vista l'enorme quantità di HI la quantità di  diseccitazioni radiative è significativo, quindi quest'emissione diventa una componente fondamentale delle osservazioni astronomiche.
La riga a 21cm viene osservata nella banda radio, la quale è l'unica che ci permette ossrvazioni da terra. I fotoni radio infatti non interagiscono con l'atmosfera, ionosfera e ISM.
Possiamo ottenere una mappatura della distribuzione di HI nelle galassie a spirale ed irregolari: qui il gas è organizzato in nubi che si estendono oltre alla componente stellare.
La massa di idrogeno neutro per regioni otticamente sottili è data da:

$$ M_{HI} = 2.36×10^5(\frac{D}{Mpc})^2 ∫ \frac{S}{Jy}\frac{dv}{km/s} [M_\odot]  $$

dove:

- $D$ è la distanza dalla nube
- $S$ è il fusso osservato
- $dv$ misura la larghezza della riga allargata dall'effetto Doppler

La distribuzione della massa di idrogeno ci permette di capire quali zone del mezzo interstellare stiamo osservando.
Infatti abbiamo il Warm Neutral Medium con temperature tra i $T ∼ 10^3 − 10^4 \text{K}$ dove l'idrogeno viene riscaldato dai raggi UV e radiazione X ed il Cold Neutral Medium $T ∼ 10 − 100 \text{K}$.

#### Curva di rotazione delle galassie a spirale

A causa della sua rotazione intorno al centro galattico, quando andiamo a fare una misurazione nei bracci della galassia a spirale, misuriamo uno spostamento della riga dovuto all'effetto Doppler. Quando il moto della nube è in allontanamento abbiamo uno spostamento verso il rosso, in caso di avvicinamento verso il blu.
Con questo fenomeno possiamo capire quale è il moto di un oggetto anche a grandi distanze.

Il potenziale gravitazionale a cui sono soggetti stelle e gas è quello della galassia, quindi devono muoversi in modo che la forza gravitazionale eguagl la forza centripeta:
$$
F=\frac{GM(r)m}{r^2} = \vec{F} = m\vec{a}
→
\frac{GM(r)m}{r^2}= m\frac{v^2}{r}
$$
Con $\vec{a}$ accelerazione centripeta.
Quindi, la velocità circolare di rotazione è
$$
v^2_c = \frac{GM(r)}{r}
$$

Per analizzare questa velocità di rotazione dobbiamo dividere la galassia in 3 zone in base alla distribuzione della massa. La distribuzione viene stimata dalla radiazione proveniente da quelle zone.

- Bulge Galattico: $v(r) ∼ r\sqrt{\rho(r)}$ questa regione viene considerata a densità costante ed assumiamo la rotazione di corpo rigido. La velocità cresce in maniera lineare rispetto alla distanza.
- Disco galattico: $v(r) = const$ la velocità di rotazione rimane costante.
- A grande distanza dal centro galattico ci si aspetterebbe una caduta kepleriana quindi $v(r) = \sqrt{\frac{GM}{r}}$ con $M =$ costante.

Dal profilo di riga osservata possiamo risalire alla cinematica della galassia e dall'allargamento possiamo capire la velocità radiale.
Tuttavia la situazione in cui $v(r) = const$ si osserva per raggi molto maggiori di quelli previsti dal modello teorico.
Superata l'estensione del disco galattico la curva di rotazione rimane piatta. Questa cosa ci suggerisce la presenza di una massa aggiuntiva oltre a quella del disco.

#### Relazione di Tully-Fisher

Nel solo caso delle galassie a spirale, a partire dai dati precedenti, possiamo ricavare una legge che lega la luminosità del disco galattico alla velocità di rotazione delle nubi HI.
Si ha
$$
L_{disk} \propto v^4_{HI}
→
L \propto v^\alpha_c
$$
Questa relazione è importantissima nel calcolo delle distanze astronomiche. Si ha
$$
L_{disk}= 4 \pi d^2 l
$$
dove l è il flusso (luminosità apparente) e d la distanza alla quale osserviamo la galassia. Da questo possiamo ricavare la distanza come:
$$
d = \sqrt{\frac{L_{disk}}{4\pi l}} \approx \sqrt{\frac{v^4_{HI}}{4\pi l}}
$$

### Idrogeno Ionizzato

L'idrogeno ha un'energia di ionizzazione pari a 13.6 eV e si trova in regioni con temperature $\geq10^4\text{K}$.
Queste regioni sono:

- Hot Ionized Medium
- Intra Cluster Medium, $10^6 - 10^7 \text{K}$
- Warm Ionized Medium, $10^4 \text{K}$, intorno a stelle di classe O-B.

Le stelle di classe O-B sono stelle dalla vita molto breve, quindi queste regioni dove si trova l'HII sono relativamente giovani, con un recente episodio di formazione stellare.11111111
In queste zone la densità degli ioni di idrogeno è tra i $10^{-1} \text{ e } 10^{-4} cm^{-3}$ mentre per l'HIM $10^{-3} cm^{-3}$ ed il mezzo interstellare assume la forma di plasma neutro.

#### Emissione in righe di ricombinazione

Nelle zone ad alta Ionizzazione può avvenire la ricombinazione: gli elettroni liberi vengono catturati dagli ioni positivi e si posizionano in un certo livello energetico emettendo un fotone.
La transizione avviene tra il livello $n= \infty$ ed il livello al quale si ricollega.
Da questo livello possono poi decadere fino ad arrivare ai livelli $n=1,2$.
Le righe generate dall'emissione in seguito alla ricombinazione vengono chiamati con il numero del livello energetico di arrivo dell'elettrone seguito da $\alpha$ se $\Delta n = 1$, $\beta$ se $\Delta n = 2$ e così via.
Per le serie iniziali i fotoni vengon chiamati

- $H\alpha$, $H\beta$, ... per Balmer
- $Ly\alpha$ per Lyman
- $Pa\delta$ per Paschen

La serie di Lyman difficilmente uscirà dalla nube, visto che i fotoni sono considerati fotoionizzanti.
Le righe $H\alpha$ ed $H\beta$ sono le più importanti ed emettono a $656.3nm$ nel rosso e $486.1nm$ nel blu.

#### Sfera di Strömgren

Nelle nubi attorno alle stelle giovani di classe O-B vi è un intenso campo di radiazione di fotoni, il quale comporta un processo di fotoionizzazione del gas.
Il rate di fotoionizzazione dipende dalla sezione d'urto di fotoionizzazione $\sigma_ion(\nu)$, dalla densità di atomi neutri $n(H)$ e dal flusso di fotoni fotoionizzanti $S_*$
Il rate di fotoinizzazione è
$$
\dot{N}_{pi} = n(H)\sigma_{ion}(\nu)\frac{S_*}{4 \pi R^2} → S_*=\int^\infty_{13.6 eV} \frac{L_{\nu}}{h \nu} d \nu
$$
Questi elettroni liberi emettono per bremsstrahlung. Il rate di ricombinazione si definisce come
$$
\dot{N}_{rec} = n(H^+)n(e)\alpha_H(T)
$$
Dove abbiamo:

- $\alpha_H(T)$ = tasso di ricombinazione
- $n(H^+)$ = densità di ioni
- $n(e)$ = elettroni liberi

Imponendo un equilibrio tra i processi di ionizzazione e ricombinazione si ha una superficie sfetica all'interno della quale l'idrogeno è completamente ionizzato ed all'esterno è completamene neutro. Questa sfera di chiama sfera di Strömgren ed ha raggio stimato
$$
R_s = (\frac{3}{4 \pi} \frac{S_*}{\alpha(T)n^2_H})^{1/3}
$$

Questo fenomeno comporta una diminuzione di radiazione nell'UV (causa ionizzazione), la presenza di un continuo di bremsstrahlung ed un gran numero di righe di ricombinazione.
Il tempo scala di ricombinazione risulta essere
$$
\tau_{rec} = \frac {1}{n_e \alpha_H} \approx \frac{10^5yr}{n(e)}
$$

La grandezza della densità elettronica $n(e)$ ci dà delle indicazioni sulla soglia di densità critica oltre la quale prevalgono i processi radiativi attraverso la comparazione con la densità critica $n_c = \frac{A_{ul}}{Q_{ul}}$ abbiamo:

- $n(e)>n_c$ l'energia degli elettroni verrà dissipata in urti
- $n(e)<<n_c$ ci sarà irraggiamento sotto forma di righe di ricombinazione con $L \propto  n(e)^2$

$n_c$ è il rapporto tra il coefficiente di Einstein  di emissione spontanea e quello di diseccitazione collisionale dati due livelli $u$ ed $l$ con $u>l$.
La densità elettronica è correlata alla luminosità bolometrica attraverso la funzione di raffreddamento $\Lambda(T)$. Questa dipende anche dalla metallicità e ci dice quanto è efficiente nel dissipare energia radiativa, quindi ad emettere luminosità.
$$
L \propto  n(e)^2 \Lambda(T)
$$

### Idrogeno Molecolare

Il gas molecolare è il responsabile della formazione stellare grazie al collasso delle zone chiamate GMC (giant molecular clouds), delle grandissime nubi di $H_2$.
I canali di formazione dell'$H_2$ sono:

- canale dell'$H^+$ efficiente ad alti redshift; le reazioni sono:
  - $H^+ + H → H_2^+ + h\nu$
  - $H^+_2 + H → H_2 + H^+$
- canale dell'$H^-$ a redshift inferiori con le reazioni:
  - $H + e^- → H^- + h\nu$
  - $H + H^- → H_2 + e^-$
- formazione a 3 corpi, ad alte densità durante il collasso della nube:
  - $H+H+H →  H_2 + H$
  - $H+H+H_2 →  H_2 + H_2$

I grani di polvere interstellare aiutano la formazione dell'$H_2$ e schermano gli atomi di idrogeno dal campo di radiazione.
Avvengono transizioni elettroniche (UV, visibile), vibrazionali (IR) e rotazionali (microonde), quantizzate.
La formazione di $H_2$ è rara e, di conseguenza, anche la sua osservazione visto che ha un $\Delta J = \pm2$ relativo alla transizione di quadripolo osservabile a temperature intorno ai $510\text{K}$ ed ha un coefficiente di Einstein basso, pari ad $A=3*10^{-11} s^{-1}$.
La molecola di CO, la seconda più presente nell'universo, ci viene in aiuto per lo studio dell'abbondanza dell'$H_2$, perché avendo un'elevata energia di legame (11.1 eV) risulta difficile da dissociare ed ha un momento di dipolo permanente che permette transizioni di dipolo $\Delta J = \pm1$ che si può osservare a temperature di $5.5\text{K}$. Si stima il fattore di conversione $\frac{CO}{H_2}$ osservando l'intensità integrata in velocità $I_{CO}$ di CO prodotto durante una transizione
$$
x_{CO} = \frac{N_{H_2}}{I_{CO}} ∼ 2 * 10^{20}[cm^{-2}(\text{K km }s^{-1})^{-1}]
$$
dove
$$
I_{CO} = \int_{ \Delta \nu}F(\nu)d\nu
$$
$N_{H_2}$ rappresenta la densità di colonna di $H_2$.
Le GMC hanno un'alta densità rispetto all'ISM. La densità di colonna $N_{H_2}$ ricavata dal fattore $x_{CO}$  ci permette di scoprire che per valori $\geq 10^{17} cm ^ {-2}$ la nube sviluppa un'opacità di $\tau ∼ 1$ per cui la radiazione UV ed ottica non riesce a passare. Questo fenomeno prende il nome di self shielding e permette alla nube di non perdere materiale molecolare per fotodissociazione.

## Nucleosintesi stellare

La vita delle stelle viene regolata dall'idrogeno, il quale funge da carburante nella fase dominante della loro esistenza, ovvero quando si trovano nella sequenza principale.
Il mantenimento della struttura stellare è dovuto alla fusione dell'idrogeno in elio attraverso due canali principali, il ciclo CNO e la catena PP.

### La catena Protone-Protone (PP)

La catena PP si divide in 3 rami in base alle temperature di attivazione.
Attorno a temperature di $\sim 6 * 10^6\text{K}$ diventa efficiente la fusione PPI tra due protoni che producono un nucleo di deuterio, grazie al decadimento $\beta^+$, il quale viene poi fuso con l'idrogeno per formare $^3He$ che, unito ad un altro nucleo, $^3He$ da $^4He$.
Intorno ai $15*10^6 \text{K}$, dopo che la catena PPI ha iniziato a formare $^4He$, si avvia la seconda reazione, la catena PPII.
Questa catena a partire da $^3He + ^4He$ produce del $^7Be$ che interagendo con un elettrone produce del $^7Li$.
Il ramo PPIII è una diramazione del PPII e differisce per l'interazione del $^7Be$. Invece di interagire con un elettrone, interagisce con un protone portando alla formazione del boro $^8B$ il quale poi decade in $^8Be$. Quest'ultima reazione porta ad una grande perdita di energia che rende questo ramo quello con la produzione energetica minore di tutta la catena.

### Ciclo CNO

In presenza di elementi pesanti come Carbonio (C), Azoto (N) ed Ossigeno (O) e temperature di circa $15*10^6 \text{K}$ si attiva il ciclo CNO.
Questo elementi fungono da catalizzatori per il bruciamento dell'idrogeno in elio.
Il ciclo si divide in un ramo veloce ed in un ramo lento.
La parte del ciclo fino alla reazione $^{14}N + ^1H \rightarrow ^{15}O + \gamma$ è quella del ramo veloce, mentre tutta la parte di ciclo che viene dopo si chiama ramo lento.
Questo ciclo si pensa essere il dominante in stelle con $M_\ast \gtrsim  1.3 M_\odot$.

Dopo la bruciatura dell'idrogeno e quando la temperature raggiungono valori  $T = 15*10^8 \text{K}$ può iniziare la fase di combustione dell'elio attraverso il processo Triplo Alfa.
