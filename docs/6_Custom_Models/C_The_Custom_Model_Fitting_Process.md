---
Title: The Custom Models Fitting Process
summary: This section details how to the fitting of custom models is done.
authors:
    - Pedro Brasil   
date: 2019/9/9
---

# The Custom Models Fitting Process

To fit a custom model the user can follow the same process used for standard model fitting. The __Custom Model__ option should appear at the bottom of the list of models available to fit in the model fitting dropdown menu as shown in the figure below.

![Custom Model Fitting](../img/6_Custom_Models/6_C_custom_model_fitting.png)

Selecting the __Custom Model__ item from the dropdown will bring up the __Custom Model Selection Dialog__ shown in the figure below. Select the custom model to be fit by either double clicking on it, or selecting it and clicking the __OK__ button. This will launch the fitting process.

![Custom Tire Model Selection](../img/6_Custom_Models/6_C_custom_tire_model_selection.png)

The main differences in the custom fitting process are the constraints and boundary files. Which coefficients appear in the __Constraints Wizard__ will depend on the __Constraint Boolean__ specified in the coefficient file created by the user (see [Creating a Coefficient File](../6_Custom_Models/A_Creating_Custom_Models.md#Creating-a-Coefficient-File)). Also the boundaries wizard will not contain predefined templates so a new boundary must be created for each new custom model.
