# Preprocessing_unplash_dataset
Unsplash Image Dataset Preprocessing and Fusion


This repository contains a comprehensive data preprocessing and fusion workflow for the Unsplash Image Dataset. The dataset is rich in image attributes, keywords, conversions, colors, and collections. The goal of this project is to prepare and integrate this diverse data, creating a consolidated dataset for advanced analysis and modeling.

**Key Features**:
**Data Import and Initial Filtering**:

**Load the Unsplash Image Dataset** 
Initial filtering to exclude rows with missing values in the 'ai_description' column.

**Attribute Selection:** 

Select relevant attributes for analysis, including image attributes, exif data, and location information.

**Keyword Integration:** 

Merge the dataset with a keywords dataset based on the 'photo_id' column, enhancing it with additional keyword information and confidence scores from AI services.

**Data Type Conversion and Cleaning:** 
Convert data types as necessary.
Remove rows with invalid values (NaN) in specific columns.
Address duplicate rows based on the 'photo_id'.

**Conversions Integration:** Merge the dataset with a conversions dataset, adding information related to conversion country and additional keywords.

**Colors Integration:** Enrich the dataset with data from a colors dataset, including hex values, RGB values, keywords, AI coverage, and AI score.

**Collections Integration:** Merge the dataset with collections data, introducing collection titles for each image.

