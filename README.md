This project uses the technology of jupyter notebooks and the power of math to obtain wavefunction equations and hydrogenic atoms plot

### by Randhal Ramirez (randhal45@gmail.com)

# Calculating the wavefunction of any hydrogenic atom:

## $-\frac{\hbar}{2 \mu} \nabla^2 \psi_{nlm} - \frac{Ze^2}{4\pi \epsilon_0 r} \psi_{nlm} = E_n \psi_{nlm}$

## Solving this Differential Equation:

## $\psi_{nlm}=c_1 \exp \left[ \sqrt{-\frac{\hbar}{2 \mu E_n}-\frac{Ze^2}{4 \pi \epsilon_0 r E_n}} \right]+c_2 \exp \left[ -\sqrt{-\frac{\hbar}{2 \mu E_n}-\frac{Ze^2}{4 \pi \epsilon_0 r E_n}} \right]$

# For especific n,l,m values this equation is often used:

### Where $\psi_{nlm}(\theta,\phi)$ is the whole wavefunction

## $\psi_{nlm}=R_{nl}(r) \times Y_m^l(\theta,\phi)$

### $R_ {nl}$: Is the radius contribution.

## $R_{nl}(r) = \left[ \frac{(n-l-1)!}{2n(n+l)!} \right]^\frac{1}{2} \left( \frac{2}{an} \right)^\frac{3}{2}x^l e^{-\frac{x}{2}} L_{n-l-1}^{2l+1}(x)$

## $Y_{lm}(\theta,\phi)=(-1)^m \left[ \frac{2l+1}{4 \pi} \frac{(l-m)!}{(l+m)!} \right]^\frac{1}{2} P_l^m(cos \theta) e^{im \phi}$

## $L_{n-l-1}^{2l+1}(x)= \displaystyle \sum_{k=0}^{n-l-1} \frac{ (l+n)! (-x)^k }{ (2l+1+k)! (n-l-1-k)! k!}$

## $P_l^{-m}(x)=(-1)^m\frac{(l-m)!}{(l+m)!} P_l^m(x)$

## $P_l^m(x)=(1-x^2)^\frac{m}{2} \frac{d^m}{dx^m} P_l(x)$ for $l \geq m \geq 0$

### $P_l(x)$: Is the Legendre Polynomial

## $P_l(x)=\frac{1}{2^l \cdot l!} \frac{d^l}{dx^l}(x^2-1)^l$

## $x=\frac{2r}{na}$

## $a=\frac{m_e}{\mu} \frac{a_0}{Z} \approx \frac{a_0}{Z}$

## $\mu=\frac{m_e m_Z}{m_e + m_Z}$
