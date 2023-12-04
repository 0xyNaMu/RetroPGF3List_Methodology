# RetroPGF3List_Methodology
Here you'll find some of the methodology for my lists.


# Optimism Translators:
Data can be found here: https://docs.google.com/spreadsheets/d/1hVWSrZKrt3Cp7cC5ZFX10-E1KSR4s_58Zg_iCjgt85c/edit#gid=0

1. Calculated the average number of words per article included in the RetroPGF application, 
2. Calculated the total number of words translated per language, per type of contribution (Mirror articles vs official (technical) documentation), 
For Mirror articles:
i. Categorized the "translated into" languages into 4 groups based on their translation pair "rarity" (how uncommon they are in the translation market),
ii. Categorized the "translated into" languages into 5 groups based on the size of the languages' speaking population (1 most spoken - 5 least spoken),
iii. Multiplied the number of translated words per language by the rarity level as a percentage (1% most common, 4% rarest pairs)
iv. Multiplied the result of iii) by their speaking population group with the logic (0% for least spoken, 10% for most spoken). (I think this is fine because this is where community-tailored content shines.
Python script under "Optimism translators" doc
