# Faulty-Steel-Plates
## Description
This dataset comes from research by Semeion, Research Center of Sciences of Communication. The original aim of the research was to correctly classify the type of surface defects in stainless steel plates, with six types of possible defects (plus "other"). The Input vector was made up of 27 indicators that approximately [describe] the geometric shape of the defect and its outline. According to the research paper, Semeion was commissioned by the Centro Sviluppo Materiali (Italy) for this task and therefore it is not possible to provide details on the nature of the 27 indicators used as Input vectors or the types of the 6 classes of defects.
## Dataset
There are 34 fields. The first 27 fields describe some kind of steel plate faults seen in images. Unfortunately, there is no other information that I know of to describe these columns.

- X_Minimum
- X_Maximum
- Y_Minimum
- Y_Maximum
- Pixels_Areas
- X_Perimeter
- Y_Perimeter
- SumofLuminosity
- MinimumofLuminosity
- MaximumofLuminosity
- LengthofConveyer
- TypeOfSteel_A300
- TypeOfSteel_A400
- SteelPlateThickness
- Edges_Index
- Empty_Index
- Square_Index
- OutsideXIndex
- EdgesXIndex
- EdgesYIndex
- OutsideGlobalIndex
- LogOfAreas
- LogXIndex
- LogYIndex
- Orientation_Index
- Luminosity_Index
- SigmoidOfAreas

The last seven columns are one hot encoded classes, i.e. if the plate fault is classified as "Stains" there will be a 1 in that column and 0's in the other columns. If you are unfamiliar with one hot encoding, just know that the last seven columns are your class labels.

- Pastry
- Z_Scratch
- K_Scatch
- Stains
- Dirtiness
- Bumps
- Other_Faults

EDA, feature engineering - https://nbviewer.jupyter.org/github/planeta-237/Faulty-Steel-Plates/blob/main/EDA%2C%20Feature%20engineering.ipynb
