# Inizio preparazione Orale

**Argomenti principali:** idrogeno neutro, molecolare e ionizzato; riga a 21 cm (principale).

**Collegamenti con il corso:** idrogeno, riga a 21 cm, formazione stellare, formazione delle galassie, quantistica (serie e livelli energetici), curve di rotazione delle galassie, luminosità stellare, sequenza principale, nucleosintesi.

## L'atomo di idrogeno

L'idrogeno è l'elemento più semplice, abbondante e antico. Il protone compare a t ≈ 1 µs dopo il Big Bang; a t = 20 min l'abbondanza chimica primordiale era 76% H, 24% He, con tracce di Li e Be.

È formato da un nucleo di carica positiva e da un elettrone che gli orbita attorno. Ha numero atomico Z = 1, mentre il numero di massa A dipende dal numero di neutroni (isotopo). Gli isotopi stabili sono due:

- prozio, A = 1, 99.985%
- deuterio, A = 2, 0.015%

Fino all'inizio del '900 si pensava che lo spazio interstellare fosse vuoto. Nel 1904 Hartmann, osservando δ Orionis (binaria spettroscopica), notò che le righe del CaII (e NaI) restavano ferme, senza lo spostamento Doppler periodico delle righe stellari, e avevano velocità radiali diverse da quelle della stella. Non potevano quindi appartenere alla stella osservata. Nel 1930 Trumpler scoprì la polvere interstellare e si iniziò a parlare di ISM (interstellar medium), insieme di gas e polveri che riempie lo spazio tra le stelle. L'ISM è per ≈ 99% gas e ≈ 1% polveri; del gas, ≈ 90% è idrogeno. L'idrogeno si presenta come ionizzato (HII), neutro (HI), molecolare (H₂). Ogni forma ha un proprio meccanismo di emissione e una propria firma osservativa.

### Struttura atomica, fisica dell'atomo, modello quantistico

Bohr, con l'obiettivo di spiegare la stabilità degli atomi, propose questo modello:

- Gli elettroni ruotano attorno al nucleo solo su orbite precise, stazionarie, sulle quali non emettono energia.
- Su queste orbite il moto segue la meccanica classica (che non vale nei passaggi tra orbite).
- Le orbite stazionarie hanno momento angolare quantizzato:

$$ Lₙ = nħ = \frac{n·h}{2π}, n = 1, 2, 3, … $$

- Si assorbe o emette energia solo passando da un'orbita a un'altra, e il fotone ha energia uguale alla differenza:$ hν = |E_i − E_f| $. Se $E_i − E_f > 0$ c'è emissione, se $< 0$ assorbimento.

Il modello nasce anche dagli studi di Balmer (1885) sull'emissione dell'idrogeno: lo spettro non è continuo ma discreto, a frequenze precise. Alcune righe seguono la serie

$$ν = cR(\frac{1}{4} − \frac{1}{n²}), n = 3, 4, 5, … (Balmer) $$

con $R = 109677.576 cm⁻¹$ costante di Rydberg. Furono poi scoperte altre serie:

- Lyman:  $ν = cR(1 − \frac{1}{n²}), n = 2, 3, 4, …$
- Paschen: $ν = cR(\frac{1}{9} − \frac{1}{n²}), n = 4, 5, 6, …$
- Brackett: $ν = cR(\frac{1}{16} − \frac{1}{n²}), n = 5, 6, 7, …$
- Pfund: $ν = cR(\frac{1}{25} − \frac{1}{n²}), n = 6, 7, 8, …$

Rydberg e Ritz le riassunsero in un'unica formula:

$$ ν_mn = cR(\frac{1}{m²} − \frac{1}{n²}), m = 1, 2, 3, …, n = m+1, m+2, … $$

Un elettrone sull'n-esima orbita ha energia $Eₙ = −\frac{13.6}{n²}eV$. Questi Eₙ sono gli autovalori dell'operatore hamiltoniano nell'equazione di Schrödinger $Ĥψ(r,θ,φ) = Eψ(r,θ,φ)$, la cui soluzione è:

$$ ψ_nlm(r,θ,φ) = [\frac{Rₙₗ(r)}{r}]·Y_l^m(θ,φ) $$

- $\frac{Rₙₗ(r)}{r}$: parte radiale, descrive la probabilità di trovare l'elettrone in funzione della distanza dal nucleo.
- $Y_l^m(θ,φ)$: parte angolare (armoniche sferiche), dipende da l e m, che determinano forma e orientazione spaziale degli orbitali.

Vincoli sui numeri quantici, per n fissato: $0 ≤ l ≤ n−1$ e $−l ≤ m ≤ +l$.
Per ogni l ci sono $2l+1$ stati degeneri (stessa energia); per ogni n ce ne sono n² (2n² con lo spin). L'energia è

$$ Eₙ = −[\frac{mₑ}{2ħ²}·(\frac{e²}{4πε₀})²]· \frac{1}{n²} $$

Le transizioni elettroniche descrivono il passaggio tra stati Eₘ ed Eₙ.
Einstein identificò tre processi $(m > n, Eₘ > Eₙ)$:

- **Emissione spontanea:** l'elettrone in Eₘ si diseccita e emette un fotone $hν = Eₘ − Eₙ$. Il coefficiente $A_{mn} [s⁻¹]$ è la probabilità per unità di tempo; il tempo di vita medio è $t = 1/A_{mn}$.
- **Emissione stimolata:** un fotone incidente induce la diseccitazione, con emissione di un fotone di pari energia e fase. Coefficiente $B_{mn} ρ_{mn} [s⁻¹]$, con $ρ$ densità media di fotoni.
- **Assorbimento:** l'elettrone passa da $Eₙ$ a $Eₘ$ assorbendo un fotone $hν = Eₘ − Eₙ$. Coefficiente $B_{nm} ρ_{mn}$.

Regole di selezione (approssimazione di dipolo elettrico):
$$ Δl = ±1, Δm = 0, ±1, Δn\neq0 $$
(e $Δm_s = 0$ per lo spin). Le transizioni che le violano sono "proibite" ma non impossibili: hanno coefficienti A molto bassi.

L'elettrone si comporta come un dipolo magnetico, quindi ha un momento angolare intrinseco (spin, $s = ½$, $m_s = ±½$). Questo porta alla struttura fine (accoppiamento spin-orbita più correzioni relativistiche) e, per l'interazione col momento magnetico del protone, alla struttura iperfine. Nello stato fondamentale l'iperfine toglie la degenerazione: spin paralleli = tripletto (energia maggiore), spin antiparalleli = singoletto (energia minore, più favorito). La differenza è

$$ ΔE = (\frac{4}{3})·g_p·(\frac{mₑ}{m_p})·α⁴·mₑc² ≈ 5.88·10⁻⁶ eV $$
che corrisponde a un fotone con $$ ν = \frac{ΔE}{h} = 1420 MHz $$ cioè $$ λ ≈ 21 cm $$

## Mezzo interstellare

Come detto in precedenza l'idrogeno si trova in tre diverse forme nell'universo, per questo è utile fare una classificazione in base al tipo. Abbiamo Idrogeno Neutro HI, Ionizzato HII, Molecolare H2. Il mezzo interstellare (ISM) può essere diviso in 5 categorie in distinte:

- **HIM** (Hot Ionized Medium) Caretterizzato dalla presenza di Idrogeno Ionizato HII a temperature elevate $ T = 10^6-10^7 K $ con densità tipiche $ n_H = 10^{-1}-10^{-3}$ cm $^{-3}$. Queste regioni si trovano nelle galassie ellittiche o nel bulge delle galassie a spirale. Le temperature sono conseguenza di esplosioni di supernove. Si possono osservare anche processi di ricombinazione.
- **WIM** (Warm Ionized Medium) Vi è ancora Idrogeno Ionizzato HII e temperature di circa $ T = 10^4 K $ e densità $ n_H = 1-10^{-3}$ cm $^{-3} $. Si trovano in zone limitrofe a stelle massicce e calde, come stelle del tipo O e B. Queste stelle emettono moltissimo nell'UV, quinid sono in grado di Ionizzare l'idrogeno. Sono presenti anche intorno ai nuclei galattici.
- **WNM** (Warm Neutral Medium) Caratterizzato dalla presenza di Idrogeno Neutro HI a temperature di circa $ T = 10^2-10^4 K $ con densità $ n_H = 0.1-1$ cm $^{-3}$. Queste zone si trovano tutto intorno alle galassie e vengono rilevate principalmente grazie all'emissione dell'idrogeno neutro a 1420MHz.
- **CNM** (Cold Neutral Medium) Composto da Idrogeno Neutro, polveri, molecole e principalmente idrogeno molecolare H2. $ T = 10-10^3 K $ con densità $ n_H = 1-10 $ cm $^{-3} $

### Idrogeno Neutro

Nella nostra galassia, la forma dell'idrogeno neutro, (HI) è la forma dominante in cui questo si presenta.

- Neutro $M_{HI}$~$4 * 10^9 M_☉$
- Molecolare $M_{H_2}$~$10^9 M_☉$
- Ionizzato $M_{HII}$~$10^8 M_☉$
- Componente stellare $M_{*}$~$5 * 10^{10} M_☉$

La distribuzione dell'HI non è isotropica, ma si concentra sui bracci a spirale

#### La riga a 21cm

La riga a 21cm oppure 1.4GHz in frequenza, è il metodo più importante per osservarlo.
Come detto in precedenza, un fotone a frequenza $λ ≈ 21cm$ viene emesso quando avviene un'inversione di spin all'itnerno dell'atomo di idrogeno, quando si passa da uno stato di tripletto (eccitato) ad uno stato di singoletto. Questra transizione avviene per emissione spontanea ed il suo coefficiente di Einstein è $A_H = 2.87 ×10^{−15}s^{−1}$. Questa transizione è proibita ed il tempo di vita medio dell'elettrone in stato eccitato risulta essere $τ = \frac{1}{A_H}∼10^7 anni.$
Gli atomi HI si trovano nello stato di tripletto dopo aver subito una collisione con un altro HI; a questo punto possono tornare nello stato fondamentale liberandosi di questa energia in eccesso tramite un'altra collisione oppure emettendo radiazione a 21cm.
Vista l'enorme quantità di HI la quantità di  diseccitazioni radiative è significativo, quindi quest'emissione diventa una componente fondamentale delle osservazioni astronomiche.
La riga a 21cm viene osservata nella banda radio, la quale è l'unica che ci permette ossrvazioni da terra. I fotoni radio infatti non interagiscono con l'atmosfera, ionosfera e ISM.
Possiamo ottenere una mappatura della distribuzione di HI nelle galassie a spirale irregolari: qui il gas è organizato in nubi che si estendono otlre alla componente stellare.
La massa di idrogeno neutro per regioni otticamente sottili è data da:

$$ M_{HI} = 2.36×10^5(\frac{D}{Mpc})^2 ∫ \frac{S}{Jy}\frac{dv}{km/s} [M_☉]  $$

dove:

- $D$ è la distanza dalla nube
- $S$ è il fusso osservato
- $dv$ misura la larghezza della riga allargata dall'effetto Doppler

La distribuzione della massa di idrogeno ci permette di capire quali zone del mezzo interstellare stiamo osservando.
Infatti abbiamo il Warm Neutral Medium con temperature tra i $T ∼ 10^3 − 10^4 K$ dove l'idrogeno viene riscaldato dai raggi UV e radiazione a raggi X ed il Cold Neutral Medium $T ∼ 10 − 100 K$.

#### Curva di rotazione delle galassie a spirale

A cusa della sua rotazione intorno al centro galattico, quando andiamo a fare una misurazione nei bracci della galassia a spirale, misuriamo uno spostamento della riga dovuto all'effetto Doppler. Quando li moto della nube è in allontanamento abbiamo uno spostamento verso la riga del rosso, in caso di avvicinamento verso il blu.
Con questo fenomeno possiamo capire quale è il moto di un oggetto anche a grandi distanze.

Il potenziale gravitazionale a cui sono soggetti stelle e gas è quello della galassia, quindi devono muoversi con
$$
F=\frac{GM(r)m}{r^2} = \vec{F} = m\vec{a}
→
\frac{GM(r)m}{r^2}= m\frac{v^2}{r}
$$
Con $\vec{a}$ accellerazione centripeta.
Quindi, la velocità circolare di rotazione è
$$
v^2_c = \frac{GM(r)}{r}
$$

Per analizzare questa velocità di rotazione dobbiamo dividere la galassia in 3 zone in base alla distribuzione della massa. La distribuzione viene stimata dalla radiazione proveniente da quelle zone.

- Bulge Galattico: $v(r) = r\sqrt{\rho(r)}$ questo punto viene considerato a densità costante ed assumiamo la rotazione di corpo rigido. La velocità cresce in maniera lineare rispetto alla distanza.
- Disco galattico: $v(r) = const$ la velocità di rotazione rimane costante.
- A grande distanza dal centro galattico ci si aspetterebbe una caduta kepleriana quindi $v(r) = \sqrt{\frac{GM}{r}}$ con $M =$ costante.

Dal profilo di riga osservata possiamo risalire alla cinematica della galassia e dall'allargamento possiamo capire la velocità radiale.
Tuttavia la situazione in cui $v(r) = const$ si osserva per raggi molto maggiori di quelli previsti dal modello teorico.
Superata l'estensione del disco galattico la curva di rotaizione rimane piatta. Questa cosa ci suggerisce la presenza di una massa aggiuntiva oltre a quella del disco.

#### Relazione di Tully-Fisher


