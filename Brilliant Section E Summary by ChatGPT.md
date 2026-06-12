
Assuming you mean **new IB Physics Topic E: Nuclear and quantum physics**, not old Option E Astrophysics. The current Topic E is: **E1 atomic structure, E2 quantum physics HL only, E3 radioactive decay, E4 fission, E5 fusion and stars**; IB lists Topic E as **23 hours SL / 39 hours HL**. ([Peda.net](https://peda.net/kuopio/lukiot/lyseonlukio/ib/syllabukset/group-4-sciences/physics-2025.pdf%3Afile/download/c56a8c8592e847bbb555540b087b0990d1ade5b0/Physics%2C%202025.pdf "Physics guide"))

# Topic E in one sentence

Most of Topic E is this:

> **Energy is quantized in atoms, nuclear stability depends on binding energy, unstable nuclei decay statistically, and nuclear reactions release energy when products are more tightly bound.**

Once you understand that, the formulas become much easier.

---

# E1 — Structure of the atom

## 1. Rutherford scattering

Alpha particles are fired at thin gold foil.

Observed:

|Observation|Conclusion|
|---|---|
|Most α-particles pass straight through|Atom is mostly empty space|
|Some are deflected|Positive charge is concentrated|
|Very few bounce back|There is a tiny, dense, positively charged nucleus|

For SL, this is mostly qualitative. For HL, you may calculate closest approach.

At closest approach, the alpha particle’s kinetic energy is converted into electric potential energy:

$$
E_k=\frac{1}{4\pi\epsilon_0}\frac{(2e)(Ze)}{r}
$$
So:

$$
r=\frac{1}{4\pi\epsilon_0}\frac{2Ze^2}{E_k}
$$
This gives an upper estimate for nuclear radius.

---

## 2. Nuclear notation

$$
{}^A_ZX
$$
where:

$$
A = \text{nucleon number} = p+n
$$
$$
Z = \text{proton number}
$$
$$
n = A-Z
$$
Example:

$$
{}^{235}_{92}\text{U}
$$
has 92 protons and $235-92=143$ neutrons.

**Isotopes** have the same $Z$, different $A$. Same element, different neutron number.

---

## 3. Emission and absorption spectra

Atoms have **discrete energy levels**. Electrons cannot have arbitrary energies.

When an electron drops from high to low energy:

$$
\Delta E = hf = \frac{hc}{\lambda}
$$
It emits a photon.

When an electron absorbs a photon, it moves up only if the photon energy exactly matches an allowed energy gap.

So:

|Process|What happens|Spectrum|
|---|---|---|
|Emission|Electron falls down|Bright lines|
|Absorption|Electron jumps up|Dark lines|

Each element has unique energy levels, so each element has a unique spectral fingerprint. This is why spectra can identify chemical composition. ([Peda.net](https://peda.net/kuopio/lukiot/lyseonlukio/ib/syllabukset/group-4-sciences/physics-2025.pdf%3Afile/download/c56a8c8592e847bbb555540b087b0990d1ade5b0/Physics%2C%202025.pdf "Physics guide"))

---

## 4. HL: Nuclear radius

$$
R = R_0 A^{1/3}
$$
where usually:

$$
R_0 \approx 1.2\times10^{-15}\text{ m}
$$
Important consequence:

$$
V \propto R^3 \propto A
$$
Mass is also proportional to $A$, so nuclear density is roughly constant for all nuclei.

Typical problem:

> Find density of a nucleus.

Use:

$$
\rho=\frac{m}{V}
$$
with:

$$
m \approx A u
$$
and:

$$
V=\frac{4}{3}\pi R^3
$$
---

## 5. HL: Bohr model of hydrogen

Hydrogen energy levels:

$$
E_n = -\frac{13.6}{n^2}\text{ eV}
$$
The negative sign means the electron is bound. Higher $n$ means less negative, so higher energy.

Photon emitted/absorbed:

$$
\Delta E = E_{\text{final}} - E_{\text{initial}}
$$
Use magnitude for photon energy:

$$
E_\gamma = |\Delta E|
$$
Then:

$$
E_\gamma = hf = \frac{hc}{\lambda}
$$
Bohr angular momentum quantization:

$$
mvr = \frac{nh}{2\pi}
$$
This is the reason only certain orbits are allowed. IB explicitly includes Bohr energy levels and angular momentum quantization for HL. ([Peda.net](https://peda.net/kuopio/lukiot/lyseonlukio/ib/syllabukset/group-4-sciences/physics-2025.pdf%3Afile/download/c56a8c8592e847bbb555540b087b0990d1ade5b0/Physics%2C%202025.pdf "Physics guide"))

---

# E2 — Quantum physics, HL only

E2 is basically: **light behaves like particles, matter behaves like waves.**

## 1. Photons

Photon energy:

$$
E = hf = \frac{hc}{\lambda}
$$
Photon momentum:

$$
p=\frac{h}{\lambda}
$$
Higher frequency means higher energy. Shorter wavelength means higher energy.

---

## 2. Photoelectric effect

Light hits a metal. Electrons may be emitted.

Einstein’s equation:

$$
hf = \Phi + E_{k,\max}
$$
So:

$$
E_{k,\max}=hf-\Phi
$$
where:

$$
\Phi = \text{work function}
$$
The work function is the minimum energy needed to remove an electron from the metal.

Threshold frequency:

$$
f_0=\frac{\Phi}{h}
$$
If $f<f_0$, no electrons are emitted, no matter how intense the light is.

Stopping potential:

$$
E_{k,\max}=eV_s
$$
So:

$$
eV_s = hf-\Phi
$$
Common graph:

$$
E_{k,\max} \text{ vs } f
$$
has gradient $h$, x-intercept $f_0$, y-intercept $-\Phi$.

Very important conceptual distinction:

|Change|Effect|
|---|---|
|Increase frequency|increases max kinetic energy|
|Increase intensity|increases number of emitted electrons/current|
|Frequency below threshold|no emission|
|Higher work function|harder to emit electrons|

Classical wave theory fails because it predicts energy depends on intensity, emission should be delayed at low intensity, and any frequency should eventually eject electrons. Experimentally, none of that happens. IB specifically expects you to discuss why classical wave theory cannot explain photoelectric observations. ([Peda.net](https://peda.net/kuopio/lukiot/lyseonlukio/ib/syllabukset/group-4-sciences/physics-2025.pdf%3Afile/download/c56a8c8592e847bbb555540b087b0990d1ade5b0/Physics%2C%202025.pdf "Physics guide"))

---

## 3. Matter waves

de Broglie wavelength:

$$
\lambda=\frac{h}{p}
$$
For non-relativistic particles:

$$
p=mv
$$
so:

$$
\lambda=\frac{h}{mv}
$$
If an electron is accelerated through a potential difference $V$:

$$
eV=\frac12mv^2
$$
so:

$$
p=\sqrt{2meV}
$$
therefore:

$$
\lambda=\frac{h}{\sqrt{2meV}}
$$
Matter diffraction is evidence that particles have wave-like properties.

---

## 4. Compton scattering

A photon scatters off an electron. The photon loses energy, so its wavelength increases.

$$
\Delta \lambda = \lambda_f-\lambda_i
$$
$$
\Delta \lambda = \frac{h}{m_ec}$1-\cos\theta$
$$
Special cases:

|Angle|Result|
|---|---|
|$\theta=0^\circ$|no wavelength shift|
|$\theta=90^\circ$|$\Delta\lambda=\frac{h}{m_ec}$|
|$\theta=180^\circ$|maximum shift $2\frac{h}{m_ec}$|

IB includes Compton scattering as further evidence for the particle nature of light, but not the derivation. ([Peda.net](https://peda.net/kuopio/lukiot/lyseonlukio/ib/syllabukset/group-4-sciences/physics-2025.pdf%3Afile/download/c56a8c8592e847bbb555540b087b0990d1ade5b0/Physics%2C%202025.pdf "Physics guide"))

---

# E3 — Radioactive decay

E3 is about unstable nuclei and exponential decay.

## 1. Binding energy and mass defect

A nucleus has lower mass than its separated protons and neutrons.

Mass defect:

$$
\Delta m = Zm_p + Nm_n - m_{\text{nucleus}}
$$
Binding energy:

$$
E_b = \Delta mc^2
$$
Binding energy is the energy required to completely separate the nucleus into individual nucleons.

Binding energy per nucleon:

$$
\frac{E_b}{A}
$$
This measures nuclear stability.

Higher binding energy per nucleon = more stable.

The curve peaks around iron/nickel. Therefore:

|Region|Energy-releasing process|
|---|---|
|Light nuclei|fusion|
|Heavy nuclei|fission|

because both move products toward higher binding energy per nucleon.

IB explicitly includes mass defect, binding energy, and the binding-energy-per-nucleon curve. ([Peda.net](https://peda.net/kuopio/lukiot/lyseonlukio/ib/syllabukset/group-4-sciences/physics-2025.pdf%3Afile/download/c56a8c8592e847bbb555540b087b0990d1ade5b0/Physics%2C%202025.pdf "Physics guide"))

---

## 2. Types of radioactive decay

### Alpha decay

$$
{}^A_ZX \rightarrow {}^{A-4}_{Z-2}Y + {}^4_2\alpha
$$
Alpha particle = helium nucleus.

Effect:

$$
A \downarrow 4,\quad Z \downarrow 2
$$
---

### Beta-minus decay

$$
{}^A_ZX \rightarrow {}^A_{Z+1}Y + e^- + \bar{\nu}
$$
A neutron becomes a proton.

Effect:

$$
A \text{ unchanged},\quad Z \uparrow 1
$$
---

### Beta-plus decay

$$
{}^A_ZX \rightarrow {}^A_{Z-1}Y + e^+ + \nu
$$
A proton becomes a neutron.

Effect:

$$
A \text{ unchanged},\quad Z \downarrow 1
$$
---

### Gamma decay

$$
{}^A_ZX^* \rightarrow {}^A_ZX + \gamma
$$
The nucleus loses excess energy.

Effect:

$$
A \text{ unchanged},\quad Z \text{ unchanged}
$$
---

## 3. Conservation laws in nuclear equations

Always conserve:

$$
A,\quad Z,\quad \text{charge},\quad \text{energy},\quad \text{momentum}
$$
In IB homework, the fastest method is usually:

1. Balance $A$.

2. Balance $Z$.

3. Identify the missing particle.

---

## 4. Decay law

Radioactive decay is random for one nucleus, but predictable for a large sample.

$$
N=N_0e^{-\lambda t}
$$
Activity:

$$
A=\lambda N
$$
So:

$$
A=A_0e^{-\lambda t}
$$
Half-life:

$$
T_{1/2}=\frac{\ln 2}{\lambda}
$$
Alternative form:

$$
N=N_0\left(\frac12\right)^{t/T_{1/2}}
$$
Same for activity:

$$
A=A_0\left(\frac12\right)^{t/T_{1/2}}
$$
Use the half-life form when the time is a clean multiple of half-lives. Use the exponential form when it is not.

---

## 5. Radioactive dating

If you know the original amount and current amount:

$$
\frac{N}{N_0}=e^{-\lambda t}
$$
So:

$$
t=\frac{1}{\lambda}\ln\left(\frac{N_0}{N}\right)
$$
If using activity:

$$
t=\frac{1}{\lambda}\ln\left(\frac{A_0}{A}\right)
$$
---

## 6. Radiation penetration

|Radiation|Stopped by|Ionizing power|Penetration|
|---|---|---|---|
|Alpha|paper/skin|high|low|
|Beta|thin aluminium|medium|medium|
|Gamma|thick lead/concrete|low|high|

---

# E4 — Fission

Fission is splitting a heavy nucleus into smaller nuclei.

Example structure:

$$
{}^{235}_{92}\text{U}+{}^1_0n\rightarrow \text{fission fragments}+2\text{ or }3n+\text{energy}
$$
Energy comes from increased binding energy per nucleon of the products.

## 1. Chain reaction

One neutron causes fission. Fission releases more neutrons. Those neutrons cause more fissions.

For a sustained chain reaction, on average one neutron from each fission must cause another fission.

|Case|Meaning|
|---|---|
|subcritical|reaction dies out|
|critical|steady chain reaction|
|supercritical|reaction grows rapidly|

---

## 2. Nuclear reactor components

|Component|Purpose|
|---|---|
|Fuel|undergoes fission, e.g. uranium-235|
|Moderator|slows neutrons, e.g. water/graphite|
|Control rods|absorb neutrons, e.g. boron/cadmium|
|Coolant|transfers thermal energy|
|Shielding|absorbs radiation|
|Turbine/generator|converts thermal energy to electrical energy|

Moderator is important because slow neutrons are more likely to cause fission in U-235.

Control rods regulate the reaction by absorbing excess neutrons.

IB includes fission, chain reactions, and nuclear reactors in E4. ([focuseducational.com](https://www.focuseducational.com/ib-dp-physics-2025/ "IB DP Physics 2025"))

---

## 3. Fission energy calculations

Two common methods.

### Method 1: mass defect

$$
Q=\Delta mc^2
$$
where:

$$
\Delta m = m_{\text{initial}}-m_{\text{final}}
$$
If final mass is smaller, energy is released.

### Method 2: binding energy

$$
Q = E_{b,\text{products}} - E_{b,\text{reactants}}
$$
If products have greater total binding energy, energy is released.

---

## 4. Power from fission

If one fission releases energy $E$, and the reactor produces power $P$, then number of fissions per second is:

$$
\text{rate}=\frac{P}{E}
$$
Remember to convert MeV to joules:

$$
1\text{ eV}=1.60\times10^{-19}\text{ J}
$$
$$
1\text{ MeV}=1.60\times10^{-13}\text{ J}
$$
---

# E5 — Fusion and stars

E5 connects nuclear fusion to stellar physics.

## 1. Fusion

Fusion combines light nuclei into heavier nuclei.

Example:

$$
{}^2_1\text{H}+{}^3_1\text{H}\rightarrow{}^4_2\text{He}+{}^1_0n+\text{energy}
$$
Fusion releases energy because light nuclei combine into products with higher binding energy per nucleon.

---

## 2. Why fusion needs high temperature and density

Nuclei are positively charged, so they repel each other electrically.

To fuse, they need:

|Condition|Why|
|---|---|
|high temperature|high kinetic energy to overcome Coulomb repulsion|
|high density|frequent collisions|
|confinement/pressure|enough time for fusion to occur|

In stars, gravity provides confinement.

---

## 3. Stellar equilibrium

A stable star balances:

$$
\text{outward radiation pressure} = \text{inward gravitational force}
$$
Gravity tries to collapse the star. Fusion releases energy and produces pressure that pushes outward.

IB explicitly states that star stability depends on equilibrium between outward radiation pressure and inward gravitational forces. ([Peda.net](https://peda.net/kuopio/lukiot/lyseonlukio/ib/syllabukset/group-4-sciences/physics-2025.pdf%3Afile/download/c56a8c8592e847bbb555540b087b0990d1ade5b0/Physics%2C%202025.pdf "Physics guide"))

---

## 4. Stellar evolution

The most important variable is **mass**.

### Low/medium mass star

$$
\text{nebula} \rightarrow \text{protostar} \rightarrow \text{main sequence} \rightarrow \text{red giant} \rightarrow \text{planetary nebula} \rightarrow \text{white dwarf}
$$
### High mass star

$$
\text{nebula} \rightarrow \text{protostar} \rightarrow \text{main sequence} \rightarrow \text{red supergiant} \rightarrow \text{supernova} \rightarrow \text{neutron star or black hole}
$$
Massive stars evolve faster because they consume fuel much faster.

---

## 5. Hertzsprung–Russell diagram

The HR diagram plots:

$$
\text{luminosity vs surface temperature}
$$
Usually:

- luminosity increases upward

- temperature decreases to the right

Main regions:

|Region|Properties|
|---|---|
|Main sequence|stable hydrogen fusion|
|Red giants/supergiants|cool surface, very luminous, large radius|
|White dwarfs|hot surface, low luminosity, small radius|

Key relation:

$$
L = 4\pi R^2 \sigma T^4
$$
So if you know luminosity and temperature, you can find radius:

$$
R=\sqrt{\frac{L}{4\pi\sigma T^4}}
$$
Useful comparison form:

$$
\frac{L}{L_\odot}=\left$\frac{R}{R_\odot}\right$^2\left$\frac{T}{T_\odot}\right$^4
$$
This form is usually faster in IB problems.

---

## 6. Stellar parallax

Parallax formula:

$$
d$\text{pc}$=\frac{1}{p$\text{arcsec}$}
$$
where:

- $d$ is distance in parsecs

- $p$ is parallax angle in arcseconds

Examples:

$$
p=0.5'' \Rightarrow d=2\text{ pc}
$$
$$
p=0.01'' \Rightarrow d=100\text{ pc}
$$
IB explicitly includes stellar parallax and stellar radii in E5. ([Peda.net](https://peda.net/kuopio/lukiot/lyseonlukio/ib/syllabukset/group-4-sciences/physics-2025.pdf%3Afile/download/c56a8c8592e847bbb555540b087b0990d1ade5b0/Physics%2C%202025.pdf "Physics guide"))

---

# Problem-solving patterns

## Pattern 1: Photon transition

Given two energy levels, find wavelength.

Steps:

1. Find energy gap:

$$
\Delta E = |E_2-E_1|
$$
2. Convert eV to joules if needed.

3. Use:

$$
\lambda=\frac{hc}{\Delta E}
$$
---

## Pattern 2: Nuclear equation balancing

Example:

$$
{}^{238}_{92}\text{U}\rightarrow{}^{234}_{90}\text{Th}+?
$$
Mass number dropped by 4, proton number dropped by 2, so:

$$
?={}^4_2\alpha
$$
---

## Pattern 3: Half-life

Given initial activity $A_0$, final activity $A$, half-life $T$.

Use:

$$
A=A_0\left$\frac12\right$^{t/T}
$$
If solving for time:

$$
t=T\frac{\ln$A/A_0$}{\ln(1/2)}
$$
or:

$$
t=T\log_2\left$\frac{A_0}{A}\right$
$$
---

## Pattern 4: Binding energy

Given atomic/nuclear masses.

1. Find mass defect:

$$
\Delta m=m_{\text{separate nucleons}}-m_{\text{nucleus}}
$$
2. Convert mass to energy:

$$
E=\Delta mc^2
$$
or if mass is in atomic mass units:

$$
1u = 931.5\text{ MeV}/c^2
$$
so:

$$
E$\text{MeV}$=\Delta m$u$\times 931.5
$$
3. Binding energy per nucleon:

$$
\frac{E_b}{A}
$$
---

## Pattern 5: Photoelectric effect

Given frequency and work function:

$$
E_{k,\max}=hf-\Phi
$$
If stopping voltage is asked:

$$
V_s=\frac{E_{k,\max}}{e}
$$
If threshold wavelength is asked:

$$
f_0=\frac{\Phi}{h}
$$
$$
\lambda_0=\frac{c}{f_0}=\frac{hc}{\Phi}
$$
---

## Pattern 6: de Broglie wavelength

Given mass and speed:

$$
\lambda=\frac{h}{mv}
$$
Given electron accelerated through voltage $V$:

$$
\lambda=\frac{h}{\sqrt{2meV}}
$$
---

## Pattern 7: Star radius

Given luminosity and temperature:

$$
L=4\pi R^2\sigma T^4
$$
Rearrange:

$$
R=\sqrt{\frac{L}{4\pi\sigma T^4}}
$$
If comparing to the Sun:

$$
\frac{R}{R_\odot}=\sqrt{\frac{L/L_\odot}{$T/T_\odot$^4}}
$$
---

# The most important traps

1. **Photon energy must match exactly** for atomic transitions.

2. **Intensity does not increase photoelectron max kinetic energy**; frequency does.

3. **Half-life is exponential**, not linear.

4. **Activity is proportional to number of undecayed nuclei**:

$$
A=\lambda N
$$
5. **Mass defect uses initial minus final for reactions**, but separated nucleons minus nucleus for binding energy.

6. **Binding energy released means products are more tightly bound.**

7. **Gamma decay changes energy, not $A$ or $Z$.**

8. **Fusion and fission both release energy by moving toward higher binding energy per nucleon.**

9. **In HR diagrams, temperature usually decreases to the right.**

10. **Parsec formula only works if parallax is in arcseconds.**

---

# Minimal formula sheet

$$
E=hf=\frac{hc}{\lambda}
$$
$$
{}^A_ZX,\quad n=A-Z
$$
$$
R=R_0A^{1/3}
$$
$$
E_n=-\frac{13.6}{n^2}\text{ eV}
$$
$$
hf=\Phi+E_{k,\max}
$$
$$
E_{k,\max}=eV_s
$$
$$
\lambda=\frac{h}{p}
$$
$$
\Delta\lambda=\frac{h}{m_ec}$1-\cos\theta$
$$
$$
E_b=\Delta mc^2
$$
$$
N=N_0e^{-\lambda t}
$$
$$
A=\lambda N
$$
$$
T_{1/2}=\frac{\ln2}{\lambda}
$$
$$
N=N_0\left$\frac12\right$^{t/T_{1/2}}
$$
$$
Q=\Delta mc^2
$$
$$
L=4\pi R^2\sigma T^4
$$
$$
d$\text{pc}$=\frac{1}{p$\text{arcsec}$}
$$
---

# Fastest way to study this

Do it in this order:

1. **Memorize the formula sheet.**

2. Do 5 photon/spectrum questions.

3. Do 5 nuclear equation balancing questions.

4. Do 5 half-life/activity questions.

5. Do 5 binding-energy/mass-defect questions.

6. For HL: do 5 photoelectric + 3 de Broglie + 2 Compton questions.

7. Finish with HR diagram/parallax/radius questions.

For homework fluency, the highest-yield topics are **spectra, photoelectric effect, half-life, binding energy, fission/fusion energy, and HR diagram calculations**.
