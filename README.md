# Data Mining Course

**Task 3**

- Victor Manuel Vargas Forero
- Paula Andrea Figueroa Polanco

In this exercise, the goal is to optimize the medication delivery process and inventory management of a healthcare service provider by applying association rule techniques. The objective is to identify patterns in the formulation of medications, meaning detecting which medications tend to be prescribed together more frequently. This will enable the entity to improve inventory planning and streamline the delivery of medications to patients.

To achieve this, a data mining algorithm such as Apriori will be used to identify the most frequent combinations of medications in prescriptions and generate association rules. These rules will not only show which medications are prescribed together but will also indicate the confidence in each rule, meaning the probability that if one medication is prescribed, another one is also likely to be prescribed.

# Conclusions
Based on the results table, we were able to reach the following key conclusions:
1.	Medications that tend to be prescribed together (Confidence): These are medications that, whenever one of them is prescribed, the other one is as well. To identify them in the results table, we selected those with a confidence of 100%. Some examples are:
  -	Amikacin and Vancomycin
  - Ampicillin and Amoxicillin-Clavulanate
  -	Cefalotin and Cisplatin
  - Omeprazole and Ranitidine.
    
2.	Medications with high association (Lift): Medications with a lift greater than 1 were identified, indicating the strength of the association between medications compared to being prescribed randomly. A lift greater than 1 suggests that the combination occurs more frequently than expected. For example, in the results table, we can find medication combinations with higher lift values:

| MEDICATION COMBINATIONS | LIFT |
| ------------- | ------------- |
| CEFALOTINA Y CLINDAMICINA | 77.15 |
| GENTAMICINA Y HEPARINA  | 68.66  |
| OMEPRAZOL Y RANITIDINA  | 47.37  |
| NAFAZOLINA Y SULFACETAMIDA | 41.34 |


This could indicate that these medication combinations are used together in specific medical treatments.

3.	Medications with high frequency (Support): Medications with high frequency calculate how often these medication combinations occur in the data, meaning how frequently they are prescribed together. Although all rules have low support, ranging from 0.004 to 0.065, it was found that the most frequent combination is Amikacin and Vancomycin, with a support of 0.036.
   
4.	Inventory improvement: Based on these results, the healthcare provider can prioritize stocking certain medications that are commonly prescribed together. For example, Amikacin and Vancomycin should always be in stock as both medications are frequently used together. The same applies to Cefalotin and Cisplatin, which show high lift values.
