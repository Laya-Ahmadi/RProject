# RProject

# Motivation
My PhD Project is mostly about Upscaling the effect of agricultural activities on the water quality of Lake Erie. The main goal is assessing the effectiveness of agricultural land management practices to reduce nutrient losses to the Great Lakes by analyzing and comparing:
- Ontario data of farmer behaviours/activities
- Watershed modeling

Start working with the available dataset to get familiar with the available data  and its format.

# Objectives
Based on literature review, the method that farmers use to apply fertilizer and the timing of the application matter in how much micronutrients will spread in surface water and the objective is to know these factors better and quantify their effect as much as possible.

for some of the application method the fertilizer would tilled down in the soil so the odds of washing away by the surface water is lower. On the other hand the application used for applying manure or fertilization depends on various factors such as land area, crop type, equipment the farmer has access to and etc.

questions:
1- Can we use the crop type and the area of the field to predict whether a field has been fertilized or not?
In this case the outcome is binary so we can use binary logistic regression.
2- What is the probability of using each application method for three dominant crop type in the basin over the range of field area?
In this case the outcome is non-binary and we can use multinomial logistic regressions to calculate the odds of each outcome category.

# dominant crop types
- Corn
- Wheat
- Soybeans
