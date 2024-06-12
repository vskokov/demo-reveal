# Yang-Lee Edge singularity and <!-- .element: class="r-fit-text" -->

# and the structure of QCD phase diagram <!-- .element: class="r-fit-text" -->

Vladi Skokov

North Carolina state University

---

### QCD Phase diagram

<img src="img/phase.png" width="50%">

- Experiment with relativistic heavy ions: the system is small and has a short
  lifetime
- Theory: although the underlying theory (QCD) is known, we cannot solve it
  &cross;
- Numerical methods: zero density region only due to the ``sign'' problem
  &cross;
- Indirect methods: Taylor series coefficients/imaginary $\mu$ $\to$ non-zero
  baryon density &check;

<span style="font-size:0.8em;">

`\[  p/T^4 = \sum_{n=0}^{\infty} \frac{  \chi_n }{n!}\left(\frac{\mu}{T}\right)^n;  \quad  \chi_n = \frac{ \partial^n(p/T^4)} { \partial\ (\mu/T)^n}  \quad     {\color{gray}  \chi_2 =  \frac{ \langle (\delta N)^2 \rangle   }{VT^3}     \quad   \chi_4 = \frac{ \langle (\delta N)^4 \rangle  -  3 \langle (\delta N)^2 \rangle^2  }{VT^3}}  \]`

</span>

---

### Taylor series expansion

- Consider an arbitrary function expanded around a regular point
  $$f(x) = \sum_{n=0}^{\infty} \frac{1}{n!}  f_n x^{n}$$
- What limits the predictive power of this expansion?

<div class="r-stack">

<img class="fragment fade-in-then-out" data-fragment-index="0" src="img/expans.png" width="40%" />

<img  class="fragment fade-in-then-out" data-fragment-index="1" src="img/func3d.png" width="40%" />

<span  class="fragment fade-in"  data-fragment-index="2" >

$$|x| < R_c \equiv \left(  \lim_n \sup \left| f_n^{1/n} \right| \right)^{-1}$$

- $R_c$ is the radius of convergence
- $R_c =$ distance in the _complex_ plane from the expansion point to the
  nearest singularity

</span>
</div>

---

### Are there singularities associated with critical point/phase transitions?

---

### Example: Landau free energy

`\[ F = \int d^{d} x \left(  \frac{1}{2} t \phi^2 + \frac{1}{4}  \lambda \phi^4 - h \phi   \right) \]`

Parameters can be:

- near chiral limit: $t \propto T-T_c + \kappa \mu^2$, $h\propto m_{u,d}$
- near CP: $t,h \propto \alpha_{t,h}(T-T_c) + \beta_{t,h} (\mu-\mu_c)$
- near RW: $t \propto T-T_{RW}$, $h\propto \mu_B - i \pi T$

--

### Vary $h$

<img src="img/LandauPD.png" width="42%">
<img src="img/LandauFE.png" width="40%">

--

### Vary $t$

<img src="img/LandauPD.png" width="42%">
<img src="img/LandauFE2.png" width="40%">

--

### Magnetic equation of state

`\[ F = \int d^{d} x \left(  \frac{1}{2} t \phi^2 + \frac{1}{4}  \lambda \phi^4 - h \phi   \right) \]`

Minimize $F[\phi]$ $\leadsto$ equilibrium order parameter:

- Arbirary $t$ and $h$: $t \phi + \lambda \phi^3 = h$
- Simplify $\lambda\to1$: $t \phi + \phi^3 = h$
- Ansatz for the solution $\phi = h^{1/3} f_G$

$t h^{1/3} f_G  + h f_G^3 = h$ or $\frac{t}{ h^{2/3}} f_G  + f_G^3 = 1$

- Scaling form of "magnetic equation of state"
  $$f_G ({z}  + f_G^2) = 1, \quad {\color{red} z}  =  {\frac{t}{ h^{\frac1{\beta \delta}} }} \quad\text{with} \quad  \beta = 1/2, \delta=3$$

---

#### Sample math

`\[     \begin{aligned}         M &= B_c {\hat h}^{1/\delta}, \quad \hat t=0, \\         M &= B (-\hat t)^\beta, \quad \hat H=0 \quad \text{and} \quad  \hat t<0\,.       \end{aligned} \]`<!-- .element: class="r-fit-text" -->

`\[     \begin{aligned}     \Gamma_k  = \int d^dx  \left[  \frac{1}{2} Z_k(\rho)\,  \partial^\mu \phi_a \partial_\mu \phi_a  +  \frac{1}{4} Y_k(\rho) \,  \partial^\mu \rho \partial_\mu \rho  + U_k(\rho) \right]\,,     \end{aligned} \]`

  <!-- .element: class="r-fit-text" -->

---

### Sample list

- Why YLE?
- Analytic structure
- more
- more

---

### Sample figure

![z](https://inspirehep.net/files/66674c85c2204835d6588978249abf9d)<!-- .element: class="r-fit-text" -->

---

### Sample columns

<div class="container">

<div class="col" data-markdown>

- a
- b
- c

</div>

<div class="col" data-markdown>

![z](https://inspirehep.net/files/66674c85c2204835d6588978249abf9d) some
comments

</div>
</div>

---

### Sample columns 2

<div class="half-part" data-markdown>

- a
- b
- c

</div>

<div class="half-part" data-markdown>

![z](https://inspirehep.net/files/66674c85c2204835d6588978249abf9d) some

</div>
