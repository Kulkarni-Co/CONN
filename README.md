# This Repository Houses the Code for our Capstone Thesis Titled : "A New Framework with Convoluted Oscillatory Neural Network (CONN) for Efficient Object-Based Land Use and Land Cover Classification on Remote Sensing Images" 

Owners:
* [Shlok Chetan Kulkarni](https://github.com/Sckarge)
* [Chirag Jitendra Chandnani](https://github.com/chiragchandnani10)

![Methodology](https://github.com/user-attachments/assets/71a1b0ef-a1f2-4d98-a7c9-d6a9801b049e)



##  Repository Structure

- **`Data Collection/`** – Contains code for GEE Data Extraction
  - `GEE_Extraction_Script.js` – GEE Code for Dataset Extraction
- **`Preprocessing/`**
  - `Data_preprocessing.ipynb` – Implementation of the CONN architecture
- **`Data/`** – Dataset 
- **`models/`** – CONN model architecture and ML along with training scripts
  - `conn_model.ipynb` – Implementation of the CONN architecture
  - `train.ipynb` – Training and validation script

- **`outputs/`** – Stores final results and visualizations
  - `Graphing.ipynb` – Graph the required Train and Test Graphs
  - `Plot_Logs.ipynb` – Plots for ML Codes

- **`README.md`** – Project overview, installation guide, and, documentation

---
### Abstract  
Rigorous urbanization leads to unprecedented climate change. Pune area in India has witnessed recent flash floods and landslides due to unplanned rapid urbanization. It therefore becomes vital to manage and analyse man-made impact on the environment through effective Land Use Land Cover classification (LULC). Accurate LULC classification allows for better planning and effective allocation of resources in urban development. Remote sensing images provide surface reflectance data that are used for accurate mapping and monitoring of land cover. Convolution Neural Networks (CNN) trained with Relu are conventionally used in classifying different land types. However, every neuron has a single hyperplane decision boundary which restricts the model’s capability to generalize. Oscillatory activation functions with their periodic nature have demonstrated that a single neuron can have multiple hyperplanes in the decision boundary which helps in better generalization and accuracy. This study proposes a novel framework with Convoluted Oscillatory Neural Networks (CONN) that synergistically combines the periodic, non-monotonic nature of oscillatory activation functions with the deep convoluted architecture of CNNs to accurately map LULC. Results carried out on LANDSAT-8 surface reflectance images for the Pune area indicate that CONN with Decaying Sine Unit achieved an overall train accuracy of 99.999%, test accuracy of 95.979% and outperforms conventional CNN models in precision, recall and User’s Accuracy. A thorough ablation study was conducted with various subsets of the feature set to test the performance of the selected models in the absence of data.


<div align="center">
<img src="https://github.com/user-attachments/assets/648e2da6-83bb-4cae-8970-19eefebc3320" width="700" height="700">
</div>



