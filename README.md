# Intensity-Map
The Intensity Map program primarily focuses on the field of land science. It provides a pedigree-based method for determining and visualizing land use change patterns. By utilizing a land use transfer matrix, the program calculates the absolute and relative intensities of land use changes. This information is then used to construct a spectrum of land use change intensities for various time intervals. The program further fills in the spectrum of land use change intensities for blank time intervals using both absolute and relative intensities of land use change, ultimately generating a comprehensive intensity spectrum of land use changes. The purpose of the Intensity Map program is to address the limitations of transfer matrices in intuitively assessing multi-time interval trends in land use transitions and their impact on land use structure. It aims to analyze patterns and regularities in land use changes, with the ultimate goal of facilitating land use risk assessment.
# Data Preparation
Prepare land use change data for the initial and final periods within different time intervals in the study area. Create land use transfer matrices, where each row represents the transition from various initial land classes, and each column represents the transition to various final land classes. Below is an example dataset.
Specifically, the land use transfer matrix includes six land use types: cropland, woodland, grassland, water bodies, built-up areas, and unused land. The two time intervals are 2000-2010 and 2010-2020. The land use transfer matrix for the period 2000-2010 is shown in Table 1, and for the period 2010-2020 in Table 2. The numbers in the tables represent areas in 10³ square kilometers.
|             | Cropland | Woodland | Grassland | Water Bodies | Built-up Areas | Unused Land |
|-------------|----------|----------|-----------|--------------|----------------|-------------|
| Cropland    | 17.95    | 0.09     | 0.53      | 0.04         | 0.29           | 0.13        |
| Woodland    | 0.02     | 8.74     | 0.10      | 0.00         | 0.02           | 0.00        |
| Grassland   | 0.68     | 0.12     | 57.44     | 0.04         | 0.05           | 0.08        |
| Water Bodies| 0.01     | 0.00     | 0.01      | 4.12         | 0.01           | 0.03        |
| Built-up Areas| 0.10   | 0.00     | 0.02      | 0.00         | 1.27           | 0.00        |
| Unused Land | 0.03     | 0.01     | 1.20      | 0.08         | 0.01           | 6.39        |

|             | Cropland | Woodland | Grassland | Water Bodies | Built-up Areas | Unused Land |
|-------------|----------|----------|-----------|--------------|----------------|-------------|
| Cropland    | 15.47    | 0.12     | 2.59      | 0.09         | 0.46           | 0.07        |
| Woodland    | 0.12     | 8.18     | 0.59      | 0.01         | 0.03           | 0.01        |
| Grassland   | 2.55     | 0.60     | 55.45     | 0.09         | 0.28           | 0.33        |
| Water Bodies| 0.07     | 0.01     | 0.08      | 4.09         | 0.01           | 0.01        |
| Built-up Areas| 0.26   | 0.01     | 0.08      | 0.01         | 1.27           | 0.01        |
| Unused Land | 0.12     | 0.01     | 0.32      | 0.04         | 0.02           | 6.12        |
# Run
- Enter the number of land categories in the "Number of Categories" input field, and input the number of time points in the "Number of Points" input field.
![image](https://github.com/Mr-ShiRui/Intensity-Map/assets/142878280/9b29dfb8-ef50-4285-9f1b-7d207ea2bc67)
- In the "Category" field, input the names of the land categories you want to analyze, either individually or you can copy and paste a list of land category names. In the "Time" field, input the corresponding years.
![image](https://github.com/Mr-ShiRui/Intensity-Map/assets/142878280/f314348f-b6a5-48ba-aee8-028fe15dedaf)
- Input the prepared land use transfer matrix data into the generated blank dialog box for the transfer matrix. You can either manually enter the data or copy and paste it in bulk.
![image](https://github.com/Mr-ShiRui/Intensity-Map/assets/142878280/89f4e402-bcf7-4f8a-81c3-76c72f37a649)
- The software will automatically generate a land use change intensity spectrum graph and a data table. In the "Intensity Map" interface, click the "Export Map" button located in the bottom right corner to download the land use change intensity spectrum graph in Excel xlsx format to your designated location on the computer.
- In the "Intensity Analysis" interface, click the "Export Analysis" button in the bottom right corner to similarly download the land use change intensity data table in Excel xlsx format to your designated location on the computer.
![image](https://github.com/Mr-ShiRui/Intensity-Map/assets/142878280/e5b29d46-d671-4b69-91d8-2b0b76d657bb)

