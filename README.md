# Gender Determination Using Deep Learning

## Project Overview
This project explores **gender classification** using **deep learning techniques** applied to eye images. The classification is based on a **convolutional neural network (CNN) model**, specifically **VGG-19 architecture**, trained to differentiate between male and female eye regions.

## Features
- **Deep Learning Model:** Uses **VGG-19** CNN for gender classification.
- **Custom Dataset:** Eye images extracted from larger face datasets.
- **Training & Testing Pipeline:** Dataset split into **train** and **test** sets.
- **Performance Analysis:** Accuracy, loss, and results visualization.
- **GitHub Pages Documentation:** Hosted in the `docs/` folder for easy access.

## Repository Structure
```
/ (root)
├── Code/
│   └── GenderDetermination_Vgg19Model.ipynb   # Jupyter Notebook
├── docs/
│   ├── images/
│   │   ├── HowData_Looks.png
│   │   ├── OurCustom_Methodology.png
│   │   ├── Results.png
│   │   ├── Vgg19_architecture.png
│   ├── index.html  # GitHub Pages website
│   ├── style.css   # CSS Styling for the website
├── eye_gender_data/
│   ├── train/      # Training Images
│   ├── test/       # Testing Images
│   ├── sample_submission.csv
│   ├── Testing_new.csv
│   ├── Testing_set.csv
│   ├── Training_set.csv
├── Report/
│   └── Deep Learning for Computer Vision.pdf  # Project Report
├── README.md  # Project Documentation
```

## Dataset
- The dataset contains **eye images** extracted from face datasets.
- It is stored in `eye_gender_data/`.
- CSV files provide mappings for training and testing sets.

## Installation & Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/YOUR-USERNAME/GenderDetermination_DeepLearning.git
   ```
2. Install dependencies (Python & TensorFlow required):
   ```sh
   pip install -r requirements.txt
   ```
3. Open and run the Jupyter Notebook:
   ```sh
   jupyter notebook Code/GenderDetermination_Vgg19Model.ipynb
   ```

## Results
- Model trained on the dataset achieved **97% accuracy**.
- Loss and accuracy graphs provided in the **Results.png**.

## GitHub Pages
For documentation, visit: https://nabeeljadoon.github.io/GenderDetermination_DeepLearning/

Please cite our work as:
@misc{Jadoon2025GenderDL,
  author = {Jadoon, Nabeel Ahmad Khan and Dharmasena, P. H. Amindu and Wongpromkal, Nutthapong},
  title = {Gender Determination Using Deep Learning: Classification of Eye Morphometry Using VGG-19},
  year = {2025},
  url = {https://github.com/YOUR-USERNAME/GenderDetermination_DeepLearning},
  note = {GitHub Repository}
}


## License
This project is open-source and licensed under **MIT License**.


