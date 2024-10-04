# rheologyHacks


## Chapter 1: Making the most of oscillatory rheometry
* This chapter gives a condensed view of a pipeline that takes oscillatory rheometer data and turns into something useful to an engineer who is mostly concerned with steady-state behaviour.
* It must be said that this pipeline is only applicable to data in the regime of linear viscoelasticity (see Chapter 1.1.)

### 1.1. Linear viscoelasticity
* tba
* tba

### 1.2 Cox-Merz-Rule [1]
Using this rule, we can relate the elastic storage modulus $G'$ and the viscous loss  modulus   $G''$ to the steady-state shear rate at a certain shear rate (that is equal to the oscillatory frequency).

$\eta(\dot{\gamma}=\omega)=\frac{G''(\omega)}{\omega}\sqrt{1+\left ( \frac{G'(\omega)}{G''(\omega)} \right )^{2}}$

or formulated in terms of shear stress

$\tau_{12}(\dot{\gamma}=\omega)=G''(\omega)\left [1+\left (\frac{G'(\omega)}{G''(\omega)}  \right )^{2}\right ]^{0.5}$

### 1.3 Launs normal stress rule [2]
$N_{1}(\dot{\gamma}=\omega)=2G'(\omega)\left [1+\left (\frac{G'(\omega)}{G''(\omega)}  \right )^{2}\right ]^{\alpha} \approx \tau_{11}$

with $\alpha$ usually being 0.7

One can also relate the (shear-rate-dependant) first normal stress coefficient $\Psi_{1}$:

$\Psi_{1}\omega^{2}=N_{1}(\omega)=2G'(\omega)\left [1+\left (\frac{G'(\omega)}{G''(\omega)}  \right )^{2}\right ]^{\alpha}$ 

## Chapter 2: Analysis of transient behaviour using mirror rules

### 2.1: First mirror relation of Gleissle

### 2.2: Second mirror relation of Gleissle

## Chapter 3: From shear viscosity to the shear modulus and back

### 3.1: The interrelation of shear modulus, shear viscosity and relaxation time

### 3.2: just what on earth is steady-state-compliance?

## Chapter 4: A simple formula for shear-induced die-swell



### Literature


[1] Cox, W. P. ; Merz, E. H.: Correlation of dynamic and steady flow viscosities. Journal of Polymer Science 28 (1958) 118, p. 619–622 - DOI: 10.1002/pol.1958.1202811812

[2] Laun, H. M.: Prediction of Elastic Strains of Polymer Melts in Shear and Elongation. Journal of Rheology 30 (1986) 3, p. 459–501 - DOI: 10.1122/1.549855
