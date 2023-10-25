#Oscillateur_Harmonique
# Equation différentielle

> On reconnait l'équation d'un oscillateur harmonique quand c'est une équation de ce type : $\boxed{f'' + \omega_{0}^{2}\cdot f= 0}$

## $$\boxed{U_{C}+L \cdot C \cdot \frac{d{^2}U_{C}}{dt{^2}} = 0 } $$
Forme canonique de l'équation différentielle :
## $$\boxed{\frac{d^{2}U_{C}}{dt^{2} + \omega_{0}{^{2}}\cdot}U_{C}= 0 }$$
avec 
### $$\omega_{0} = \frac{1}{\sqrt{ L\cdot C }}$$
$\omega_{0}{^{2}} = \text{Pulsation propre de l'OH en } s^{-1} \text{ ou } rad\cdot s^{-1}$ #Pulsation_Propre 


# Résolution de l'équation différentielle
Il y a 3 types de solutions
### $$\boxed{\begin{cases}U_{C}(t) = A\cdot \cos(\omega_{0}(t)+\varphi_{c}) \\U_{C}(t) = A\cdot \sin(\omega_{0}(t)+\varphi_{s}) \\U_{C}(t) = A_{1}\cdot \sin(\omega_{0}(t))+A_{2}\cdot \cos(\omega_{0}(t))\end{cases}}$$
$A = \text{L'amplitude du signal } \omega_{0}$
$\varphi_{s} / \varphi_{c} = \text{Le déphasage à l'origine, ou la phase}$

![[Pasted image 20231025234252.png]]
>Remarque : $A \in \mathbb{R}\;$ et $\; \varphi_{c} \in [\;0;2\pi\;[\;$ et $\; \varphi_{s} = \varphi_{c}-\frac{\pi}{2}$

>Remarque : $A^{2} = A_{1}{^2}+A_{2}{^2}$

Par périodicité du cosinus, on a $U_{C}(t + T) = U_{C}(t)$ avec $t$ le temps qui sécoule et $T$ la période.
On a donc $$\omega_{0}(T) = 2k\;\pi \;\text{ avec }\; k \in \mathbb{Z}$$
donc si on choisit $k=1$ : $$\boxed{T=\frac{2\pi}{\omega_{0}}} \implies \boxed{f = \frac{\omega_{0}}{2\pi}}$$

# Conditions initiales

- $U_{C}(0^{-}) = U_{0}\;$ or $U_{C}$ est continu donc $\;U_{C}(0^{+}) = U_{0}$
- $t<0$, l'interrupteur est ouvert donc $i(0^{-})=0$ et à cause de la bobine $i(0^{+})=0$

On cherche ($A, \varphi_{c} )$

#### A $t=0$ :
