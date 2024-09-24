# Yang-Lee edge singularity <!-- .element: class="r-fit-text" -->

# with functional renormalization group  <!-- .element: class="r-fit-text" -->

Vladi Skokov

North Carolina state University





---

## Outline

- Introduction: what is Yang-Lee Edge (YLE) singularity?
  - Second order phase transition 
  - Universal magnetic equation of state 
  - Analytic structure near a critical point
  - YLE and spinodals
  - Why no results on YLE for about five decades? 

- Universal location of YLE for  most relevant universality classes 
  - FRG to locate YLE 
  - Analysis of systematic uncertainty 

- Tracing YLE in QCD 
  - Roberge-Weiss phase transition 
  - Critical end point 

- Conclusions 


---

### QCD phase diagram 

- This talk is about universal properties near a second order phase transition 

- Motivation: QCD phase diagram

<img src="img/phase.png" width="55%">

The only phase diagram of Standard Model of fundamental particles that can be studied in laboratory  

---

### Analytic continuation 


<div class="container">

<div class="col" data-markdown>

- Lattice MC is one of the leading methods to study QCD

- Sign problem limits utility of the method to zero _real_ baryon chemical potential:
  - Taylor series expansion at $\mu_B =0$ 
  - Calculations at purely imaginary $\mu_B$ 


- To learn about _real_ baryon chemical potential: analytic  continuation
</div>

<div class="col" data-markdown>

<img  src="img/qcdpd.png" width="70%">

</div>

</div>


- Analytic continuation requires  knowledge of analytic structure 

- Reversely, analytic structure can help reveal QCD phase structure 

- Thus, there is an important question to consider




---

### Are there singularities  associated <!-- .element: class="r-fit-text" -->


###  with critical point/phase transitions?  <!-- .element: class="r-fit-text" -->


---

### Second-order phase transition:  Landau model

- To set up the stage, introduce  notation and relevant concepts, best to consider Landau model 



`\[ F = \int d^{d} x \left(  \frac{1}{2} {\color{red} t} \phi^2 + \frac{1}{4}  \lambda \phi^4 - {\color{blue} h} \phi   \right) \]`

E.g.: 

- near chiral limit: ${\color{red} t} \propto T-T_c + \kappa \mu^2$, ${\color{blue} h}\propto m_{u,d}$
- near CP: ${\color{red}t},{\color{blue}h} \propto \alpha_{t,h}(T-T_c) + \beta_{t,h} (\mu-\mu_c)$
- near RW: ${\color{red}t} \propto T-T_{RW}$, ${\color{blue}h}\propto \mu_B - i \pi T$

--

### Vary $h$

<img src="img/isingvh.png" width="42.5%">
<img src="img/firstorderising.png" width="40%">

--

### Vary $t$

<img src="img/isingpdvt.png" width="42.5%">
<img src="img/secondorderising.png" width="40%">

--

### Magnetic equation of state

`\[ F = \int d^{d} x \left(  \frac{1}{2} t \phi^2 + \frac{1}{4}  \lambda \phi^4 - h \phi   \right) \]`

<div class="container">

<div class="col" data-markdown>

Minimize $F[\phi]$ $\leadsto$ equilibrium order parameter:

- Arbitrary $t$ and $h$: $t \phi + \lambda \phi^3 = h$
- Simplify: $\lambda\to1$: $t \phi + \phi^3 = h$
- Ansatz for the solution $\phi = h^{1/3} {\color{Emerald}f_G}$

$t h^{1/3} {\color{Emerald}f_G}  + h {\color{Emerald}f_G}^3 = h$ or
${ \color{red}{\frac{t}{ h^{2/3}}} } {\color{Emerald}f_G}  + {\color{Emerald}f_G}^3 = 1$



</div>

<div class="col" data-markdown>

<img class="fragment fade-in"  data-fragment-index="1"  src="img/meos.png" width="70%">

</div>

</div>
- Scaling form of ${\color{Emerald} \text{magnetic equation of state}}$ ($\beta = 1/2, \delta=3$)
  $${\color{Emerald} f_G} ( {\color{red}{z}}  + {\color{Emerald}f_G}^2) = 1, \quad {\color{red}{ z  =  {\frac{t}{ h^{\frac1{\beta \delta}} }} } }$$
--

### Yang-Lee edge singularity

<img src="img/fg3d.png">


--

### Near YLE singularity:  $\frac{\partial^2 F}{\partial \phi^2} = 0 $

- $f_G$ is singular
  $$f_G - f_G^c \propto (z-z_c)^{\color{red}{\sigma_{\rm YLE}}} $$

- Critical exponent ${\color{red}{\sigma_{\rm YLE}}}$ is independent of the
  underlying universality class (for O(N), $\sigma_{\rm YLE}$ is $N$-independent); superuniversality 

- From conformal bootrstrap, $\color{red}{\sigma^{d=3}_{\rm YLE}} = 0.085(1)$

- Mean-field approximation gets it wrong:
  ${\sigma^{\rm MF}_{\rm YLE}} = \frac12$

- Mean-field approximation also does not get correct $z_c$   

- $z_c$ is universal: for $O(N)$, $z_c$ depends only on $N$ and $d$

</div>

---

| Type of critical point:       | <p class="fragment fade-in" data-fragment-index="2"> ${\color{red} \text{protocritical = YLE}}$ </p> | critical | tricritical |
| ----------------------------- | ----------------------------------------------------------------------------- | -------- | ----------- |
| Number of relevant variables: | <p class="fragment fade-in" data-fragment-index="1">  1              | 2        | 4           |

 <p class="fragment fade-in" data-fragment-index="2"> 1 independent crit. exp., c.f.  standard critical point with 2 independent crit. exp. </p>

--


### Illustration in Ising model: $h_c(t) = i |z_c|^{-\beta \delta} t^{\beta \delta}$  

<img src="img/complexfg.png"  width=46.5%>
<img src="img/complexfgBM.png"  width=45%>

<div class="cite">
F. Rennecke, G. Johnson, and V.S.,     Phys.Rev.D 107 (2023) 11, 116013
</div>

- In contrast to the critical point, YLEs form lines
- YLEs are continuously connected to critical point
- On YLE lines, the mass of the critical  mode  is zero 


---

### Universal location of YLE

- The phase of $z_c = |z_c| e^{\pm \frac{i \pi}{2 \beta \delta}}$ is defined by
  the critical exponents of the underlying universality class.  

- How to determine $|z_c|$?  


- Ordinary, two methods: 

  - $\varepsilon$-expansion 

  - lattice


--

###  $\varepsilon$-expansion to locate YLE  ⛔
     


 - Ordinary, $\varepsilon$-expansion is equivalent to  loop expansion; e.g.    
    $$
      \beta = \frac{1}{2} + \frac{1}{6} \varepsilon  + \frac{1}{162} \varepsilon^2 + \frac{1}{2} \left( \frac{163}{8748} - \frac{2}{27} \zeta(3) \right) \varepsilon^3 + {\cal O}(\varepsilon^4), \quad \epsilon = 4 - d 
    $$

- Ginzburg-Landau theory near YLE: $\phi = \phi_{\rm YLE} + \varphi$: 

$$ L \approx (\nabla \varphi)^2  - \lambda \phi_{\rm YLE}\   {\color{red}\varphi^3}   - H \varphi   $$


- YLE is described by ${\color{red}\varphi^3}$ with upper critical dimension ${\color{red} d_c=6}$, </br> 
 while underlying universality class  ($\phi^4$) has $d_c=4$
<div class="cite"> M. Fisher, “Yang-Lee Edge Singularity and φ3 Field Theory”, Phys. Rev. Lett. 40 1610 (1978) </div>

- Only *leading correction* is under perturbative control; </br> 
expansion in $\varepsilon \ne$ expansion in loops 

$$
|z_c| \approx  |z_c^{\rm MF}| \left[1 +  \frac{ 27 \ln \left(\frac{3}{2}\right) -  (N-1)  \ln 2}{9
(N+8)}\epsilon \right] + \epsilon^2 \log \epsilon \times  ( \text{all loops} ) 
$$





--

### Lattice  ⛔
     
- Direct calculations at complex values of parameters are impossible
    due to sign problem
- Indirectly lattice can provide information about YLE through analytic continuation 

</p>    
<div class="cite"> E.g.  through Schofield representation in  F. Karsch, C. Schmidt, S. Singh, 2311.13530 </div>


--


FRG approach is <!-- .element: class="r-fit-text" -->

uniquely  suited <!-- .element: class="r-fit-text" -->

for locating YLE  ✅   <!-- .element: class="r-fit-text" -->

--

### FRG ✅ 


- No sign problem 
- Non-perturbative 
- Working near second-order critical point $\leadsto$ justified truncation scheme 
- Validated by computing critical exponents and amplitude ratios

| $N=1, d=3$  | $\nu$        | $\eta$ |
|---|-------------|--|            
|FRG|0.63012(16)   | 0.0361(11) | 
|CB|         0.629971(4)      | 0.0362978(20) |

<div class="cite"> G. De Polsi, I. Balog, M. Tissier, N. Wschebor, 2001.07525   </div>
<div class="cite"> G. De Polsi, G. Hernández-Chifflet, N. Wschebor, 2109.14731   </div>

- As a bonus: calculations are possible at any $d$ and $N$ (including non-integer). 


---

### Functional/Exact Renormalization Group

- Start with bare classical action at small distances/large momentum
  $S_{k=\Lambda}$
- Gradually include fluctuations of larger size/smaller momentum
- Continue until fluctuations of all possible sizes/momenta are accounted for

<img src="img/frg.png" width=15% >

- Equation that does it: Functional Renormalization Group equation
  $$
  \partial_k \Gamma_{k}[\phi] = \frac{1}{2} {\rm STr} \Big[ \big( \Gamma^{(2)}_{k}[\phi] + R_k \big)^{-1} \cdot \partial_k R_k  \Big]
  $$

<div class="cite"> Wetterich, 1993</div>




--


### Truncation: derivative expansion

Wave function renormalization:

$$
\begin{aligned}
 \partial_t Z_{\parallel}(\phi) &= \int \bar d^d q \partial_t R_k(q^2) \Bigg\\{ G_\parallel^2 \Big[ \gamma_\parallel^2 \big(G_\parallel' + 2 G_\parallel'' \frac{q^2}{d}\big) 2 \gamma_\parallel Z_\parallel'(\phi) \big(G_\parallel + 2 G_\parallel' \frac{q^2}{d}\big) \\\\
& + (Z_\parallel'(\phi))^2 G_\parallel \frac{q^2}{d} \frac12 Z''_\parallel(\phi) \Big]
\\\\ & + (N-1) G^2\_{\perp} \Big[ \gamma_\perp^2 \big(G_\perp' + 2 G_\perp'' \frac{q^2}{d}\big) 4 \gamma_\perp Z_\perp'(\phi)  G_\perp' \frac{q^2}{d} (Z_\perp'(\phi))^2 G_\perp \frac{q^2}{d}
\\\\ &+  2 \frac{Z_\parallel(\phi)-Z_\perp(\phi)}{\phi} \gamma_\perp G_\perp \frac12 \left(\frac{1}{\phi}Z'_\parallel(\phi) \frac{2}{\phi^2} (Z_\parallel-Z_\perp) \right) \Big] \Bigg\\}
\end{aligned}
$$

<div class="smallmath">

with
$
\gamma_\parallel = q^2 Z_\parallel'(\phi) + U^{(3)}(\phi),  \quad \gamma_\perp = q^2 Z_\perp'(\phi) + \frac{\partial}{\partial \phi} \left( \frac{1}{\phi}U' (\phi) \right), \quad G' = \frac{\partial G} {\partial q^2}, \ldots
$

</div>

<div class="cite">
G. Johnson, F. Rennecke, and V.S., Phys.Rev.D 107 (2023) 11,
116013
</div>


--

### Truncation: series expansion

- Taylor series expansion of $U_k(\phi)$ and $Z_k(\phi)$ truncated at  $(N_U, N_Z) = (12,6)$

  - Usually: expansion near $k$-dependent minimum: $U_k'[\phi_k] = h =$
    const.

  - To locate YLE: expand near $U_k''[\phi_k] = m^2 \to 0$.

    $\leadsto$ $U_k'[\phi_k] = h_k \ne$ const

    $\leadsto$ Calculations in the broken phase are not feasible



- Uncertainty due to the truncation dependence ($\Delta_{trunc}$) is estimated by the maximum of the differences between  $|\zeta_c|$  computed at orders $(12,6) - (10,6)$ and   $(12,6) - (12,4)$  


--
### After the truncation 

- 18-26 coupled stiff differential equations

  - Mathematica to obtain equations (multiple Gb)

  - Implicit solvers for ODE's

  - Months on an HPC


--
### Regulator dependence \& minimal sensitivity 1

- To estimate the systematic uncertainty of truncations:  include  a free parameter in the regulator 

$$
    R_k(q^2) = {\color{red} a} Z^{\\|}_k (k^2 - q^2) \theta(k^2-q^2)
$$


<img src="img/msa.png" width=100% >

<div class="smallmath">
$\Delta = \beta \delta$ is the gap critical exponent (defines the phase of $z_c$)
</div>


--

### Regulator dependence \& minimal sensitivity 2

- $a_\\Delta$ and $a_\eta$ might not be the most crucial as long as $|z_c|$ is concerned 

- Additionally, we perform minimal sensitivity analysis for  $h_c$ ($z_c = t / h_c^{1/\Delta}$) 


| N                              | 1      | 2       | 3      | 4      |
| ---- | ------ | ------- | ------ | ------ |
| $a_\\Delta$                       | 0.5108 |  0.5069 | 0.5026 | 0.5044 |
| $a_\\eta$                         | 0.5044 | 0.5075 | 0.5064 | 0.4906  |
| $a_h$                            | 0.6299 | 0.5921   | 0.5724  | 0.5617 |



- Uncertainty due to the regulator dependence ($\Delta_{reg}$) is estimated by the difference between  $|\zeta_c|$  computed at $a_\\Delta$ and $a_h$ 


--

### Results: importance of fluctuations ($N$=1)

<img src="img/etaevo.png" width=65% >

<div class="cite">
F. Rennecke and V. S, Annals Phys. 444 (2022) 169010

</div>

---

### Results: Ising universality class $N=1$

$d$ does not have to be integer in FRG

<img src="img/FRG_8_4.png" width=45% >

| d                                | 1   | 2          | 3        | 4           |
| -------------------------------- | --- | ---------- | -------- | ----------- |
| $ \| z_c \| /R\_\chi^{1/\gamma} (N_{trunc})$ | 1   | 1.32504(2) | 1.621(4) | $3/2^{2/3}$ |

<div class="cite">
G. Johnson, F. Rennecke, and V. S, Phys.Rev.D 107 (2023) 11,
116013 <br>
F. Rennecke and V. S, Annals Phys. 444 (2022) 169010 <br>
A. Connelly, G. Johnson, F. Rennecke, and V. S, Phys.Rev.Lett. 125 19, 191602
(2020) <br>
$d=2$: H.-L. Xu and A. Zamolodchikov, JHEP 08 (2022) 057 H.-L. Xu and A.
Zamolodchikov, 2304.07886

</div>

---

### Arbitrary $N$, $d=3$

<img src="img/zeta.png" width=45% >

| N                                | 1           | 2           | 3           | 4           | 
| -------------------------------- | ----------- | ----------- | ----------- | ----------- |
| $ \| z_c \| /R\_\chi^{1/\gamma} (N_{trunc}) (N_{reg})$ | 1.621(4)(1) | 1.612(9)(0) | 1.604(7)(0) | 1.597(3)(0)  |

<div class="cite">
G. Johnson, F. Rennecke, and V. S, Phys.Rev.D 107 (2023) 11,
116013 <br>
c.f. F. Karsch, C. Schmidt, and S. Singh Phys.Rev.D 109 (2024) 1, 014508

</div>

---


### Analytic structure in QCD: $T_c<T<T_{RW}$


<img src="img/YLEs.png" height=500em >



--


### Analytic structure in QCD: $T\to T_c$


<img src="img/YLEtoTc.png" height=500em >




--


### Analytic structure in QCD: $T\to T_{RW}$


<img src="img/YLEtoRW.png" height=500em >






---
### Tracing YLE singularity: RW critical point 


Lattice QCD and indirect methods to locate YLE: 

input from  Im $\mu$  \& analytic continuation 


<img src="img/RW_YLE.png" height=350em >

$$
  z = z_c \to \text{Re} \mu_{YLE} \propto (T_{RW}-T)^{\beta \delta} \quad \leadsto T_{RW} = 211.1 \pm 3.1 \text{MeV}.
$$

<div class="cite">
Christian Schmidt, et. al., 2401.07790
</div>



---
### Tracing YLE singularity: chiral critical point  


Lattice input from Taylor series coeff. at $\mu=0$ or  Im $\mu$  \&  analytic continuation 

<div class="r-stack">

<div class="fragment fade-out"  data-fragment-index="1"  >
<img src="img/BasarYLE.png" height=350em >
<img src="img/LatticeYLElocation.png" height=350em >
<div class="cite">
G. Basar, 2312.06952 <br>
D. Clarke et. al., 2405.10196
</div>
</div>
<img class="fragment current-visible" data-fragment-index="1" src="img/clarke.png" height=350em >
</div>



<div class=smallmath>
$$ z=z_c \to \text{Re} (\mu-\mu_c) = c_1 (T-T_c) + c_2 (T-T_c)^2  \text{ and }  \text{Im} \mu = c_3 (T-T_c)^{\beta\delta}
$$
$$
\leadsto 
T_c \approx 110 \text{ MeV} , \mu_c \approx 650 \text{ MeV}$$ 
</div>

--

### Taking it further 

- Properties of YLE, e.g. $\sigma_{\rm YLE}$ can be use to validate indirect
  methods of locating YLE in QCD, e.g. volume scaling of the density of zeros

- Moreover,

  - YLE defines the behavior of the higher order Taylor expansion coefficients
    (Darboux's theorem). E.g. for of $f_G(z)$:

    <div class="smallmath">
    $$
    f_G^{(n)} \sim 2 B_0 {\red{|z_c|}}^{-n} \frac{n^{ \red \sigma -1 }}{\Gamma(\red \sigma  )}  \cos \left(\beta_0 - {\red{\frac{\pi n}{2\beta \delta}}  } \right),
    \quad B_0 \exp (i \beta_0) = \lim\limits_{z\to z_c}  \frac{ f_G(z)-f_G(z_c)}
    {(1-z/z_c)^{\sigma} }
    $$
</div>

  - Fourier coefficients are exponentially sensetive to YLE

    $$
    b_{k\gg1} \approx \|\tilde A_{\rm YLE}\| \frac{e^{-\hat \mu_r^{\rm YLE} k }}{k^{1+\sigma}} \cos(\hat \mu_i^{\rm YLE} k + \phi^{\rm YLE}_a)
    $$

$$
     +\|\hat A_{\rm RW}\|  (-1)^k \frac{e^{-\hat \mu_r^{\rm RW} k }}{k^{1+\sigma}}
    $$
<div class="cite">
 M. Bryant, C. Schmidt, V. S., 2401.06489 
</div>
--

### Fourier coefficients

<img src="img/FTfits.png" height=350em >

<div class="cite">
 M. Bryant, C. Schmidt, V. S., 2401.06489 
</div>


---

### Conclusions

- Every second order phase transition comes with Yang-Lee edge singularity. In the "crossover" region, there is a singularity in the complex plane
- Universal location of YLE was one of not many unknown universal quantities
  - FRG is uniquely positioned to determine the universal location of YLE with precision. In our work, $d>2.7$ and arbitrary $N$
  - Xu and Zamolodchikov determined location of YLE in Ising Field Theory, $d=2$
    and $N=1$
- To map universal location to QCD, one requires non-universal metric factors.
  They are generically are not known
- Nevertheless properties of YLE singularities might be useful in establishing
  existence/location of QCD critical point
  - YLE is continuously connected to critical point 
  - Two distinct approaches based on lattice input from Taylor coefficients and imaginary $\mu$ $\leadsto$ approximately the same $T_c$ 
  - Associated analytic structure of complex $\mu$-plane constraints the
    behaviour of Fourier coefficients
