# Inizio preparazione Orale

**Argomenti principali:** idrogeno neutro, molecolare e ionizzato; riga a 21 cm (principale).

**Collegamenti con il corso:** idrogeno, riga a 21 cm, formazione stellare, formazione delle galassie, quantistica (serie e livelli energetici), curve di rotazione delle galassie, luminosità stellare, sequenza principale, nucleosintesi.

## L'irogeno

L'idrogeno è l'elemento più semplice, abbondante e antico. Il protone compare a t ≈ 1 µs dopo il Big Bang; a t = 20 min l'abbondanza chimica primordiale era 76% H, 24% He, con tracce di Li e Be.

È formato da un nucleo di carica positiva e da un elettrone che gli orbita attorno. Ha numero atomico Z = 1, mentre il numero di massa A dipende dal numero di neutroni (isotopo). Gli isotopi stabili sono due:

- prozio, A = 1, 99.985%
- deuterio, A = 2, 0.015%

Fino all'inizio del '900 si pensava che lo spazio interstellare fosse vuoto. Nel 1904 Hartmann, osservando δ Orionis (binaria spettroscopica), notò che le righe del CaII (e NaI) restavano ferme, senza lo spostamento Doppler periodico delle righe stellari, e avevano velocità radiali diverse da quelle della stella. Non potevano quindi appartenere alla stella osservata. Nel 1930 Trumpler scoprì la polvere interstellare e si iniziò a parlare di ISM (interstellar medium), insieme di gas e polveri che riempie lo spazio tra le stelle. L'ISM è per ≈ 99% gas e ≈ 1% polveri; del gas, ≈ 90% è idrogeno. L'idrogeno si presenta come ionizzato (HII), neutro (HI), molecolare (H₂). Ogni forma ha un proprio meccanismo di emissione e una propria firma osservativa.

## Struttura atomica, fisica dell'atomo, modello quantistico

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

$$ Eₙ = −[\frac{mₑ}{2ħ²}]·(\frac{e²}{4πε₀})²· \frac{1}{n²} $$

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
che corrisponde a un fotone con $$ ν = ΔE/h = 1420 MHz $$ cioè $$ λ ≈ 21 cm $$.
