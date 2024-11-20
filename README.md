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
* First you need to know what start-up of shear looks like: The lower the non-zero shear we choose as target, the longer it takes to reach it. 
* Now we ask ourselves: What is the longest possible time needed to reach the steady-state viscosity? And what are the intermediate values like?
* To answer that question, we transform the time t (i.e. how many seconds have passed since start-up) into a shear rate gamma_dot = 1/t.
* Looking at the steady-state shear viscosity curve for that gamma_dot, we can determine the steady-state shear viscosity. This steady-state shear viscosity is also transient viscosity during start-up.
* From this we can conclude that [TBA]
* Do note that this rule is best applicable to an infinitesimally low target shear rate.
* What are outcomes for time shorter/longer than the characteristic relaxation time?

### 2.2: Second mirror relation of Gleissle

## Chapter 3: From shear viscosity to the shear modulus and back

### 3.1: The interrelation of shear modulus, shear viscosity and relaxation time

### 3.2: just what on earth is steady-state-compliance?

## Chapter 4: A simple formula for shear-induced die-swell

* We assume a fluid being sheared in the plane defined by the '1' and '2' axes, of which the '1' axis is the flow direction/direction of the moving plate.
* This shear flow stores energy in the melt, the elastic recovery of which then causes the extrudate to swell.
* The first normal stress difference $N_{1}$ is defined as:

$N_{1} = \tau_{11}-\tau_{22}$


* Mendelson et al. [3] posit that (Eq.18):

$N_{1} = \tau_{11}-\tau_{22} =\frac{2}{3}\tau_{12} \sqrt{B^4-\frac{1}{B^{2}}}$

* In most cases $\tau_{22}$ is small and can be neglected.
* For die swell factors B larger than 1.5 we can also neglect the contribution of $`\frac{1}{B^{2}}`$.
* Thus, we can conclude that the die swell factor B is given by:

$B = \sqrt{\frac{3}{2}\frac{\tau_{11}}{\tau_{12}}}$

* Obviously, this simplistic model make some major assumptions:
  * Whatever energy might have been imparted through elongational flow occuring at the entry into the capillary has relaxed/dissipated. Note that this does not assume dissipation of energy imparted through shear!
  * The capillary and the extrudate are cylindrical.
  * The extrudate can swell until all energy has been converted.
    
* The model is hence best applicable to cases in which:
  * Residence time in the capillary is long relative to the relaxation time (e.g. a L/D ratio of 30 or higher)
  * The capillary is cylindrical, swell is evaluated at the point of maximum strand diameter.
  * The extrudate is not cooled (which would cause energy to be 'frozen in' as internal stresses) / the extrudate has been stress-relieved and expanded to final shape through tempering (e.g. in a bath of silicone oil).
    


### Literature


[1] Cox, W. P. ; Merz, E. H.: Correlation of dynamic and steady flow viscosities. Journal of Polymer Science 28 (1958) 118, p. 619–622 - DOI: 10.1002/pol.1958.1202811812

[2] Laun, H. M.: Prediction of Elastic Strains of Polymer Melts in Shear and Elongation. Journal of Rheology 30 (1986) 3, p. 459–501 - DOI: 10.1122/1.549855

[3]  Mendelson, R. A. ; Finger, F. L. ; Bagley, E. B.: Die swell and recoverable shear strain in polyethylene extrusion.  Journal of Polymer Science Part C: Polymer Symposia 35 (1971) 1, p. 177–188 - DOI: 10.1002/polc.5070350114
