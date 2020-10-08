# ソリトン

@tkoyama010

---
## KdV方程式

非線形浅水長波の波形の第1近似 $\eta^{\left(1\right)}$に対する方程式

`\[
\dfrac{\partial\eta^{\left(1\right)}}{\partial\tau}+\dfrac{3c_{0}}{2h}\eta^{\left(1\right)}\dfrac{\partial\eta^{\left(1\right)}}{\partial\xi}=-\dfrac{c_{0}h^{2}}{6}\dfrac{\partial^{3}\eta^{\left(1\right)}}{\partial\xi^{3}}
\]`

ただし、$\tau=\varepsilon^{3/2}t$ 、 $c_{0}=\sqrt{gh}$ 、 $g$ は重力加速度、 $h$ は水深、$\xi=\varepsilon^{1/2}\left(x-c0t\right)$ 。

---
## KdV方程式の解

- クノイド波
- 孤立波

---
## KdV方程式の解

初期条件が
`\[
u\left(x,0\right)=\cos\left(\pi x\right)
\]`
のとき、
`\[
\left.\dfrac{\partial u}{\partial t}+u\dfrac{\partial u}{\partial x}+\mu\dfrac{\partial^{3}u}{\partial x^{3}}\right|_{\mu=0}=\dfrac{\partial u}{\partial t}+u\dfrac{\partial u}{\partial x}=0
\]`
の解は
`\[
u=\cos\left[\pi\left(x-ut\right)\right]
\]`

---
## KdV方程式

カタストロフ(catastrophe)

---
## KdV方程式

`\[
u\left(x,0\right)=U\mathrm{sech}^{2}\left(\dfrac{x}{D}\right),D=\sqrt{\dfrac{12\mu}{U}}
\]`

---
## ソリトン

---
# 音波

@tkoyama010

---
## 音波

- 内部波
- 音波

`\[
\dfrac{\partial\rho}{\partial t}+\mathrm{div}\left(\rho\boldsymbol{u}\right)=0
\]`
`\[
\dfrac{D\boldsymbol{u}}{Dt}=-\dfrac{1}{\rho}\mathrm{grad}p
\]`

---
## 音波

`\[
\rho=f\left(p\right)
\]`
`\[
\dfrac{\partial\rho}{\partial t}+\rho_{0}\mathrm{div}\boldsymbol{u}=0
\]`

両辺から速度$\boldsymbol{u}$を消去すれば、密度$\rho$に対する方程式が得られる。
`\[
\dfrac{\partial^{2}\rho}{\partial t^{2}}-a_{0}^{2}\Delta\rho=0
\]`
ただし、
`\[
a_{0}=\sqrt{\left(\dfrac{dp}{d\rho}\right)_{0}}
\]`

---
## 音波

圧縮率
`\[
\dfrac{1}{\rho}\dfrac{d\rho}{dp}
\]`
流体が理想気体である場合の状態方程式は
`\[
p=\rho^{T}\exp\left[\dfrac{S-S_{0}}{c_{V}}\right]
\]`
ただし、
- $S0$は静止状態におけるエントロピー$S$の値
- $\gamma=cp/cV$は比熱の比
- $c_{P}$は定圧比熱
- $c_{V}$は定積比熱

---
## 音波

断熱法則
`\[
p=C\rho^{\gamma}\left(C:\mathrm{const}\right)
\]`
が成り立つとき音速は
`\[
a_{0}=\sqrt{\dfrac{\gamma p_{0}}{\rho_{0}}}=\sqrt{\gamma RT_{0}}
\]`

---
## 音波

波が空間的に1方向に変化する平面波
`\[
\dfrac{\partial\rho}{\partial t}+\rho_{0}\dfrac{\partial u}{\partial x}=0
\]`
`\[
\dfrac{\partial u}{\partial t}+\dfrac{a_{0}^{2}}{\rho_{0}}\dfrac{\partial\rho}{\partial x}=0
\]`
両辺から$u$または$p$を消去すると。
`\[
\left(\dfrac{\partial^{2}}{\partial t^{2}}-a_{0}^{2}\dfrac{\partial^{2}}{\partial x^{2}}\right)\begin{pmatrix}\rho\\u\end{pmatrix}=0
\]`

---
## 音波

一般解は
`\[
\begin{pmatrix}\rho\\u\end{pmatrix}\begin{pmatrix}x, & t\end{pmatrix}=f\left(x-a_{0}t\right)+g\left(x+a_{0}t\right)
\]`
ただし、$f$、$g$は任意関数。

---
# 有限振幅波

@tkoyama010

---
# 有限振幅波

変動が微小ではなく有限の場合を考える。
`\[
\dfrac{\partial\rho}{\partial t}+u\dfrac{\partial\rho}{\partial x}+\rho\dfrac{\partial u}{\partial x}=0
\]`
`\[
\dfrac{\partial u}{\partial t}+u\dfrac{\partial\rho}{\partial x}+\rho\dfrac{\partial u}{\partial x}=0
\]`
ただし、
`\[
a=\sqrt{\left(\dfrac{dp}{d\rho}\right)_{s}}
\]`
