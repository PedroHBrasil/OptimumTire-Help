---
Title: Brush Model
summary: This section details the Brush Model.
authors:
    - Pedro Brasil   
date: 2019/9/10
---

# Brush Model

Brush tire models can be very simple or very complex. The model included in OptimumTire is a very simple example of the brush model. The brush model is a physically based model that represents the tire as a row of elastic bristles that can deflect in the direction of the road. The deformation of these elements to applied forces represents the combined elasticity of the tire belt, carcass, and tread.

The model included in OptimumTire does not include the effects of inclination angle, the lateral force offset at zero slip (from tire conicity or ply steer), tire load sensitivity, or the fall off of force after the optimum slip has been reached. However, it does include the effects of combined lateral and longitudinal slip. 

|Brush Model Parameters|Unit Type|
|:---|:---:|
|Fz0 (Nominal vertical load)|force|
|mu (Coefficient of friction|ratio|
|cpy (Lateral tread element stiffness)|force / length|
|cpx (Longitundinal tread element stiffness)|force / length|
|a0 (Contact patch length at Fz0 divided by two|ratio|
