---
Title: Model Fitting Order
summary: This section describes the recommended order to fit the data.
authors:
    - Pedro Brasil   
date: 2019/9/5
---

# Model Fitting Order

The order in which the models are fit can vary depending on the tire data available and the goals of the project. However, since some of the models are dependent on each other there are some restrictions on the order. The table in [Additional Models](../4_Tire_Models/C_Fitting_Models_To_Raw_Data.md#Additional-Models) shows what models are required before other models can be fit. This is also displayed in the Model Fitting Selection window in OptimumTire. These requirements, which will vary depending on the type of model being fit, can be seen to the right of the dropdown boxes in the figure below.

![Model Fitting Requirements](../img/4_Tire_Models/4_C_model_fitting_selection.png)

The two most common model fitting sequences are described in the tables below. The first sequence uses pure lateral and combined data like the model fitting example in the previous sections. The second sequence uses pure lateral, pure longitudinal and combined data. Under __Coefficients to be Fixed__ the __Fix__ indicates that these coefficients should be selected in the __Advanced Fitting Options__ window. Under __Coefficients to be Fit__ the __FE__ indicates that these coefficients should be set to __Fit and Calculate Error__ and the __Fit__ indicates that these coefficients should be set to __Fit__ in the __Model Fitting Selection__ window.

<table>
    <thead>
        <tr>
            <th colspan="14" style="text-align:center">Model Fitting with Pure Lateral and Combined Data</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan="3" style="text-align:center">Step</td>
            <td rowspan="3" style="text-align:center">Data Used</td>
            <td colspan="6" style="text-align:center">Coefficients to be Fixed</td>
            <td colspan="6" style="text-align:center">Coefficients to be Fit</td>
        </tr>
        <tr>
            <td colspan="3" style="text-align:center">Pure</td>
            <td colspan="3" style="text-align:center">Combined</td>
            <td colspan="3" style="text-align:center">Pure</td>
            <td colspan="3" style="text-align:center">Combined</td>
        </tr>
        <tr>
            <td style="text-align:center">Fx</td>
            <td style="text-align:center">Fy</td>
            <td style="text-align:center">Mz</td>
            <td style="text-align:center">Fx</td>
            <td style="text-align:center">Fy</td>
            <td style="text-align:center">Mz</td>
            <td style="text-align:center">Fx</td>
            <td style="text-align:center">Fy</td>
            <td style="text-align:center">Mz</td>
            <td style="text-align:center">Fx</td>
            <td style="text-align:center">Fy</td>
            <td style="text-align:center">Mz</td>
        </tr>
        <tr>
            <td style="text-align:center">1</td>
            <td style="text-align:center">Pure Lat.</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center">Fe</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
        </tr>
        <tr>
            <td style="text-align:center">2</td>
            <td style="text-align:center">Pure Lat.</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center">Fix</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center">Fe</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
        </tr>
        <tr>
            <td style="text-align:center">3</td>
            <td style="text-align:center">Combined</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center">Fix</td>
            <td style="text-align:center">Fix</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center">Fit</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center">Fe</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
        </tr>
        <tr>
            <td style="text-align:center">4</td>
            <td style="text-align:center">Combined</td>
            <td style="text-align:center">Fix</td>
            <td style="text-align:center">Fix</td>
            <td style="text-align:center">Fix</td>
            <td style="text-align:center">Fix</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center">Fe</td>
            <td style="text-align:center"> </td>
        </tr>
        <tr>
            <td style="text-align:center">5</td>
            <td style="text-align:center">Combined</td>
            <td style="text-align:center">Fix</td>
            <td style="text-align:center">Fix</td>
            <td style="text-align:center">Fix</td>
            <td style="text-align:center">Fix</td>
            <td style="text-align:center">Fix</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center">Fe</td>
        </tr>
    </tbody>
</table>


<table>
    <thead>
        <tr>
            <th colspan="14" style="text-align:center">Model Fitting with Pure Lateral, Pure Longitudinal and Combined Data</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan="3" style="text-align:center">Step</td>
            <td rowspan="3" style="text-align:center">Data Used</td>
            <td colspan="6" style="text-align:center">Coefficients to be Fixed</td>
            <td colspan="6" style="text-align:center">Coefficients to be Fit</td>
        </tr>
        <tr>
            <td colspan="3" style="text-align:center">Pure</td>
            <td colspan="3" style="text-align:center">Combined</td>
            <td colspan="3" style="text-align:center">Pure</td>
            <td colspan="3" style="text-align:center">Combined</td>
        </tr>
        <tr>
            <td style="text-align:center">Fx</td>
            <td style="text-align:center">Fy</td>
            <td style="text-align:center">Mz</td>
            <td style="text-align:center">Fx</td>
            <td style="text-align:center">Fy</td>
            <td style="text-align:center">Mz</td>
            <td style="text-align:center">Fx</td>
            <td style="text-align:center">Fy</td>
            <td style="text-align:center">Mz</td>
            <td style="text-align:center">Fx</td>
            <td style="text-align:center">Fy</td>
            <td style="text-align:center">Mz</td>
        </tr>
        <tr>
            <td style="text-align:center">1</td>
            <td style="text-align:center">Pure Lat.</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center">Fe</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
        </tr>
        <tr>
            <td style="text-align:center">2</td>
            <td style="text-align:center">Pure Lat.</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center">Fix</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center">Fe</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
        </tr>
        <tr>
            <td style="text-align:center">3</td>
            <td style="text-align:center">Combined</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center">Fix</td>
            <td style="text-align:center">Fix</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center">Fe</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
        </tr>
        <tr>
            <td style="text-align:center">4</td>
            <td style="text-align:center">Combined</td>
            <td style="text-align:center">Fix</td>
            <td style="text-align:center">Fix</td>
            <td style="text-align:center">Fix</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center">Fe</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
        </tr>
        <tr>
            <td style="text-align:center">5</td>
            <td style="text-align:center">Combined</td>
            <td style="text-align:center">Fix</td>
            <td style="text-align:center">Fix</td>
            <td style="text-align:center">Fix</td>
            <td style="text-align:center">Fix</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center">Fe</td>
            <td style="text-align:center"> </td>
        </tr>
        <tr>
            <td style="text-align:center">6</td>
            <td style="text-align:center">Combined</td>
            <td style="text-align:center">Fix</td>
            <td style="text-align:center">Fix</td>
            <td style="text-align:center">Fix</td>
            <td style="text-align:center">Fix</td>
            <td style="text-align:center">Fix</td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center"> </td>
            <td style="text-align:center">Fe</td>
        </tr>
    </tbody>
</table>