
# Utilizing Hyperspectral Non-Image Data to Identify Materials in Ancient Structures  

## 📌 Project Overview  
This research project focuses on the **noninvasive identification of materials** used in ancient structures through **hyperspectral non-imaging data analysis**. Traditional methods of material identification often involve invasive sampling, which can damage historical sites. This project leverages **machine learning** and **spectral signature analysis** to accurately classify materials used in ancient architecture.  

## 🏛️ Research Context  
Ancient structures in **Chhatrapati Sambhajinagar** were constructed using materials such as **limestone** and natural additives like **bel-fruit (Aegle marmelos), jaggery (Saccharum officinarum), Ambada vegetable (Hibiscus sabdariffa) and udid dal (Vigna mungo)**. These materials played a significant role in enhancing the durability and strength of these constructions. This study aims to:  
- Build a **spectral library** for ancient materials.  
- Apply **hyperspectral data processing** techniques.  
- Develop a **machine learning model** for material classification.  

## 🔬 Methodology  
1. **Data Collection:**  
   - Spectral data obtained using **ASD FieldSpec 4 Spectroradiometer**.  
   - Measurements processed using **RS³ and ViewSpec Pro software**.  

2. **Feature Extraction & Preprocessing:**  
   - First derivative analysis of reflectance spectra.  
   - Selection of key wavelengths for material classification.  

3. **Machine Learning Model:**  
   - **Support Vector Machine (SVM)** trained on hyperspectral data.  
   - Achieved an **accuracy of 93.60%** in material classification.  

4. **Results & Discussion:**  
   - Ancient **limestone** was the most dominant material (53.6%).  
   - The **spectral library** developed serves as a valuable resource for future studies.  

## 📊 Tools & Technologies Used  
- **ASD FieldSpec 4** (Hyperspectral Spectroradiometer)  
- **RS³ Software** (Spectral Data Collection)  
- **ViewSpec Pro** (Spectral Analysis)  
- **Python & Scikit-Learn** (Machine Learning Model)  
- **ENVI Software** (Spectral Library Development)  

## 🌍 Impact & Applications  
- **Archaeological Conservation**: Non-destructive material identification for heritage sites.  
- **Geological & Environmental Studies**: Spectral analysis for natural material classification.  
- **Historical Research**: Understanding ancient construction techniques and material use.  

## 📂 Repository Structure  
```
📂 datasets/            # Hyperspectral data files  
📂 models/              # Trained ML models  
📂 doc/                 # Documentations  
📂 results/             # Analysis, plots, and spectral library  
📜 README.md            # Project Overview (this file)  
```  

## 📢 Acknowledgment  
This project was completed as part of the **M.Sc. Artificial Intelligence** department of compueter science & Information Technology at **Dr. Babasaheb Ambedkar Marathwada University** under the guidance of **Prof. Dr. Sachin N. Deshmukh**. Special thanks to the **MultiSpectral Research Lab** for providing the necessary resources.  

🔗 **For more details, refer to the full research documentation in the repository.**  
