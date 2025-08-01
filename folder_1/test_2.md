# Data Extraction for Environmental Product Declaration
------

## Table of Contents
1. [Project Overview](#project-overview)
2. [The Environmental Product Declaration](#The-Environmental-Product-Declaration)
3. [Visualize the extracted](#Visualize-the-extracted)
4. [Clear Summary of the Task](#Clear-Summary-of-the-Task)
5. [Parameters in Data Extraction](#Parameters-in-Data-Extraction)
6. [Data Preprocessing](#Data-Preprocessing)
   * [Removing Duplicates](#Removing-Duplicates)
7. [Data Visualization](#Data-Visualization)

## Project Overview
The Environmental Product Declaration (EPD) project aimed to extract valuable information from a dataset containing product descriptions with a focus on environmental impact. Postman was used in scrapping all the existing EPDs valid till 2023, using ECO Platform API. Out of 6820 EPDs valid till 2023, 100 EPDs were randomly selected.
One major challenge encountered during the project execution was that most documents were not in a consistent format. This was resolved by carefully evaluating each of the documents. 

## Clear Summary of the Task
The overarching goal of the data extraction process is to compile and analyze information from EPDs to provide stakeholders with comprehensive insights into the environmental performance of products.

## Parameters in Data Extraction
EPD Code, Group, EPD owner, EPD Programme Operator, Product Name, Registration No, Data Type,	Product Information, Product Category, Valid From, Valid To,	Geographical Representativeness, Temporal Representativeness, Standard Considered, Product Category Rules, Functional Unit, Declared unit, LCA database, LCA software, Global warming potential total (GWP-total)/ Climate change (kg CO2-eq), Global warming potential fossil fuels (GWP-fossil)/ Climate change (kg CO2-eq),	Global warming potential biogenic (GWP-biogenic)/ Climate change (kg CO2-eq), Global warming potential land use and land use change (GWP-luluc) / Climate change (kg CO2-eq), Ozone layer depletion / Stratospheric ozone depletion (kg CFC-11-eq), Acidification potential (mol H+ eq), Eutrophication aquatic freshwater (kg P eq),Eutrophication aquatic marine (kg N eq), Eutrophication aquatic terrestrial (mol N eq), Eutrophication Potential according to ISO 21930-2017 (kg PO4 3-eq), Photochemical ozone formation (kg NMVOC eq), Depletion of abiotic resources - mineral and metals (kg Sb eq), Depletion of abiotic resources - fossil fuels (MJ), Water use (m3-eq), Particulate matter emissions (Disease incidence), Ionizing radiation human health (kBq U235 eq), Eco-toxicity (freshwater) (CTUe),	Human toxicity, cancer (CTUh),	Human toxicity, non-cancer effects (CTUh), Soil Quality(Pt), Use of renewable primary energy excluding renewable primary energy resources used as raw materials (MJ), Use of renewable primary energy resources used as raw materials (MJ), Total use of renewable primary energy resources (primary energy and primary energy resources used as raw materials (MJ), Use of non-renewable primary energy excluding renewable primary energy resources used as raw materials (MJ),	Use of non-renewable primary energy resources used as raw materials (MJ), Total use of non-renewable primary energy resources (primary energy and primary energy resources used as raw materials (MJ),	Use of secondary material (kg), Use of renewable secondary fuels (MJ),	Use of non-renewable secondary fuels (MJ), Recovered energy (MJ), Consumption of fresh water  (m3), Net use of fresh water  (m3), Hazardous waste disposed (kg), Non-hazardous waste disposed (kg), Radioactive waste disposed (kg), Components for re-use (kg), Materials for recycling (kg), Materials for energy recovery (kg),  Exported Energy (MJ), Biogenic removals and emissions within bio-based products (kg CO2 eq. (100 years), Biogenic removals and emissions within packaging (kg CO2 eq. (100 years), Biogenic carbon content in product (kg C)	, Biogenic carbon content in accompanying packaging (kg C), Removals and emissions from calcination and carbonation - ISO21930 (kg CO2 eq. (100 years), Biogenic CO2 (combustion of waste) - ISO21930 (kg CO2 eq. (100 years), Biogenic CO2 (leaving the product system) - ISO21930 (kg CO2 eq. (100 years)

## Data Preprocessing
### Removing Duplicates
* Checking for Duplicates
```sql
SELECT *
FROM table
```

I used a `SELECT` statement.

**This is a Bold text.**
*This is Italics.*
_This is italics._

> [!NOTE]
> Always add comments in your SQl codes.


> [!IMPORTANT]
> This is important

> [!TIP]
> This is a tip

> [!CAUTION]
> This is a warning.



## Data Visualization
Visualize the extracted information using charts, graphs, and other visualization techniques to provide insights into the EPDs' data quality assurance levels.

**Number of EPDs and Owners**

![image](https://github.com/AngelGabby/Data-Extraction-for-Environmental-Product-Declaration/assets/34291140/7c7d244b-35d2-44d9-961b-d9d0fdfaf4d9)


<figure>
  <img src="https://github.com/AngelGabby/Data-Extraction-for-Environmental-Product-Declaration/assets/34291140/7c7d244b-35d2-44d9-961b-d9d0fdfaf4d9" width=100% height=100% alt="alt text">
  <figcaption>Figure: Number of EPDs and Owners</figcaption>
</figure>
<br/><br/>


**Functional Unit**

![:book:](https://github.com/AngelGabby/Data-Extraction-for-Environmental-Product-Declaration/assets/34291140/8420cb2e-d510-4d42-9cce-8dbfbce449ef)


**Geographical Representativeness**

![image](https://github.com/AngelGabby/Data-Extraction-for-Environmental-Product-Declaration/assets/34291140/01f79180-029f-4870-b2ab-6b09730b5a7b)








