# Formule

---

## 1. RADIAZIONE E MATERIA

### Corpo Nero (Legge di Planck)
$$B_\nu(T) = \frac{2h\nu^3}{c^2} \frac{1}{e^{h\nu/kT} - 1}$$
$$B_\lambda(T) = \frac{2hc^2}{\lambda^5} \frac{1}{e^{hc/\lambda kT} - 1}$$

| Variabile | Significato |
|-----------|-------------|
| $B_\nu(T)$ | Brillanza spettrale per unità di frequenza [W m⁻² Hz⁻¹ sr⁻¹] |
| $B_\lambda(T)$ | Brillanza spettrale per unità di lunghezza d'onda [W m⁻³ sr⁻¹] |
| $h$ | Costante di Planck |
| $\nu$ | Frequenza della radiazione [Hz] |
| $\lambda$ | Lunghezza d'onda [m] |
| $c$ | Velocità della luce nel vuoto |
| $k$ | Costante di Boltzmann |
| $T$ | Temperatura del corpo nero [K] |

---

### Legge di Wien
$$\lambda_{max} \cdot T = b$$

| Variabile | Significato |
|-----------|-------------|
| $\lambda_{max}$ | Lunghezza d'onda al picco dello spettro [m] |
| $T$ | Temperatura del corpo [K] |
| $b$ | Costante di Wien = $2.898 \times 10^{-3}$ m·K |

---

### Legge di Stefan-Boltzmann
$$F = \sigma T^4 \qquad L = 4\pi R^2 \sigma T^4$$

| Variabile | Significato |
|-----------|-------------|
| $F$ | Flusso totale irradiato dalla superficie [W m⁻²] |
| $L$ | Luminosità totale della stella [W] |
| $R$ | Raggio della stella [m] |
| $\sigma$ | Costante di Stefan-Boltzmann = $5.671\times10^{-8}$ W m⁻² K⁻⁴ |
| $T$ | Temperatura efficace [K] |

---

### Luminosità e Flusso ricevuto
$$F = \frac{L}{4\pi d^2}$$

| Variabile | Significato |
|-----------|-------------|
| $F$ | Flusso ricevuto dall'osservatore [W m⁻²] |
| $L$ | Luminosità intrinseca della sorgente [W] |
| $d$ | Distanza dalla sorgente [m o pc] |

---

### Energia del fotone
$$E = h\nu = \frac{hc}{\lambda}$$

| Variabile | Significato |
|-----------|-------------|
| $E$ | Energia del fotone [J o eV] |
| $h$ | Costante di Planck |
| $\nu$ | Frequenza [Hz] |
| $\lambda$ | Lunghezza d'onda [m] |

---

### Effetto Doppler
$$\frac{\Delta\lambda}{\lambda_0} = \frac{v_r}{c} \qquad \text{(non relativistico)}$$
$$\frac{\lambda_{obs}}{\lambda_{em}} = \sqrt{\frac{1+\beta}{1-\beta}} \qquad \text{(relativistico)}$$

| Variabile | Significato |
|-----------|-------------|
| $\Delta\lambda = \lambda_{obs} - \lambda_0$ | Spostamento in lunghezza d'onda [m] |
| $\lambda_0, \lambda_{em}$ | Lunghezza d'onda emessa (a riposo) [m] |
| $\lambda_{obs}$ | Lunghezza d'onda osservata [m] |
| $v_r$ | Velocità radiale della sorgente rispetto all'osservatore [m/s]; positiva se si allontana |
| $\beta = v/c$ | Velocità in unità di $c$ |

---

### Approssimazione di Rayleigh-Jeans
$$B_\nu \approx \frac{2\nu^2}{c^2} kT_b$$

| Variabile | Significato |
|-----------|-------------|
| $T_b$ | Temperatura di brillanza: temperatura del corpo nero che darebbe la stessa $B_\nu$ osservata [K] |

---

## 2. MAGNITUDINI

### Scala di Pogson
$$m_1 - m_2 = -2.5 \log_{10}\left(\frac{F_1}{F_2}\right)$$

| Variabile | Significato |
|-----------|-------------|
| $m_1, m_2$ | Magnitudini apparenti dei due oggetti (adimensionale) |
| $F_1, F_2$ | Flussi ricevuti dei due oggetti [W m⁻²] |

---

### Modulo di distanza
$$\mu = m - M = 5\log_{10}(d/\text{pc}) - 5$$

| Variabile | Significato |
|-----------|-------------|
| $m$ | Magnitudine apparente (osservata) |
| $M$ | Magnitudine assoluta (magnitudine apparente se l'oggetto fosse a 10 pc) |
| $\mu$ | Modulo di distanza [mag] |
| $d$ | Distanza in parsec |

---

### Estinzione interstellare
$$m - M = 5\log_{10}(d) - 5 + A$$

| Variabile | Significato |
|-----------|-------------|
| $A$ | Estinzione interstellare in magnitudini (sempre positiva, oscura e arrossisce) |

---

### Magnitudine bolometrica
$$M_{bol} = M_{bol,\odot} - 2.5\log_{10}\left(\frac{L}{L_\odot}\right)$$

| Variabile | Significato |
|-----------|-------------|
| $M_{bol}$ | Magnitudine assoluta bolometrica (integrata su tutte le lunghezze d'onda) |
| $M_{bol,\odot} = 4.74$ | Magnitudine bolometrica assoluta del Sole |
| $L, L_\odot$ | Luminosità dell'oggetto e del Sole |

---

### Correzione bolometrica
$$M_{bol} = M_V + BC$$

| Variabile | Significato |
|-----------|-------------|
| $M_V$ | Magnitudine assoluta nella banda V (visibile) |
| $BC$ | Correzione bolometrica: tiene conto della radiazione fuori dalla banda V; negativa per stelle molto calde o molto fredde |

---

### Parallasse trigonometrica
$$d(\text{pc}) = \frac{1}{p''}$$

| Variabile | Significato |
|-----------|-------------|
| $d$ | Distanza in parsec [pc] |
| $p''$ | Parallasse annua in arcosecondi ['']; metà dello spostamento angolare apparente della stella rispetto alle stelle di sfondo in 6 mesi |

---

## 3. MASSE STELLARI

### Terza Legge di Keplero (forma generale)
$$\frac{a^3}{P^2} = \frac{G(M_1 + M_2)}{4\pi^2}$$

| Variabile | Significato |
|-----------|-------------|
| $a$ | Semiasse maggiore dell'orbita relativa [m o AU] |
| $P$ | Periodo orbitale [s o yr] |
| $G$ | Costante di gravitazione universale |
| $M_1, M_2$ | Masse dei due corpi [kg o $M_\odot$] |

---

### Centro di massa
$$M_1 r_1 = M_2 r_2 \qquad a = r_1 + r_2$$

| Variabile | Significato |
|-----------|-------------|
| $r_1, r_2$ | Distanze dei due corpi dal centro di massa [m] |

---

### Funzione di massa (binarie spettroscopiche a una riga)
$$f(M) = \frac{M_2^3 \sin^3 i}{(M_1+M_2)^2} = \frac{P\,v_{r1}^3}{2\pi G}$$

| Variabile | Significato |
|-----------|-------------|
| $f(M)$ | Funzione di massa: quantità osservabile che vincola le masse [kg o $M_\odot$] |
| $i$ | Inclinazione del piano orbitale rispetto alla linea di vista ($i=90°$: orbita edge-on) |
| $v_{r1}$ | Semiampiezza della curva di velocità radiale della stella 1 [m/s] |

---

### Relazione massa-luminosità
$$\frac{L}{L_\odot} \approx \left(\frac{M}{M_\odot}\right)^\alpha, \quad \alpha \approx 3.5\text{–}4$$

| Variabile | Significato |
|-----------|-------------|
| $\alpha$ | Esponente empirico; varia con la massa (~4 per stelle di massa intermedia) |

---

### Teorema del Viriale
$$\langle E_k \rangle = -\frac{1}{2}\langle E_p \rangle \qquad E_{tot} = -\langle E_k \rangle$$

| Variabile | Significato |
|-----------|-------------|
| $\langle E_k \rangle$ | Energia cinetica media del sistema |
| $\langle E_p \rangle$ | Energia potenziale gravitazionale media |
| $E_{tot}$ | Energia meccanica totale (negativa → sistema legato) |

---

## 4. SPETTRI STELLARI

### Formula di Rydberg
$$\frac{1}{\lambda} = R_H\left(\frac{1}{n_1^2} - \frac{1}{n_2^2}\right), \quad n_2 > n_1$$

| Variabile | Significato |
|-----------|-------------|
| $\lambda$ | Lunghezza d'onda della riga spettrale [m] |
| $R_H = 1.097\times10^7$ m⁻¹ | Costante di Rydberg per l'idrogeno |
| $n_1$ | Livello inferiore della transizione (intero ≥ 1) |
| $n_2$ | Livello superiore della transizione (intero > $n_1$) |

### Serie principali H:
| Serie | $n_1$ | Regione spettrale |
|-------|--------|-------------------|
| Lyman | 1 | UV |
| Balmer | 2 | Visibile |
| Paschen | 3 | IR vicino |
| Brackett | 4 | IR |

---

### Distribuzione di Boltzmann
$$\frac{N_b}{N_a} = \frac{g_b}{g_a} e^{-(E_b - E_a)/kT}$$

| Variabile | Significato |
|-----------|-------------|
| $N_a, N_b$ | Numero di atomi nei livelli $a$ e $b$ |
| $g_a, g_b$ | Pesi statistici (degenerazione) dei livelli; per H: $g=2n^2$ |
| $E_a, E_b$ | Energie dei livelli [J o eV] |
| $k$ | Costante di Boltzmann |
| $T$ | Temperatura [K] |

---

### Equazione di Saha
$$\frac{N_{r+1}}{N_r} = \frac{1}{n_e}\frac{2Z_{r+1}}{Z_r}\left(\frac{2\pi m_e kT}{h^2}\right)^{3/2} e^{-\chi_r/kT}$$

| Variabile | Significato |
|-----------|-------------|
| $N_r, N_{r+1}$ | Popolazioni al grado di ionizzazione $r$ e $r+1$ |
| $n_e$ | Densità numerica degli elettroni liberi [m⁻³] |
| $Z_r, Z_{r+1}$ | Funzioni di partizione degli stati di ionizzazione $r$ e $r+1$ |
| $m_e$ | Massa dell'elettrone |
| $\chi_r$ | Potenziale di ionizzazione dal grado $r$ [J o eV] |
| $h$ | Costante di Planck |

---

### Larghezza equivalente
$$W_\lambda = \int \frac{F_c - F_\lambda}{F_c} d\lambda$$

| Variabile | Significato |
|-----------|-------------|
| $W_\lambda$ | Larghezza equivalente della riga [m o Å]: larghezza di un rettangolo di altezza $F_c$ con la stessa area della riga |
| $F_c$ | Flusso del continuo (fondo spettrale senza riga) [W m⁻³] |
| $F_\lambda$ | Flusso osservato (con la riga di assorbimento) [W m⁻³] |

---

## 5. ATMOSFERE STELLARI & TRASPORTO RADIATIVO

### Equazione del trasporto radiativo
$$\frac{dI_\nu}{ds} = -\kappa_\nu \rho I_\nu + j_\nu$$

| Variabile | Significato |
|-----------|-------------|
| $I_\nu$ | Intensità specifica monocromatica [W m⁻² Hz⁻¹ sr⁻¹] |
| $s$ | Coordinata lungo la direzione di propagazione [m] |
| $\kappa_\nu$ | Opacità monocromatica (sezione d'urto per unità di massa) [m² kg⁻¹] |
| $\rho$ | Densità del mezzo [kg m⁻³] |
| $j_\nu$ | Coefficiente di emissione monocromatica [W m⁻³ Hz⁻¹ sr⁻¹] |

---

### Profondità ottica
$$\tau_\nu = \int_0^s \kappa_\nu \rho \, ds'$$

| Variabile | Significato |
|-----------|-------------|
| $\tau_\nu$ | Profondità ottica monocromatica (adimensionale); $\tau\gg1$: mezzo otticamente spesso; $\tau\ll1$: otticamente sottile |

---

### Soluzione formale del trasporto
$$I_\nu(0,\mu) = \int_0^\infty S_\nu(\tau_\nu)\, e^{-\tau_\nu/\mu}\frac{d\tau_\nu}{\mu}$$

| Variabile | Significato |
|-----------|-------------|
| $S_\nu = j_\nu/(\kappa_\nu\rho)$ | Funzione sorgente monocromatica [W m⁻² Hz⁻¹ sr⁻¹]; in LTE: $S_\nu = B_\nu(T)$ |
| $\mu = \cos\theta$ | Coseno dell'angolo tra la direzione di propagazione e la normale alla superficie |

---

### Approssimazione di Eddington-Barbier
$$I_\nu(0,\mu) \approx S_\nu(\tau_\nu = \mu)$$

> Regola pratica: l'intensità emergente in direzione $\mu$ "sonda" la funzione sorgente alla profondità ottica $\tau=\mu$. In particolare, per $\mu=1$ (nadir): $I_\nu(0,1) \approx S_\nu(\tau=1)$.

---

### Gradiente di temperatura (atmosfera grigia)
$$T^4(\tau) = \frac{3}{4}T_{eff}^4\left(\tau + \frac{2}{3}\right)$$

| Variabile | Significato |
|-----------|-------------|
| $T(\tau)$ | Temperatura locale alla profondità ottica $\tau$ |
| $T_{eff}$ | Temperatura efficace della stella: temperatura del corpo nero con uguale flusso totale |
| $\tau = 2/3$ | Profondità ottica della fotosfera (livello da cui emerge la radiazione visibile) |

---

### Pressione di radiazione
$$P_{rad} = \frac{aT^4}{3}, \qquad a = \frac{4\sigma}{c}$$

| Variabile | Significato |
|-----------|-------------|
| $P_{rad}$ | Pressione esercitata dalla radiazione [Pa] |
| $a = 7.566\times10^{-16}$ J m⁻³ K⁻⁴ | Costante di radiazione |

---

## 6. INTERNI STELLARI

### Equazioni della struttura stellare

#### Equilibrio idrostatico
$$\frac{dP}{dr} = -\frac{GM(r)\rho}{r^2}$$

#### Continuità della massa
$$\frac{dM}{dr} = 4\pi r^2\rho$$

#### Equilibrio termico
$$\frac{dL}{dr} = 4\pi r^2\rho\,\varepsilon$$

#### Trasporto radiativo
$$\frac{dT}{dr} = -\frac{3\kappa\rho}{16\pi acT^3}\frac{L(r)}{r^2}$$

| Variabile | Significato |
|-----------|-------------|
| $P(r)$ | Pressione totale (gas + radiazione) alla distanza $r$ dal centro [Pa] |
| $r$ | Distanza dal centro della stella [m] |
| $M(r)$ | Massa contenuta entro il raggio $r$ [kg] |
| $\rho(r)$ | Densità locale [kg m⁻³] |
| $G$ | Costante di gravitazione universale |
| $L(r)$ | Luminosità emergente dal guscio di raggio $r$ [W] |
| $\varepsilon$ | Tasso di generazione di energia per unità di massa [W kg⁻¹] |
| $\kappa$ | Opacità media (Rosseland) [m² kg⁻¹] |

---

### Gradiente adiabatico e criterio di Schwarzschild
$$\nabla_{ad} = \frac{\gamma-1}{\gamma} \qquad \text{(gas monoatomico: } \nabla_{ad}=0.4\text{)}$$
$$\nabla_{rad} > \nabla_{ad} \Rightarrow \text{convezione}$$
$$\nabla_{rad} = \frac{3\kappa L P}{16\pi acGMT^4}$$

| Variabile | Significato |
|-----------|-------------|
| $\nabla_{ad} = (d\ln T/d\ln P)_{ad}$ | Gradiente adiabatico: variazione di T con P in una bolla che sale adiabaticamente |
| $\nabla_{rad} = (d\ln T/d\ln P)_{rad}$ | Gradiente radiativo: gradiente necessario a trasportare tutto il flusso per sola irraggiamento |
| $\gamma = c_P/c_V$ | Indice adiabatico; gas biatomico: $5/3$; gas con ionizzazione: varia |

---

### Gas ideale
$$P = \frac{\rho kT}{\mu m_H}$$

| Variabile | Significato |
|-----------|-------------|
| $\mu$ | Peso molecolare medio (adimensionale): massa media per particella in unità di $m_H$ |
| $m_H = 1.673\times10^{-27}$ kg | Massa del protone (≈ massa dell'atomo di H) |

---

### Luminosità di Eddington
$$L_{Edd} = \frac{4\pi GMc}{\kappa_{es}}$$

| Variabile | Significato |
|-----------|-------------|
| $L_{Edd}$ | Luminosità limite oltre la quale la pressione di radiazione supera la gravità [W] |
| $\kappa_{es} \approx 0.034$ m² kg⁻¹ | Opacità per scattering di Thomson (elettroni liberi, composizione solare) |

---

### Reazioni nucleari

$$\varepsilon_{pp} \propto \rho T^4 \qquad \varepsilon_{CNO} \propto \rho T^{16\text{–}20}$$

| Variabile | Significato |
|-----------|-------------|
| $\varepsilon_{pp}$ | Tasso catena p-p: dominante in stelle con $M \lesssim 1.5\,M_\odot$, $T < 1.5\times10^7$ K |
| $\varepsilon_{CNO}$ | Tasso ciclo CNO: dominante in stelle massicce, fortissima dipendenza da $T$ |

---

### Tempo sulla sequenza principale
$$t_{MS} \approx 10^{10}\frac{M/M_\odot}{L/L_\odot} \text{ yr}$$

> Usando $L\propto M^{3.5}$: $t_{MS}\propto M^{-2.5}$. Stelle massicce vivono pochissimo!

---

## 7. EVOLUZIONE STELLARE

### Età di un ammasso dal punto di turn-off
$$t \approx 10^{10}\left(\frac{M_{TO}}{M_\odot}\right)^{-2.5} \text{ yr}$$

| Variabile | Significato |
|-----------|-------------|
| $M_{TO}$ | Massa al punto di turn-off: la massa delle stelle che stanno proprio abbandonando la MS oggi |

---

### Raggio di Schwarzschild
$$R_S = \frac{2GM}{c^2}$$

| Variabile | Significato |
|-----------|-------------|
| $R_S$ | Raggio di Schwarzschild: raggio entro cui la velocità di fuga supera $c$ (orizzonte degli eventi) [m] |
| $M$ | Massa del buco nero (o corpo collassato) [kg] |

---

### Masse limite per oggetti compatti

| Oggetto | Massa limite | Significato |
|---------|-------------|-------------|
| Nana bianca | $M_{Ch} \approx 1.44\,M_\odot$ | Massa di Chandrasekhar: limite superiore per nane bianche sostenute da pressione di degenerazione degli elettroni |
| Stella di neutroni | $M_{TOV} \approx 2\text{–}3\,M_\odot$ | Massa di Tolman-Oppenheimer-Volkoff: limite superiore per stelle di neutroni |

---

## 8. LA GALASSIA

### Velocità di rotazione
$$v^2(R) = \frac{GM(R)}{R}$$

| Variabile | Significato |
|-----------|-------------|
| $v(R)$ | Velocità di rotazione circolare a distanza $R$ dal centro galattico [km/s] |
| $R$ | Distanza dal centro galattico [kpc] |
| $M(R)$ | Massa totale contenuta entro $R$ [kg o $M_\odot$] |

---

### Legge periodo-luminosità delle Cefeidi
$$\langle M_V \rangle = -2.81\log_{10}(P/\text{d}) - 1.43$$

| Variabile | Significato |
|-----------|-------------|
| $\langle M_V \rangle$ | Magnitudine assoluta media nella banda V |
| $P$ | Periodo di pulsazione [giorni] |

---

## 9. COSMOLOGIA

### Legge di Hubble
$$v = H_0\,d$$

| Variabile | Significato |
|-----------|-------------|
| $v$ | Velocità di recessione della galassia [km/s] |
| $H_0$ | Costante di Hubble oggi [km/s/Mpc]; $H_0 \approx 70$ km/s/Mpc |
| $d$ | Distanza propria della galassia [Mpc] |
| $t_H = 1/H_0 \approx 14$ Gyr | Tempo di Hubble: stima dell'età dell'Universo |

---

### Equazioni di Friedmann
$$H^2 = \left(\frac{\dot{a}}{a}\right)^2 = \frac{8\pi G\rho}{3} - \frac{kc^2}{a^2} + \frac{\Lambda c^2}{3}$$
$$\frac{\ddot{a}}{a} = -\frac{4\pi G}{3}\left(\rho + \frac{3P}{c^2}\right) + \frac{\Lambda c^2}{3}$$

| Variabile | Significato |
|-----------|-------------|
| $H = \dot{a}/a$ | Parametro di Hubble (dipende dal tempo) [s⁻¹] |
| $a(t)$ | Fattore di scala cosmico (adimensionale); $a=1$ oggi, $a<1$ nel passato |
| $\dot{a}$ | Derivata temporale di $a$ |
| $\rho$ | Densità totale di energia/materia [kg m⁻³] |
| $P$ | Pressione del fluido cosmico [Pa] |
| $k$ | Curvatura spaziale: $k=0$ piatto, $k=+1$ chiuso, $k=-1$ aperto |
| $\Lambda$ | Costante cosmologica [m⁻²]: responsabile dell'espansione accelerata |

---

### Redshift cosmologico
$$1 + z = \frac{\lambda_{obs}}{\lambda_{em}} = \frac{a(t_{obs})}{a(t_{em})}$$

| Variabile | Significato |
|-----------|-------------|
| $z$ | Redshift cosmologico (adimensionale); $z=0$ oggi, $z>0$ nel passato |
| $\lambda_{obs}$ | Lunghezza d'onda osservata [m] |
| $\lambda_{em}$ | Lunghezza d'onda emessa [m] |
| $a(t_{obs})/a(t_{em})$ | Rapporto tra fattori di scala al momento di osservazione ed emissione |

---

### Parametri di densità
$$\Omega_m = \frac{\rho_m}{\rho_c}, \quad \Omega_\Lambda = \frac{\Lambda c^2}{3H^2}, \quad \Omega_k = -\frac{kc^2}{a^2H^2}$$
$$\Omega_m + \Omega_\Lambda + \Omega_k = 1$$

| Variabile | Significato |
|-----------|-------------|
| $\Omega_m$ | Parametro di densità della materia (ordinaria + oscura) |
| $\Omega_\Lambda$ | Parametro di densità dell'energia oscura (costante cosmologica) |
| $\Omega_k$ | Contributo della curvatura; $\Omega_k=0$ → universo piatto |
| $\rho_c = 3H^2/8\pi G$ | Densità critica: densità necessaria per avere $k=0$ [kg m⁻³] |

---

### Evoluzione della densità con $a$

| Componente | $\rho(a)$ | Motivo |
|------------|-----------|--------|
| Materia (polvere) | $\propto a^{-3}$ | Volume $\propto a^3$, masse invariate |
| Radiazione | $\propto a^{-4}$ | Volume $\propto a^3$ + redshift dell'energia ($E\propto a^{-1}$) |
| Costante cosmologica | $\rho = \text{const}$ | Proprietà del vuoto, non si diluisce |

---

### Distanze cosmologiche
$$d_C = \frac{c}{H_0}\int_0^z \frac{dz'}{E(z')}, \quad E(z) = \sqrt{\Omega_m(1+z)^3 + \Omega_\Lambda}$$
$$d_L = (1+z)\,d_C, \qquad d_A = \frac{d_C}{1+z}$$

| Variabile | Significato |
|-----------|-------------|
| $d_C$ | Distanza di comovimento: distanza "congelata" nell'espansione [Mpc] |
| $d_L$ | Distanza di luminosità: distanza che entra nella legge $F = L/4\pi d_L^2$ [Mpc] |
| $d_A$ | Distanza angolare: distanza che entra nella relazione $\theta = s/d_A$ [Mpc] |
| $E(z)$ | Funzione di Hubble normalizzata (adimensionale) |

---

### Equazione di stato
$$P = w\rho c^2$$

| Componente | $w$ |
|------------|-----|
| Materia fredda | $0$ |
| Radiazione | $1/3$ |
| Energia oscura ($\Lambda$) | $-1$ |

---

## COSTANTI FONDAMENTALI

| Costante | Simbolo | Valore | Unità |
|----------|---------|--------|-------|
| Velocità della luce | $c$ | $2.998 \times 10^8$ | m/s |
| Costante di Planck | $h$ | $6.626 \times 10^{-34}$ | J·s |
| $\hbar = h/2\pi$ | | $1.055 \times 10^{-34}$ | J·s |
| Costante di Boltzmann | $k_B$ | $1.381 \times 10^{-23}$ | J/K |
| Stefan-Boltzmann | $\sigma$ | $5.671 \times 10^{-8}$ | W m⁻² K⁻⁴ |
| Costante gravitazionale | $G$ | $6.674 \times 10^{-11}$ | N m² kg⁻² |
| Massa del protone | $m_p$ | $1.673 \times 10^{-27}$ | kg |
| Massa dell'elettrone | $m_e$ | $9.109 \times 10^{-31}$ | kg |
| Carica elementare | $e$ | $1.602 \times 10^{-19}$ | C |
| Costante di Wien | $b$ | $2.898 \times 10^{-3}$ | m·K |
| Costante di Rydberg | $R_H$ | $1.097 \times 10^7$ | m⁻¹ |
| u.m.a. | $u$ | $1.661 \times 10^{-27}$ | kg |
| Costante di radiazione | $a=4\sigma/c$ | $7.566 \times 10^{-16}$ | J m⁻³ K⁻⁴ |
| 1 eV | | $1.602 \times 10^{-19}$ | J |

---

## PARAMETRI SOLARI E ASTRONOMICI

| Quantità | Simbolo | Valore |
|----------|---------|--------|
| Massa Sole | $M_\odot$ | $1.989 \times 10^{30}$ kg |
| Raggio Sole | $R_\odot$ | $6.957 \times 10^8$ m |
| Luminosità Sole | $L_\odot$ | $3.828 \times 10^{26}$ W |
| Temperatura eff. Sole | $T_\odot$ | $5778$ K |
| Magnitudine bol. Sole | $M_{bol,\odot}$ | $4.74$ |
| 1 Unità Astronomica | AU | $1.496 \times 10^{11}$ m |
| 1 Parsec | pc | $3.086 \times 10^{16}$ m = 3.262 ly |
| 1 Anno luce | ly | $9.461 \times 10^{15}$ m |
| 1 Anno | yr | $3.156 \times 10^7$ s |
| Dist. Sole–Centro Galattico | $R_0$ | $\approx 8.5$ kpc |
| Velocità Sole in Galassia | $v_0$ | $\approx 220$ km/s |
| Periodo orb. Sole | $P_\odot$ | $\approx 225$ Myr |
| Densità critica ($H_0=70$) | $\rho_c$ | $9.47\times10^{-27}$ kg/m³ |
| Temperatura CMB oggi | $T_{CMB}$ | $2.725$ K |
