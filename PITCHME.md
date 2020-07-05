# 弦の波と振動

@tkoyama010

---
## 定義

一定の断面形をもつ柱状の弾性体で

### 棒 

太さがその中を伝わる弾性波の波長に比べ極めて小さいもの

### 糸

棒の中で曲げ剛性率が無視できるほど小さいもの

### 弦 

糸が一定の張力のもとで直線状となったもの

---
## 弦の方程式

`\[
F_{x}\left(x\right) = -T
\]`

`\[
F_{x}\left(x+\delta x\right) = -T
\]`

---
## 弦の方程式

`\[
\dfrac{\partial^2 h}{\partial t^2} = c^2 \dfrac{\partial^2 h}{\partial x^2}
\]`

`\[
c = \sqrt{\dfrac{T}{\rho S}}
\]`

---
## 弦の波

`\[
h\left(x, t\right) = f\left(x-ct\right) + g\left(x+ct\right)
\]`
`\[
h\left(x, t\right) = A \exp\left[ik\left(x-ct\right)\right] + B \exp\left[ik\left(x+ct\right)\right]
\]`

---
## 弦の正弦振動

`\[
h \left(0, t \right) = 0
\]`

`\[
h \left(L, t \right) = 0
\]`

`\[
h = a \sin\left(k_{n} x\right) \cos\left(k_{n} ct\right)
\]`

---
## 弦の任意波形の振動

`\[
a_n = \dfrac{2}{L} \int^L_0 f\left(x\right) \sin\left(k_{n} x\right)dx
\]`

`\[
h = \sum^\infty_{n=0} b_n \sin\left(k_n\right)\sin\left(k_nct\right)
\]`

---
# 棒の波と振動

@tkoyama010

---
## 棒の伸縮波

`\[
P_{11} = YE_{11} = Y\dfrac{\partial \gamma_1}{\partial x_1}
\]`
`\[
\dfrac{\partial^2 u}{\partial t^2} = c_{l\left( rod \right)}^2 \dfrac{\partial u}{\partial x^2}
\]`
`\[
c_{l\left( rod \right)} = \sqrt{\dfrac{Y}{\rho}} = \sqrt{\dfrac{\mu\left(3\lambda+2\mu\right)}{\left(\lambda+\mu\right)\rho}}
\]`

---
## 棒の伸縮振動

`\[
u\left(0, t\right) = u\left(L, t\right) = 0
\]`

`\[
u = a \sin \left(k_n x\right) \cos \left(k_n c_{l\left(rod\right)} t\right)
\]`

---
## 棒の曲げ変形波
`\[
y = h\left(x, t\right)
\]`
`\[
h = \left[A \cos\left(k x\right) + B \sin\left(k x\right) + C \cosh\left(k x\right) + D \sinh\left(k x\right)\right]\cos\left(\omega t\right)
\]`

---
## 棒の曲げ振動

### 一端が固定支持され他端が自由である

`\[
h\left(0\right) = \left[\dfrac{dh}{dx}\right]_{x=0} = 0
\]`

`\[
\left[\dfrac{d^2h}{dx^2}\right]_{x=0}=0
\]`

`\[
\left[\dfrac{d^3h}{dx^3}\right]_{x=L}=0
\]`

`\[
h = \left(A\left(\cos\left(kx\right)-\cosh\left(kx\right)\right)+B\left(\sin\left(kx\right)-\sinh\left(kx\right)\right)\right)\cos\left(\omega t\right)
\]`

`\[
\cos\left(kL\right)\cosh\left(kL\right)=-1
\]`

### 波数と振動数の固有値

### 最小固有値

`\[
k_{\min} = k_1 = \dfrac{1.88}{L}
\]`

`\[
\omega_{\min} = bk_{\min}^2 = \dfrac{3.52}{L^2}\sqrt{\dfrac{B}{\rho S}}
\]`

`\[
h = A\left(\left[\cos\left(k_nL\right) + \cosh\left(k_nL\right)\right]\left[\cos\left(k_nx\right)-\cosh\left(k_nx\right)\right]+\left[\sin\left(k_nL\right)-\sinh\left(k_nL-\sinh\left(k_nL\right)\right)\right]\left[\sin\left(k_nx\right)-\sinh\left(k_nx\right)\right]\right)\cos\left(
\omega_nt\right)
\]`

---
## 棒の曲げ振動

### 両端が固定されている

`\[
h\left(0\right) = \left[\dfrac{dh}{dx}\right]_{x=0} = 0
\]`

`\[
h\left(L\right) = \left[\dfrac{dh}{dx}\right]_{x=L} = 0
\]`

### 波数と振動数の固有値

### 最小固有値

`\[
k_{\min} = k_1 = \dfrac{4.73}{L}
\]`

`\[
\omega_{\min} = bk_{\min}^2 = \dfrac{22.4}{L^2}\sqrt{\dfrac{B}{\rho S}}
\]`

`\[
h = A\left(\left[\sin\left(k_n L\right)-\sinh\left(k_n L\right)\right]\left[\cos\left(k_n x\right)-\cosh\left(k_n x\right)\right]-\left[\cos\left(k_n L\right)-\cosh\left(k_n L\right)\left(\sin\left(k_n x\right)-\sinh\left(k_n x\right)\right)\right]\right)
\]`

---
## 棒の曲げ振動(例題4-2)

`\[
u = a\sin\left(kx\right)
\]`

### 一端が固定支持され他端が自由である

`\[
\dfrac{\partial u}{\partial x} = 0
\]`

`\[
k = k_n = \dfrac{\left(2n+1\right)\pi}{L}
\]`

### 棒の伸縮振動の固有振動数

`\[
\omega = \omega_n = k_n c_{l\left(rod\right)} = \dfrac{\left(2n+1\right)\pi}{2L}\sqrt{\dfrac{Y}{\rho}}
\]`

---
## 棒の曲げ振動(例題4-3)

### 両端が単純支持

### 波数と振動数の固有値

### 最小固有値

---
## 演習問題

---
