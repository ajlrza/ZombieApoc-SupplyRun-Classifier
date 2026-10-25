# ZombieApoc-SupplyRun-Classifier
A mini XGB classifier model trained to classify indicators of zombie status before sending out supplies.

Note: Only permutation importance on features were extracted and analyzed

# What Matters

<img width="1112" height="662" alt="image" src="https://github.com/user-attachments/assets/0eeb49fc-1ded-40c8-b88b-445eb6ccf779" />

# Analysis

Depending on the rurality of a place, zombies are likely to be in densely populated rurality such as suburban or urban. Age also plays a 
factor in identifying uninfected and infected. Those that are incapable such as the elderly may be already infected, while those that are still capable, rurality is why
they are uninfected and infected. Military personnel are advice to exhaust extra caution when navigating suburban and urban places and be mindful of each spaces. It is also
important to prioritize the younger adults and older adults in handing out supplies, ensuring their survivability. If possible, suburbans and urbans should be a target for military
extermination and must evacuate any survivors first. Sanitation is required by survivors first and foremost among the other supplies, as the apocalypse has brought on disorder in society and unclean surroundings
become rampant. And without food, survivors would have no chance to survive, followed by clothing which protects them from heat and possible zombie attacks. 
No matter the sex of survivors, they are all equal in survivability.

# Dataset
**N = 200 ADULTS**

**FEATURES:** ```[Age, Sex, Rurality, Household, Water, Food, Medication, Tools, First-aid, Sanitation, Clothing]```

```
zombieid: unique identifier
zombie: human or zombie
age: age in years
sex: male or female
rurality: rural, suburban, or urban
household: number of people living in household
water: gallons of clean water available
food: food or no food
medication: medication or no medication
tools: tools or no tools
firstaid: first aid or no first aid
sanitation: sanitation or no sanitation
clothing: clothing or no clothing
documents: documents or no documents
```

**SOURCE:** https://www.kaggle.com/code/kingabzpro/zombie-apocalypse/notebook
