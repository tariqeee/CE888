# Stress Detection Project 
This project is focused on detecting stress using machine learning by analyzing physiological indicators, such as heart rate and skin conductance. The aim is to create an accurate and efficient model for predicting stress. To use this project [github](https://github.com/tariqeee/CE888/tree/main/CE888_Reassessment), please follow the steps outlined below. 


# Step-1
Download the complete project repository file and extract it. The zip file contains several files, including:

Main.tex: The LaTeX file used to generate the via [Overleaf](https://www.overleaf.com/) PDF report submitted on [FASER](https://faser.essex.ac.uk/Student).
Image folder: Contains all images and result outputs for the project.
content folder: 

Holds the stress detection dataset provided by  
[M.S. Ravi's 2021 GitHub repository, Stress-Detection-in-Nurses](https://github.com/CPHSLab/Stress-Detection-in-Nurses)
output.log: Lists the output of all LaTeX documents.
reference.bib: Contains all references used to create the report document.
stress_detection.ipynb: The main source code file.
README and LICENSE files.


# Step 2
Open the [stress_detection.ipynb](https://github.com/tariqeee/CE888/blob/main/CE888_Reassessment/stress_detection.ipynb) file in Jupyter Notebook. 


Be sure to install all necessary libraries by executing the following command in your [Jupyter Notebook](https://jupyter.org/)

!pip install library_name

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install all the libraries.

```bash
pip install package_name 

```
Replace 'library_name' with the specific library needed for the project. This may need to be done for multiple libraries.

## Usage
Additionally, verify the dataset location/path is accurate.
```python
pathdf = r'content/combined_lagEDA.csv' # Main Dataset Path 
aggtype = ['mean', 'std'] #group ways std
palette = 'flare'
seed = 49
test_size = 0.30 #This is %size of test of this project 
# df = pd.read_csv('content/combined_lagEDA.csv')

```


# Step 3
Click the "Run All" button in Jupyter Notebook to see the output. Enjoy exploring the stress detection project!


# Additional Information
This project encompasses various machine learning models, data preprocessing methods, and data visualization techniques. By utilizing the provided code, you can gain insight into the performance of different models and learn how to effectively manage stress using machine learning algorithms.

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

Please note that this project is intended for educational purposes and should not be used for commercial applications without permission. If you have any questions or need further assistance, please contact the repository owner.



## License
Copyright (c) [2023] [Md Tariqul Islam](https://www.tariqul4bd.com/)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.








