---
Title: Pacejka Coefficients
summary: This section details the Pacejka Coefficients.
authors:
    - Pedro Brasil   
date: 2019/9/10
---

# Pacejka Coefficients

The table below contains all of the Pacejka coefficients used in OptimumTire. These coefficients are grouped into nine different categories depending on what tire characteristics they describe: General, Pure Lateral, Pure Longitudinal, Aligning Torque, Combined Lateral, Combined Longitudinal, Combined Aligning Torque, Overturning Moment and Rolling Resistance. On the left the name and a brief description of the coefficient are given. On the right the "x" in the boxes indicates whether or not each coefficient is included in each of the specific Pacejka models.

<table>
    <thead>
        <tr>
            <th colspan="2" style="text-align:center">Pacejka Coefficients</th>
            <th colspan="4" style="text-align:center">Models</th> 
        </tr>
    </thead>
    <tbody>
        <tr>
            <th colspan="2" style="text-align:center">General</th>
            <th style="text-align:center">96</th> 
            <th style="text-align:center">02</th> 
            <th style="text-align:center">02Pi</th> 
            <th style="text-align:center">06</th> 
        </tr>
        <tr>
            <td style="text-align:center">Fz0</td>
            <td style="text-align:left">Nominal load</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">r0</td>
            <td style="text-align:left">Tire unloaded radius</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">V0</td>
            <td style="text-align:left">Reference velocity</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">P0</td>
            <td style="text-align:left">Reference pressure</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center">x</td>
            <td style="text-align:center"> </td>
        </tr>
        <tr>
            <th colspan="2" style="text-align:center">Pure Lateral</th>
            <th style="text-align:center">96</th> 
            <th style="text-align:center">02</th> 
            <th style="text-align:center">02Pi</th> 
            <th style="text-align:center">06</th> 
        </tr>
        <tr>
            <td style="text-align:center">pCy1</td>
            <td style="text-align:left">Shape Factor</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">pDy1</td>
            <td style="text-align:left">Lateral coefficient of friction at Fz0</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">pDy2</td>
            <td style="text-align:left">Variation of friction with load</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">pDy3</td>
            <td style="text-align:left">Variation of friction with camber squared</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">pEy1</td>
            <td style="text-align:left">Lateral curvature at Fz0</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">pEy2</td>
            <td style="text-align:left">Variation of curvature with load</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">pEy3</td>
            <td style="text-align:left">Zero order camber dependency of curvature</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">pEy4</td>
            <td style="text-align:left">Variation of curvature with camber</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">pEy5</td>
            <td style="text-align:left">Camber curvature</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">pKy1</td>
            <td style="text-align:left">Maximum cornering stiffness</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">pKy2</td>
            <td style="text-align:left">Load at which maximum stiffness occurs</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">pKy3</td>
            <td style="text-align:left">Variation of stiffness with camber</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">pKy4</td>
            <td style="text-align:left">Variation of stiffness with camber squared</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">pKy5</td>
            <td style="text-align:left">Lateral stiffness dependency with camber</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">pKy6</td>
            <td style="text-align:left">Camber stiffness factor</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">pKy7</td>
            <td style="text-align:left">Load dependency of camber stiffness factor</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">pHy1</td>
            <td style="text-align:left">Horizontal shift at Fz0</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">pHy2</td>
            <td style="text-align:left">Variation of horizontal shift with load</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">pHy3</td>
            <td style="text-align:left">Variation of horizontal shift with camber</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center"> </td>
        </tr>
        <tr>
            <td style="text-align:center">pVy1</td>
            <td style="text-align:left">Vertical shift at Fz0</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">pVy2</td>
            <td style="text-align:left">Variation of vertical shift with load</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">pVy3</td>
            <td style="text-align:left">Variation of vertical shift with camber</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">pVy4</td>
            <td style="text-align:left">Variation of vertical shift with load and camber</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">pPy1</td>
            <td style="text-align:left">Variation of cornering stiffness with inflation pressure</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center">x</td>
            <td style="text-align:center"> </td>
        </tr>
        <tr>
            <td style="text-align:center">pPy2</td>
            <td style="text-align:left">Variation of cornering stiffness with inflation and load</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center">x</td>
            <td style="text-align:center"> </td>
        </tr>
        <tr>
            <td style="text-align:center">pPy3</td>
            <td style="text-align:left">Variation of friction with inflation pressure</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center">x</td>
            <td style="text-align:center"> </td>
        </tr>
        <tr>
            <td style="text-align:center">pPy4</td>
            <td style="text-align:left">Variation of friction with inflation pressure squared</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center">x</td>
            <td style="text-align:center"> </td>
        </tr>
        <tr>
            <th colspan="2" style="text-align:center">Pure Longitudinal</th>
            <th style="text-align:center">96</th> 
            <th style="text-align:center">02</th> 
            <th style="text-align:center">02Pi</th> 
            <th style="text-align:center">06</th> 
        </tr>
        <tr>
            <td style="text-align:center">pCx1</td>
            <td style="text-align:left">Shape factor</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">pDx1</td>
            <td style="text-align:left">Longitudinal coefficient of friction at Fz0</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">pDx2</td>
            <td style="text-align:left">Variation of friction with load</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">pDx3</td>
            <td style="text-align:left">Variation of friction with camber</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
        </tr>
        <tr>
            <td style="text-align:center">pEx1</td>
            <td style="text-align:left">Longitudinal curvature at Fz0</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">pEx2</td>
            <td style="text-align:left">Variation of curvature with load</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">pEx3</td>
            <td style="text-align:left">Variation of curvature with load squared</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">pEx4</td>
            <td style="text-align:left">Factor in curvature while driving</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">pKx1</td>
            <td style="text-align:left">Longitudinal slip stiffness at Fz0</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">pKx2</td>
            <td style="text-align:left">Variation of slip stiffness with load</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">pKx3</td>
            <td style="text-align:left">Exponent in slip stiffness with load</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">pHx1</td>
            <td style="text-align:left">Horizontal shift at Fz0</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">pHx2</td>
            <td style="text-align:left">Variation of horizontal shift with load</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">pVx1</td>
            <td style="text-align:left">Vertical shift at Fz0</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">pVx2</td>
            <td style="text-align:left">Variation of vertical shift with load</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">pPx1</td>
            <td style="text-align:left">Variation of slip stiffness with inflation pressure</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center">x</td>
            <td style="text-align:center"> </td>
        </tr>
        <tr>
            <td style="text-align:center">pPx2</td>
            <td style="text-align:left">Variation of slip stiffness with inflation pressure squared</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center">x</td>
            <td style="text-align:center"> </td>
        </tr>
        <tr>
            <td style="text-align:center">pPx3</td>
            <td style="text-align:left">Variation of friction with inflation pressure</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center">x</td>
            <td style="text-align:center"> </td>
        </tr>
        <tr>
            <td style="text-align:center">pPx4</td>
            <td style="text-align:left">Variation of friction with inflation pressure squared</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center">x</td>
            <td style="text-align:center"> </td>
        </tr>
        <tr>
            <th colspan="2" style="text-align:center">Aligning Torque</th>
            <th style="text-align:center">96</th> 
            <th style="text-align:center">02</th> 
            <th style="text-align:center">02Pi</th> 
            <th style="text-align:center">06</th> 
        </tr>
        <tr>
            <td style="text-align:center">qBz1</td>
            <td style="text-align:left">Pneumatic trail slope factor at Fz0</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">qBz2</td>
            <td style="text-align:left">Variation of trail slope with load</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">qBz3</td>
            <td style="text-align:left">Variation of trail slope with load squared</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">qBz4</td>
            <td style="text-align:left">Variation of trail slope with camber</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">qBz5</td>
            <td style="text-align:left">Variation of trail slope with  absolute camber</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">qBz6</td>
            <td style="text-align:left">Variation of trail slope with camber squared</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">qBz9</td>
            <td style="text-align:left">Slope factor of residual torque</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">qBz10</td>
            <td style="text-align:left">Slope factor of residual torque</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">qCz1</td>
            <td style="text-align:left">Shape factor for pneumatic trail</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">qDz1</td>
            <td style="text-align:left">Peak pneumatic trail</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">qDz2</td>
            <td style="text-align:left">Variation of peak trail with load</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">qDz3</td>
            <td style="text-align:left">Variation of peak trail with camber</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">qDz4</td>
            <td style="text-align:left">Variation of peak trail with camber squared</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">qDz6</td>
            <td style="text-align:left">Peak residual torque</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">qDz7</td>
            <td style="text-align:left">Variation of peak torque with load</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">qDz8</td>
            <td style="text-align:left">Variation of peak torque with camber</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">qDz9</td>
            <td style="text-align:left">Variation of peak torque with camber and load</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">qDz10</td>
            <td style="text-align:left">Variation of peak torque with camber squared</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">qDz11</td>
            <td style="text-align:left">Variation of peak torque with camber squared and load</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">qEz1</td>
            <td style="text-align:left">Pneumatic trail curvature at Fz0</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">qEz2</td>
            <td style="text-align:left">Variation of curvature with load</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">qEz3</td>
            <td style="text-align:left">Variation of curvature with load squared</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">qEz4</td>
            <td style="text-align:left">Variation of curvature with sign of slip angle</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">qEz5</td>
            <td style="text-align:left">Variation of curvature with camber and sign of slip angle</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">qHz1</td>
            <td style="text-align:left">Pneumatic trail horizontal shift at Fz0</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">qHz2</td>
            <td style="text-align:left">Variation of horizontal shift with load</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">qHz3</td>
            <td style="text-align:left">Variation of horizontal shift with camber</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">qHz4</td>
            <td style="text-align:left">Variation of horizontal shift with camber and load</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">qPz1</td>
            <td style="text-align:left">Variation of peak with inflation pressure</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center">x</td>
            <td style="text-align:center"> </td>
        </tr>
        <tr>
            <th colspan="2" style="text-align:center">Combined Longitudinal</th>
            <th style="text-align:center">96</th> 
            <th style="text-align:center">02</th> 
            <th style="text-align:center">02Pi</th> 
            <th style="text-align:center">06</th> 
        </tr>
        <tr>
            <td style="text-align:center">rBy1</td>
            <td style="text-align:left">Slope factor for combined slip lateral force reduction</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">rBy2</td>
            <td style="text-align:left">Variation of lateral force slope reduction with slip angle</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">rBy3</td>
            <td style="text-align:left">Shift factor for slip angle in lateral force slope reduction</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">rBy4</td>
            <td style="text-align:left">Variation of lateral force combined stiffness with camber</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">rCy1</td>
            <td style="text-align:left">Shape factor for combined slip lateral force reduction</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">rEy1</td>
            <td style="text-align:left">Curvature factor of combined lateral force</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">rEy2</td>
            <td style="text-align:left">Curvature factor of combined lateral force with load</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">rHy1</td>
            <td style="text-align:left">Horizontal shift factor for lateral force reduction</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">rHy2</td>
            <td style="text-align:left">Horizontal shift factor for lateral force reduction with load</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">rVy1</td>
            <td style="text-align:left">Vertical shift at Fz0 for lateral force reduction</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">rVy2</td>
            <td style="text-align:left">Variation of vertical shift factor with load</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">rVy3</td>
            <td style="text-align:left">Variation of vertical shift factor with camber</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">rVy4</td>
            <td style="text-align:left">Variation of vertical shift factor with slip angle</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">rVy5</td>
            <td style="text-align:left">Variation of vertical shift factor with slip ratio</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">rVy6</td>
            <td style="text-align:left">Variation of vertical shift factor with the arctan of slip ratio</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <th colspan="2" style="text-align:center">Combined Longitudinal</th>
            <th style="text-align:center">96</th> 
            <th style="text-align:center">02</th> 
            <th style="text-align:center">02Pi</th> 
            <th style="text-align:center">06</th> 
        </tr>
        <tr>
            <td style="text-align:center">rBx1</td>
            <td style="text-align:left">Slope factor for combined slip longitudinal force reduction</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">rBx2</td>
            <td style="text-align:left">Variation of longitudinal force slope reduction with slip ratio</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">rBx3</td>
            <td style="text-align:left">Variation of longitudinal force combined stiffness with camber</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">rCx1</td>
            <td style="text-align:left">Shape factor for combined slip longitudinal force reduction</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">rEx1</td>
            <td style="text-align:left">Curvature factor of combined longitudinal force</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">rEx2</td>
            <td style="text-align:left">Curvature factor of combined longitudinal force with load</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">rHx1</td>
            <td style="text-align:left">Shift factor for combined slip longitudinal force reduction</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <th colspan="2" style="text-align:center">Combined Aligning Torque</th>
            <th style="text-align:center">96</th> 
            <th style="text-align:center">02</th> 
            <th style="text-align:center">02Pi</th> 
            <th style="text-align:center">06</th> 
        </tr>
        <tr>
            <td style="text-align:center">sSz1</td>
            <td style="text-align:left">Effect of longitudinal force on aligning torque</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">sSz2</td>
            <td style="text-align:left">Variation of aligning torque with lateral force</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">sSz3</td>
            <td style="text-align:left">Variation of aligning torque with camber</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">sSz4</td>
            <td style="text-align:left">Variation of aligning torque with camber and load</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <th colspan="2" style="text-align:center">Overturning Moment</th>
            <th style="text-align:center">96</th> 
            <th style="text-align:center">02</th> 
            <th style="text-align:center">02Pi</th> 
            <th style="text-align:center">06</th> 
        </tr>
        <tr>
            <td style="text-align:center">qSx1</td>
            <td style="text-align:left">Vertical force induced overturning moment</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">qSx2</td>
            <td style="text-align:left">Camber induced overturning moment</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">qSx3</td>
            <td style="text-align:left">Lateral force induced overturning moment</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <th colspan="2" style="text-align:center">Rolling Moment</th>
            <th style="text-align:center">96</th> 
            <th style="text-align:center">02</th> 
            <th style="text-align:center">02Pi</th> 
            <th style="text-align:center">06</th> 
        </tr>
        <tr>
            <td style="text-align:center">qSy1</td>
            <td style="text-align:left">Rolling resistance torque coefficient</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
        <tr>
            <td style="text-align:center">qSy2</td>
            <td style="text-align:left">Variation of rolling resistance torque with load</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
            <td style="text-align:center">x</td>
        </tr>
    </tbody>
</table>