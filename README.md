# Instructions: How to use the catalogue
## Enable Macros
To enable the full functionality of the catalogue, you must first enable macros in the document.
If the macros are disabled, there should be a security warning at the top of the screen.
Press the "**Enable Content**"-button to enable the macro functionality in the document.
<img width="838" height="91" alt="billede" src="https://github.com/user-attachments/assets/6dc25001-07f5-42b6-be8d-c4c09827f58e" />

## Catalogue
The sheet named "**Catalogue**" contains a catalogue of different building materials and a selection of environmental impacts associated with their disposal.
You should not be editing in this sheet when simply using the catalogue.
By pressing the **+**-symbol on the left side of the screen, you can expand the material to see the different disposal scenarios and their associated impacts.

**Column A** contains the name of the material.

**Column B** contains an image of the material and ID-numbers of each scenario.
The ID-numbers correspond to the name of an Excel-file in the "**[LCI]([<Your Download Link here>](https://github.com/GustavS193940/Catalogue-of-value-creation-processes-for-building-materials/tree/cf0c38de1a39aad33826288989a4168c97468ab8/LCI)) **"-folder.
This Excel-file contains the life cycle inventory (LCI) as well as a detailed description of the scenario with the corresponding ID-number.

**Column D** contains the declared unit of the material and names of each scenario.

**Column E** contains the mass factor (kg/unit) of the material and short descriptions of each scenario.

**Column I** contains the circulariy level of each scenario.
The catalogue categorises each scenario into one of five different circularity levels.
The lower the number, the more circular the scenario is.

<img width="626" height="223" alt="billede" src="https://github.com/user-attachments/assets/b4172856-5576-4b89-907b-86c0433918d6" />

**Column J** contains the **Global warming** impacts of each scenario expressed in **kg CO2eq**.

**Column K** contains the **Land use** impacts of each scenario expressed in **m²a crop eq**.

**Column L** contains the **Mineral ressource scarcity** impacts of each scenario expressed in **kg CU eq**.

**Column M** contains the **Fossil ressource scarcity** impacts of each scenario expressed in **kg oil eq**.

**Column N** and **Column O** contain a visual comparison of the environmental impacts associated with every scenario of the material.
You can change which impact category is shown in the comparison graph by choosing a different one in the "**Impact Category:**" drop-down.

<img width="576" height="438" alt="billede" src="https://github.com/user-attachments/assets/ca24eb20-64d6-4ebf-a4ff-628c034e03c6" />

## Building Scenarios
In the two sheets named "**Building Scenario 1**" and "**Building Scenario 2**" you can input the materials in your project to see the environmental impacts at a building level for two separate scenarios.
For example, "**Building Scenario 1**" could be the recommendations for the project and "**Building Scenario 2**" could be a worst case scenario.
To add a material to your project, first find the category corresponding to where the material is in the building, i.e. if it is a material in the internal walls, you will want to add it under "**3. Internal walls**".
Find and choose the material in the "**Choose Material:**" drop-down and press the "**ADD**"-button.
(Note: You will have to do this in both sheets if you want to compare scenarios)

<img width="771" height="438" alt="billede" src="https://github.com/user-attachments/assets/43bd76eb-b2c7-4be3-99d9-767eb83940e5" />

Next, you will want to enter the amount of the material in the project.
In the case of gypsum boards, this would be how many 1 m² of gypsum board are in the building.
Enter this number in the "**Amount**"-field of the material. It should say "1" by default.
Once you have done this, the environmental impacts will have scaled with the amount.

<img width="840" height="263" alt="billede" src="https://github.com/user-attachments/assets/9f3719f0-162a-467a-837e-4746ab0cbb4a" />

The next step is to choose a disposal scenario for each of the building scenario.
For example, you could choose the "**Recycling**" scenario in "**Building Scenario 1**" and the "**Landfill**" scenario in "**Building Scenario 2**".
To do this, check the box of the scenario you want to choose. When chosen, the corresponding row will turn green.
(Note: Do not choose more than one scenario for a single instance of a material as this will result in double counting in the calculations.)

<img width="399" height="460" alt="billede" src="https://github.com/user-attachments/assets/cea15906-d5c6-4ba9-b180-42b3b9c88d63" /> <img width="404" height="465" alt="billede" src="https://github.com/user-attachments/assets/8103d654-a424-4329-ab18-cc6cbb6d8abb" />

You will want to repeat this process for each material you want to include in your analysis.
It is possible to add multiple instances of the same material. For example, you may have stone wool insulation in both the external walls and the roof, you can add it to both and enter separate amounts and scenarios.

## Results
The "**Results**" sheet calculates the total impacts of decisions made for each building scenario.
It also provides comparative graphs for each of the environmental impacts included in the catalogue.

<img width="987" height="661" alt="billede" src="https://github.com/user-attachments/assets/09d47ff0-3ad7-4efb-a50e-f0ab83f0cd01" />
