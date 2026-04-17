Faraday's key discovery: a constant magnetic field produces no current; a *changing* magnetic field (flux) induces an emf
- It is the relative motion between conductor and field that matters, not which one moves

Magnetic flux $\Phi$ through a loop of area $A$: $$\Phi = BA\cos\theta$$
- $\theta$ is the angle between $\vec{B}$ and the normal to the loop face
- When $B \perp$ loop face ($\theta = 0°$): $\Phi = BA$ (maximum)
- When $B \parallel$ loop face ($\theta = 90°$): $\Phi = 0$
- Unit: weber (Wb), where 1 Wb = 1 T m$^2$
- Magnetic flux density $B$ (T) ≡ magnetic field strength (Wb m$^{-2}$)

Flux linkage for a coil of $N$ turns: $N\Phi = NBA\cos\theta$

> [!MOST IMPORTANT LAW]
> **Faraday's law of electromagnetic induction**: the induced emf equals the negative rate of change of magnetic flux linkage: $$\varepsilon = -N\frac{\Delta\Phi}{\Delta t}$$
> - emf is not a force; it is the energy supplied per unit charge

Ways to change flux and induce an emf:
- Change $B$ (moving a magnet toward/away from a coil, or switching current on/off in a nearby circuit)
- Change $A$ (e.g. a conducting rod sliding along rails, changing the loop area)
- Change $\theta$ (rotating a coil in a magnetic field)

> [!QUOTE]
> "这个不变，这个不变，变那个" - Dr. Yao the Great, March 24, 2026

Application of the above: induced emf in **a straight conductor moving perpendicularly through uniform** $B$: $$\varepsilon = BvL$$
- $v$ is the speed of the conductor, $L$ is its length perpendicular to both $\vec{v}$ and $\vec{B}$
- Derived from $\varepsilon = -N\frac{\Delta\Phi}{\Delta t} = -\frac{B \cdot \Delta A}{\Delta t} = -\frac{B \cdot L \cdot \Delta x}{\Delta t} = BvL$ (for $N = 1$)

> [!Sidekick LAW]
> **Lenz's law**: the direction of the induced emf (and hence current) is such that it opposes the change in flux that caused it
> - The minus sign in Faraday's law represents Lenz's law
> - Consequence of **conservation of energy**: if the induced current aided the change, energy would be created from nothing

Applying Lenz's law (steps):
1. Identify direction of original magnetic flux
2. Determine whether flux is increasing or decreasing
3. Induced $B$ opposes the change: if flux increases, induced $B$ points opposite to original $B$; if flux decreases, induced $B$ points same direction as original $B$
4. Use right-hand rule on the induced $B$ to find current direction

Common Lenz's law scenarios:
- Magnet approaching coil: induced current creates a pole that repels the magnet
- Magnet receding from coil: induced current creates a pole that attracts the magnet
- Coil entering a field region: induced current opposes the increase in flux
- Rod sliding on rails in $B$: induced current direction opposes the area increase

Self-induction (qualitative only):
- A coil carrying a changing current produces a changing magnetic flux through itself
- This changing flux induces a back-emf in the coil that opposes the change in current
- Observed when switching circuits on/off: current doesn't change instantaneously
![[Screenshot 2026-03-25 at 14.06.38.png]]
Rotating coil in uniform $B$ — AC generator:
- Flux through coil: $\Phi = BA\cos\theta = BA\cos(\omega t)$
- By Faraday's law, the induced emf is: $$\varepsilon = -N\frac{d\Phi}{dt}= \omega NBA\sin(\omega t) = \varepsilon_0 \sin(\omega t)$$
- Peak emf: $\varepsilon_0 = \omega NBA$
- Sinusoidal output: this is alternating current (AC)

Effect of changing rotation frequency:
- Increasing $\omega$ increases both the frequency of oscillation and the peak emf $\varepsilon_0 = \omega NBA$
- The rate of change of flux increases because the coil rotates faster

AC generator components: armature (coil), permanent magnets, axle, slip rings, brushes
- Slip rings maintain continuous contact as the coil rotates, allowing AC output
- Contrast with DC motor which uses a split-ring commutator
