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

- 圧縮性流体である気体に存在する内部波
- 連続方程式
`\[
\dfrac{\partial\rho}{\partial t}+\mathrm{div}\left(\rho\boldsymbol{u}\right)=0
\]`
- 運動方程式
`\[
\dfrac{D\boldsymbol{u}}{Dt}=-\dfrac{1}{\rho}\mathrm{grad}p
\]`
- 順圧関係式
`\[
\rho=f\left(p\right)
\]`

---
## 音波

- 一様な静止状態の場合
`\[
\rho=\rho0=\mathrm{const}, p=p0=\mathrm{const}, \boldsymbol{u}=0
\]`
- 微小量$\rho-\rho0$、$p-p0$および$\boldsymbol{u}$について2次の項を無視した方程式に従う。
`\[
\dfrac{\partial\rho}{\partial t}+\rho_{0}\mathrm{div}\boldsymbol{u}=0
\]`
`\[
\dfrac{\partial\boldsymbol{u}}{\partial t}=-\dfrac{1}{\rho_{0}}\left(\dfrac{dp}{d\rho}\right)_{0}\mathrm{grad}\rho
\]`

---
## 音波

- 両辺から速度$\boldsymbol{u}$を消去すれば、密度$\rho$に対する方程式が得られる。ただし、$a0=\sqrt{\left(dp/d\rho\right)0}$
`\[
\dfrac{\partial^{2}\rho}{\partial t^{2}}-a_{0}^{2}\Delta\rho=0
\]`
- この密度の波を**音波**といい、伝搬速度$a_{0}$を **音速** という。
- 音波は縦波である。

---
## 音波

- 圧縮率
`\[
\dfrac{1}{\rho}\dfrac{d\rho}{dp}
\]`
- 流体が理想気体である場合の状態方程式は
`\[
p=\rho^{T}\exp\left[\dfrac{S-S_{0}}{c_{V}}\right]
\]`
- ただし、
  - $S0$は静止状態におけるエントロピー$S$の値
  - $\gamma=cp/cV$は比熱の比
  - $c_{P}$は定圧比熱、$c_{V}$は定積比熱

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

- 変動が微小ではなく有限の場合
`\[
\dfrac{\partial\rho}{\partial t}+u\dfrac{\partial\rho}{\partial x}+\rho\dfrac{\partial u}{\partial x}=0
\]`
`\[
\dfrac{\partial u}{\partial t}+u\dfrac{\partial u}{\partial x}+\dfrac{a^{2}}{\rho}\dfrac{\partial\rho}{\partial x}=0
\]`
- ただし、$a=\sqrt{\left(dp/d\rho\right)s}$ は局所的な圧力$p$と密度$\rho$に対する音速を表しており、理想気体に対しては、$a=\sqrt{\left(\gamma p\right)/\rho}=\sqrt{\gamma RT}$

---
# 有限振幅波

- 変動が微小ではなく有限の場合
`\[
\dfrac{\partial\rho}{\partial t}+u\dfrac{\partial\rho}{\partial x}+\rho\dfrac{\partial u}{\partial x}=0
\]`
`\[
\dfrac{\partial u}{\partial t}+u\dfrac{\partial u}{\partial x}+\dfrac{a^{2}}{\rho}\dfrac{\partial\rho}{\partial x}=0
\]`
- 音波の場合の演算子$\partial/\partial t$が、$\partial/\partial t+u\partial/\partial x$で置き換えられている。

---
# 有限振幅波

## 物理的矛盾
- 音波の場合の演算子$\partial/\partial t$が、$\partial/\partial t+u\partial/\partial x$で置き換えられている。
- 音波の場合の正負の要素波の位相速度$\pm a_{0}$が、有限振幅波では$u\pm a$となることを示唆している。

---
# 有限振幅波

## 物理的矛盾
- 例えば正の要素波では、各部分の進行速度$u+a$は$u$の大きいところでは大きく、小さいところでは小さくなる。
- すなわち、ある時刻において負勾配の部分が無限大になってしまう。これは粘性と熱伝導性を無視したためである。

---
# 有限振幅波

## 例題7-2

`\[
\dfrac{\partial u}{\partial x}+\dfrac{\partial w}{\partial z}=0
\]`
`\[
\dfrac{\partial\eta}{\partial t}+u\dfrac{\partial\eta}{\partial x}+w\dfrac{\partial\eta}{\partial z}=0
\]`
`\[
\dfrac{\partial\Phi}{\partial t}+\dfrac{1}{2}\left(u^{2}+w^{2}\right)=-q\eta
\]`
第1式と第2式を組み合わせると。
`\[
\dfrac{\partial\eta}{\partial t}+\dfrac{\partial\left(\eta u\right)}{\partial x}+\dfrac{\partial\left(\eta w\right)}{\partial z}=0
\]`
となり、また、第3式を$x$および$z$について微分し、渦なしの条件、
`\[
\left(\mathrm{rot}\boldsymbol{u}\right)_{y}=\dfrac{\partial u}{\partial z}-\dfrac{\partial w}{\partial x}=0
\]`
を考慮すると、
`\[
\dfrac{\partial u}{\partial t}+u\dfrac{\partial u}{\partial x}+w\dfrac{\partial u}{\partial z}=-g\dfrac{\partial\eta}{\partial x}
\]`
`\[
\dfrac{\partial w}{\partial t}+u\dfrac{\partial w}{\partial x}+w\dfrac{\partial w}{\partial x}=-\dfrac{1}{\rho}\dfrac{\partial p}{\partial z}
\]`
一方、気体の有限振幅波に対する方程式は2次元形では、
`\[
\dfrac{\partial\rho}{\partial t}+\dfrac{\partial\left(\rho u\right)}{\partial u}+\dfrac{\partial\left(\rho w\right)}{\partial z}=0
\]`
`\[
\dfrac{\partial u}{\partial t}+u\dfrac{\partial u}{\partial x}+w\dfrac{\partial u}{\partial z}=-\dfrac{1}{\rho}\dfrac{\partial p}{\partial x}
\]`  
`\[
\dfrac{\partial w}{\partial t}+u\dfrac{\partial w}{\partial x}+w\dfrac{\partial w}{\partial z}=-\dfrac{1}{\rho}\dfrac{\partial p}{\partial z}
\]`  
$\gamma = 2$の断熱法則
`\[
p\wasypropto\rho^{2}
\]` 
- 跳ね水
- 衝撃波
- 浅底水槽の原理
