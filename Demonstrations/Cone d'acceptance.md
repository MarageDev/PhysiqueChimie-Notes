#Demonstration
$$\text{Conditions initiales }\;
\boxed{
\begin{cases}
    RT \;\text{ ssi }\; i_{1} &>\; \arcsin \frac{n_{2}}{n_{1}} \\
 n_{0}\sin (\theta_{0}) &=\; n_{1}\sin (\theta_{1}) \\
\theta_{1}&=\;\frac{\pi}{2}-i_{1}
\end{cases}}$$
$$\begin{align*} \\\\

\theta_{1} &< \frac{\pi}{2}-\arcsin \frac{n_{2}}{n_{1}}\\
\sin(\theta_{1}) &< \sin\left( \frac{\pi}{2} - \arcsin\left( \frac{n_{2}}{n_{1}} \right) \right) \tag*{* {(1) Formule : }$\sin\left( \frac{\pi}{2}-\alpha \right) = \cos(\alpha)$}\\\\

\sin(\theta_{1}) &< \cos\left( \arcsin\left( \frac{n_{2}}{n_{1}} \right) \right) &\tag*{{* (2) Parce que : }$\sin(\theta_{1}) = \frac{n_{0}}{n_{1}}\sin(\theta_{0})$}\\\\

\sin(\theta_{0}) &< \frac{n_{1}}{n_{0}} \underbrace{ \cos\left( \arcsin\left( \frac{n_{2}}{n_{1}} \right) \right) }_{ > \; 0 } &\tag*{{* (3) }$\cos(x) = \sqrt{ 1-\sin{^2}(x) }$} \\\\

\sin(\theta_{0}) &< \frac{n_{1}}{n_{0}} \cdot \sqrt{ 1-\sin^{2}\left( \arcsin\left( \frac{n_{2}}{n_{1}} \right) \right) }\\\\

\sin(\theta_{0}) &< \frac{n_{1}}{n_{0}} \cdot \sqrt{ 1-\left( \frac{n_{2}}{n_{1}} \right)^2 }\\\\

\sin(\theta_{0}) & < \underbrace{ \frac{1}{n_{0}} \cdot \sqrt{ n_{1}{^2}-n_{2}{^2} }_{=\frac{1}{n_{0}}\cdot \sqrt{ n_{1}^{^2}-\frac{\cancel{ n_{1}^{^2} }\cdot n_{2}^{^2}}{\cancel{ n_{1}^{^2} }} } } }\\\\

\theta_{0} & < \arcsin\left( \frac{\sqrt{ n_{1}{^2}-n_{2}{^2} }}{n_{0}} \right)\\\\

&= \theta_{0,lim}
\end{align*}$$
$$\boxed{\theta_{0,lim} = \arcsin\left( \frac{\sqrt{ n_{1}{^2}-n_{2}{^2} }}{n_{0}} \right)}$$

Si $\theta_{0} < \theta_{0,lim}$ RT en I, rayon guidé
Si $\theta_{0} > \theta_{0,lim}$ RT transmis dans le milieu
___
$(2) :$
$$\begin{align}
\sin(\theta_{1}) & = \frac{n_{0}}{n_{1}}\sin(\theta_{0})  \\
\sin(\theta_{0}) &= \frac{n_{0}}{n_{1}} \;\sin(\theta_{1})
\end{align}
\;\;\;\;
\text{avec } \sin(\theta_{1}) = \cos\left( \arcsin\left( \frac{n_{2}}{n_{1}} \right) \right)$$
___
$(3) :$
$$\begin{align}
\sin^{2}(x)+\cos^{2}(x) & = 1 \\
\cos^{2}(x) &= 1-\sin^{2}(x) \\
\cos(x) & = \sqrt{ 1-\sin^{2}(x) }

\end{align}$$
___
#Chap1_Optique 