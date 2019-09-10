---
Title: Pacejka Models
summary: This section details the Pacejka Models.
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

# Pacejka Models

The Pacejka "Magic Formula" tire models are empirical relations that model the steady-state forces and moments produced by the tire as a function of the tire conditions (i.e. slip angle, slip ratio, inclination angle, etc...). These models include combined longitudinal and lateral force effects, inclination angle effects, lateral and longitudinal force offset, and tire load sensitivity. The primary form for the Pacejka models is given in the equations below. The table following these equations describes the various parameters.

$$ y=D\sin \left\\{ C\arctan\left[Bx-E\left(Bx-\arctan{Bx}\right)\right] \right\\} $$

With

$$ Y(X)= y(x)+ S_V $$

$$ x=X+S_H $$

<table>
    <thead>
        <tr>
            <th colspan="2" style="text-align:center">Input/Output</th>
            <th style="text-align:center">Description</th> 
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="text-align:center">Y</td>
            <td style="text-align:center">Output</td>
            <td style="text-align:left">Lateral force, longitudinal force, or aligning torque</td>
        </tr>
        <tr>
            <td style="text-align:center">X</td>
            <td style="text-align:center">Input</td>
            <td style="text-align:left">Slip ratio or tangent slip angle</td>
        </tr>
        <tr>
            <th colspan="2" style="text-align:center">Parameter</th>
            <th style="text-align:center">Description</th> 
        </tr>
        <tr>
            <td style="text-align:center">B</td>
            <td style="text-align:center">Stiffness Factor</td>
            <td style="text-align:left">Slope at Origin</td>
        </tr>
        <tr>
            <td style="text-align:center">C</td>
            <td style="text-align:center">Shape Factor</td>
            <td style="text-align:left">Shape of the resulting curve</td>
        </tr>
        <tr>
            <td style="text-align:center">D</td>
            <td style="text-align:center">Peak Value</td>
            <td style="text-align:left">Peak Value with C>=1</td>
        </tr>
        <tr>
            <td style="text-align:center">E</td>
            <td style="text-align:center">Curvature Factor</td>
            <td style="text-align:left">Curvature and horizontal position of the peak</td>
        </tr>
        <tr>
            <td style="text-align:center">H</td>
            <td style="text-align:center">Horizontal shift</td>
            <td style="text-align:left"> </td>
        </tr>
        <tr>
            <td style="text-align:center">V</td>
            <td style="text-align:center">Vertical shift</td>
            <td style="text-align:left"> </td>
        </tr>
    </tbody>
</table>

A description of the Pacejka models implemented in OptimumTire is given in this section. In [Pacejka Coefficients](../9_References/H_Pacejka_Coefficients.md), the coefficients used in these models are summarized.

## Pacejka '96

This model is given in the 1996 paper "The Tire as a Vehicle Component" by Hans B. Pacejka. This model includes the combined lateral and longitudinal tire response as well as lateral camber response and load sensitivity. This model does not include the rolling resistance or overturning moment of the tire. This model includes 78 coefficients.

## Pacejka 2002

This model is given in Pacejka's book "Tire and Vehicle Dynamics" published in 2002. It is similar to the '96 model but has additional coefficients in the combined lateral and longitudinal models. It also includes models for the rolling resistance and overturning moment. This model includes 89 coefficients.

## Pacejka 2002 with Inflation Pressure Effects

This model is described in the paper "Extending the Magic Formula and SWIFT Tyre Models for Inflation Pressure Changes" by Dr. Ir. A.J.C. Schmeitz, Dr. Ir. I.J.M. Besselink, Ir. J. de Hoogh, and Dr. H. Nijmeijer. This model incorporates the effect of inflation pressure into the Pacejka 2002 model. Ten additional coefficients, including the reference pressure Pi0, are added to the model. These coefficients appear in the pure lateral, longitudinal, and aligning torque models. This model includes 99 coefficients.

## Magic Formula 5.2

This model is a close development of the the Pacejka 2002 model. This model differs from Pacejka 2002 in the way that it models the effect of camber. The main advantage of the MF5.2 model is that models the effect of camber on the longitudinal coefficient of friction. This model includes 90 coefficients.

## Magic Formula 6.1

This model is a further development of the the Magic Formula 5.2 model. This model improves the description of camber, allowing the model to handle a very large range of camber angles. This makes special "`special"' motorcycle Magica Formula superfluous. In addition the model also allows for better modelling of inflation pressure changes and rolling resistance. For most tires the Magic Formula 6.1 will give slightly better results compared to Magic Formula 5.2. This model includes 155 coefficients.

## Pacejka 2006

This model is given in the second edition of Pacejka's book "Tire and Vehicle Dynamics" published in 2006. This model is based off of the 2002 model but includes significant modifications to the pure lateral and aligning torque models. An additional coefficient is also added to both the combined lateral and longitudinal models. This model includes 97 coefficients.
