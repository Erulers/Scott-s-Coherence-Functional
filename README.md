## License

This mathematical work is licensed under
Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0).

Original authorship must be credited when this work is referenced,
shared, adapted, or redistributed.

Adaptations must be distributed under the same license.

License: https://creativecommons.org/licenses/by-sa/4.0/

Formula; 

$$
\begin{aligned}
\mathcal{Q}(\mathbf{x},t)
={}&
\sum_{i,j,k=1}^{n}
\int_0^t
\frac{\partial^2\Phi_i}
{\partial x_j\partial x_k}
(\mathbf{x}(s),s)
\\
&\quad\cdot
\exp\left(
-\int_s^t
\frac{\omega_i(\mathbf{x}(\xi))}
{1+|\dot{x}_j(\xi)|}
\,d\xi
\right)
\\
&\quad\cdot
\sin\left(
\int_s^t
\Omega_{ijk}(\mathbf{x}(\eta))
\,d\eta
+\Theta_{ijk}(s,t)
\right)
\\
&\quad\cdot
\frac{\dot{x}_j(s)\dot{x}_k(s)}
{1+\displaystyle\sum_{m=1}^{n}
\chi_mx_m^2(s)}
\\
&\quad\cdot
\left(
1+
\frac{
\partial\Psi_i/\partial x_j
(\mathbf{x}(s),s)
}{
1+
\left|
\partial\Psi_k/\partial x_i
(\mathbf{x}(s),s)
\right|
}
\right)
\,ds
\\[8pt]
&+
\sum_{i=1}^{n}
\frac{\partial^3\Phi_i}
{\partial x_i^2\partial t}
(\mathbf{x}(t),t)
\prod_{j=1}^{n}
(1+\kappa_{ij}x_j^2(t))
\\[8pt]
&+
\sum_{i,j,k=1}^{n}
\Lambda_{ijk}
\frac{
\dot{x}_i(t)\dot{x}_j(t)\ddot{x}_k(t)
}{
1+
|\dot{x}_i(t)\dot{x}_j(t)|
+
|\ddot{x}_k(t)|
}.
\end{aligned}
\tag{2.1}
$$
