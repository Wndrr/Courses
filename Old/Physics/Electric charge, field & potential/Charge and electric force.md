# Triboelectric effect and charge

Rubbing a plastic balloon on your head, making your hair go up, and lightning are demonstrations of the triboelectric effect. 

This effect is due to charge. Some things have a negative charge and some have a positive charge. "Things" of opposite charge attract each other. "Things" with identical charges will repel each other. 

Charge, positive and negative are just words, models, to describe the comportment of the universe. A convention used for communication

The nuclei of atoms are composed of protons and neutrons. Based on this framework:

- protons ($p^+$) have a positive charge ($+1$)
- neutron ($n^0$) have a neutral charge ($0$) 
- electrons ($e^-$) have a negative charge ($-1$) 

In the baloon/hair example, what happens is that due to the materials the balloon and hair are made off, when they are rubbed together the balloon will "grab" electrons from the hair making it more negatively charged, because it now has more electrons and the hair becomes positively charged because it lost electrons.



## Elementary unit of charge

Electrons, despite having a mass far lower than that of protons and neutrons, has the same charge, only "opposite" that of protons.

Thus, the charge of protons is often denoted as $e$ and that of electrons as $-e$. 

## Unit "coulombs"

The unit of charge is the coulom ($C$), with a lowercase "c". Coulomb written with a capital "C" is used to refer to the person it is named after, Charles-Augustin de Coulomb" when he published in 1785 a paper describing what is now known as "Coulomb's law"

### Definition

The coulomb is approximately equal to $1C \approx 6.24*10^{18}e$ where $e$ is the charge of single particle (proton/electron). Thus the charge of $e$ of a single of these particles is $e \approx 1.60*10^{-19}C$ 

## Coulomb's Law

The purpose of Coulomb's law is the predict the magnitude of the electrostatic force between two charges will be. The magnitude of the electrostatic force $F_e$ is proportional to the product of the magnitude of the charges inversely proportional to the square of the distance.
$$
F_e = K\frac{q_1 \times q_2}{r^2}
$$
 Where 

- $K_e$ is the magnitude of the force, in newtons
- $K$ is Coulomb's; constant a constant $\approx 9\times10^9 \frac{Nm^2}{C^2}$ 
- $q_1$ and $q_2$ are the charges of the particles
- $r$ is the distance between the particles

For two particles with charges $q_1 = +5\times10^{-3}C$ and $q_2=-1\times10^{-1}C$ separated by a distance $r$ of $0.5$ meters, the electrostatic force between these two will be an attractive force of magnitude
$$
\begin{align*}
F_e &= K\frac{q_1 \times q_2}{r^2} \\
&= 9\times10^9\frac{5\times10^{-3} \times -1\times10^{-1}}{.5^2} \\
&= -1.8\times10^7
\end{align*}
$$

# Conservation of charge

The law of conservation of (electric) charge states that the sum of the charges in a closed system is constant no matter what transformation the particles go through.
$$
\sum q = constant
$$
An uncharged particle can turn into charged particles but the sum of the resulting particles has to be null as well.

# Electric field

## Definition

Michael Farady, in the 19th century, found an explanation for the ability of particles to apply a force on each other across empty space.

An electric field $\overrightarrow{E}$ is defined to be the amount of electric force per charge exerted at a point in space. That is, the electric force a particle will "feel" is the product of the strength of the electric field it is in and of its own charge.
$$
\overrightarrow{E}=\frac{\overrightarrow{F_e}}{Q}
$$
Where

- $\overrightarrow{E}$ strength of the electric field in Newtons per coulomb $\frac{N}{C}$
- $\overrightarrow{F_e}$ if the electric force induced by the electric field in Newtons $N$
- $Q$ is the charge of the particle that receives the electric force in coulombs $C$

A positive charge creates an electric field ($\overrightarrow{E}$) everywhere around it. To be noted, $\overrightarrow{E}$ is a field, is different from electric force $\overrightarrow{F_e}$ despite being denoted using a vector. $\overrightarrow{E}$ is in fact not a force. They are related because the electric field can cause an electric force to be applied on other particles.

We can get the electric force that a charged particle will "feel" using
$$
\overrightarrow{F_e}=Q\times\overrightarrow{E}
$$

## Direction

If the charge $Q$ of a particle is positive, the direction of the electric force's $\overrightarrow{F}$ vector would be the same as the direction of the electric field $\overrightarrow{E}$ it is subjected to at that point in space.

If the charge $Q$ of a particle is negative, the direction of the electric force's vector would be opposite that of the field it is in.

In sum, if a negatively charged particle is place inside an electric field, it will be subjected to a force pointed opposite to that field, no matter if the field is created by a positive or negative particle.

The electric field from a positive particle is always oriented radially away from the source particle.

The electric field from a negative particle is pointed radially inwards, toward the source particle.

## Magnitude of electric field

The formula used to determine the magnitude of an electric field $E$ created by a symmetric charge in a point system is
$$
\begin{align*}
E &= \frac{F_e}{Q_2} &&= k\frac{\frac{Q_2\times Q_2}{r^2}}{Q_1} \\
&&&= k\frac{\frac{Q_1\times \cancel{Q_2}}{r^2}}{\cancel{Q_2}} \\
E &= &&= k\frac{Q_1}{r^2}
\end{align*}
$$
where $k$ is defined as 
$$
k = 9\times10^9\frac{Nm^2}{c^2}
$$
and $r$ is the distance from the centre of the charge creating the field to the point where the measure is taking place, in meters.

*note: this formula only gives the magnitude, NOT the orientation. A negative sign in the output tell you if the field points inward or outwards **RADIALLY**. 

## Proof: Field from infinite plate

With an infinite charged plate with a charge density of $\sigma$ in "coulomb per area":
$$
\sigma = \frac{Q}{Area}
$$
 and two charged particles, one on the plate noted $Q_1$ and one above the plate noted $Q_2$ where $Q1$ is at a distance $r$ on the $x$ axis from the origin while $Q_2$ is a distance $h$ from the origin on the $y$ axis.

![InfinitePlate](C:\Repositories\Courses\Physics\Electric charge, field & potential\Img\InfinitePlate.PNG)

Because the plate is infinite, the $Q_2$ will always have an other point that is symmetrically opposite around $Q_1$, which means the $x$ component of their respective field's vectors will cancel out, leaving only the $y$ component. 

![InfinitePlate2](C:\Repositories\Courses\Physics\Electric charge, field & potential\Img\InfinitePlate2.PNG)

The $y$ component of the $E_2$ field is $=E_2\cos\theta$ 