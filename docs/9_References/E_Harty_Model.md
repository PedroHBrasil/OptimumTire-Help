---
Title: Harty Model
summary: This section details the Harty Model.
authors:
    - Pedro Brasil   
date: 2019/9/10
---

<script>
MathJax = {
  tex: {
    inlineMath: [['$', '$'], ['\\(', '\\)']]
  }
};
</script>

<script id="MathJax-script" async
  src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-chtml.js">
</script>

# Harty Model

The Harty tire model aims to provide a compromise between the complex Pacejka models and the limited Fiala model. Features of the Harty model include the ability to model camber thrust and the load dependency of cornering stiffness.

The model does not include the calculation of the overturning moment. The model also treats driving and braking forces as symmetric. Note the Harty model is only compatible with the SAE coordinate systems due to the method used to model the camber thrust. The model may still be graphed in other coordinate systems after fitting. For more information on the Harty model see "Intermediate tyre model for vehicle handling simulation" by M V Blundell and D Harty.

## Longitudinal Model

$$D= D_{x}+(|F_{z}|-R_{L})\frac{dD}{dF_{z}}$$

$$if( S < S_{c}) \rightarrow F_{x} = (1-e^{(-A_{x}|S/S_{c}|)})\mu DF_{z} sign(1,\alpha)$$

$$ if( S > S_{c}) \rightarrow F_{x} = (1-e^{-A_{x}})\mu DF_{z} sign(1,\alpha)$$

## Lateral Model

$$ B= B_{y}+(|F_{z}|-R_{L})\frac{dB}{dF_{z}} $$

$$ if( \alpha < \alpha_{c}) \rightarrow F_{y\alpha} = (1-e^{(-A_{y}|\alpha/\alpha_{c}|)})\mu BF_{z} sign(1,\alpha) $$

$$ if( \alpha > \alpha_{c}) \rightarrow F_{y\alpha} = (1-e^{-A_{y}})\mu BF_{z} sign(1,\alpha) $$

$$ F_{y\gamma}=-F_{z}tan(\gamma) $$

$$ F_{y}=-F_{y\alpha}+F_{y\gamma} $$

## Aligning Torque Model

$$ C=C_{tz}+(|F_{z}|-R_{L})\frac{dC}{dF_{z}} $$

$$ L_{CP}=2(R_{1}^{2}-(\frac{R_{1}+F_{zk}}{K_{z}})^{2})^{0.5} $$

$$ x_{pt}=\frac{L_{CP}}{4} $$

$$ if( \alpha < \alpha_{c}) \rightarrow M_{z}=-F_{y\alpha}Cx_{pt}(1-|\frac{\alpha}{\alpha_{c}}|) $$

$$ if( \alpha > \alpha_{c}) \rightarrow M_{z}=0 $$

## Rolling Resistance Model

$$ if( V > 0) \rightarrow M_{y}=-C_{r}F_{z} $$

$$ if( V < 0) \rightarrow M_{y}=C_{r}F_{z} $$

The Harty model requires 14 parameters to model the tire:

|Harty Model Parameter|Unit Type|
|:---|:---:|
|$F_{z0}$ (Reference tire load)|force|
|$R1$ (Tire loaded radius)|length|
|$\alpha_c$ (Critical slip angle)|angle|
|$A_y$ (Curvature factor for lateral force)||
|$B_y$ (Scale factor for lateral force at reference tire load)||
|$dB/F_z$ (Dimunition of lateral force scale factor with load)||
|$S_c$ (Critical slip ratio)|ratio|
|$A_x$ (Curvature factor for longitudinal force)||
|$C_{tz}$ (Scale factor for aligning moment at reference tire load)||
|$dC/F_z$ (Dimunition of aligning moment scale factor with load)||
|$D_x$ (Scale factor for longitudinal force at reference tire load)||
|$dD/F_z$ (Dimunition of longitudinal force scale factor with load)||
|$K_z$ (Tire vertical stiffness)|force / length|
|$C_r$ (Rolling resistance coefficient)|length|