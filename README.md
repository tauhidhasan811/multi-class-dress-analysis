**Repository Description**  
- Multi‑class dress attribute analysis using deep learning.  
- Includes data preprocessing, visualization, and several model architectures.  
- CNN baseline, MobileNetV2, and RegNet‑B0 transformer‑based multi‑task classifiers.  
- Each notebook handles a distinct stage: cleaning, loading, model building, and evaluation.  
- Designed for multi‑output classification with six attribute groups.  
- Uses TensorFlow/Keras, OpenCV, NumPy, Matplotlib, and Seaborn.  
- Suitable for research on fashion image tagging and attribute prediction.  
- Large notebook files are managed with Git LFS.  
- Repository URL: https://github.com/tauhidhasan811/multi-class-dress-analysis  

**Run Instructions**  
a. Clone the repository: 
   ```bash
   git clone https://github.com/tauhidhasan811/multi-class-dress-analysis.git
   ``` 
b. Create a virtual environment: 
   ```bash
   py -3.11 -m venv venv` *(replace 3.11 with your Python version)*
   ```
c. Activate the virtual environment:  
   - Windows:
        ```bash
        venv\Scripts\activate```
   - Unix/Mac:
       ```bash
        source venv/bin/activate
        ```   
d. Install dependencies: 
   ```bash
   pip install -r requirements.txt
```  
e. Execute the primary notebooks (no .py entry point):  
   - `jupyter notebook 1 preprocessing.ipynb`  
   - `jupyter notebook 2 data_visulization.ipynb`  
   - `jupyter notebook 3 model (CNN).ipynb`  
   - `jupyter notebook 3.1 Transformer(MobileNetV2).ipynb`  
   - `jupyter notebook 3.2 Transformer(RegNetB0) copy.ipynb`  

**Folder Structure**  
```
multi-class-dress-analysis
|-- .gitattributes
|-- .gitignore
|-- 1 preprocessing.ipynb
|-- 2 data_visulization.ipynb
|-- 3 model (CNN).ipynb
|-- 3.1 Transformer(MobileNetV2).ipynb
|-- 3.2 Transformer(RegNetB0) copy.ipynb
```  

**File Descriptions**  
- **.gitattributes**: Configures Git LFS for Jupyter notebooks and disables text conversion.  
- **.gitignore**: Excludes the virtual environment and NumPy binary files from version control.  
- **1 preprocessing.ipynb**: Sets up image preprocessing with OpenCV and NumPy; demonstrates basic text cleaning.  
- **2 data_visulization.ipynb**: Loads saved NumPy arrays of training/validation images and visualizes sample data.  
- **3 model (CNN).ipynb**: Builds, trains, and evaluates a multi‑output CNN using TensorFlow/Keras.  
- **3.1 Transformer(MobileNetV2).ipynb**: Constructs a multi‑task classifier with a frozen MobileNetV2 backbone and separate dense heads.  
- **3.2 Transformer(RegNetB0) copy.ipynb**: Implements a similar multi‑task model using a RegNet‑B0 backbone, including optional transformer blocks.  
