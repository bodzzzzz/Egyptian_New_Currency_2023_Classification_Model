# Egyptian New Currency 2023 Classification Model

This repository contains a Jupyter Notebook implementation of a machine learning classification model for detecting and identifying Egyptian banknotes introduced in 2023. The project covers the full pipeline from data acquisition and preprocessing to model development, evaluation, and predictions. It aims to provide a robust solution for currency recognition using image data.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Model Details](#model-details)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## Project Overview

Since the release of new Egyptian banknotes in 2023, automated recognition systems and financial institutions face the challenge of updating their models and hardware to identify new currency designs. This project tackles the problem by training a machine learning model to classify images of the new banknotes—automating detection of denomination and authenticity.

**Objectives:**

- Classify and recognize denominations of Egyptian banknotes (2023 Edition).
- Provide a reproducible and extensible workflow in Jupyter Notebook format.
- Enable further development or integration with larger currency detection systems.

---

## Dataset

The project assumes access to a dataset of Egyptian banknote images from 2023, properly labeled with denomination and optionally authenticity. If you have your own dataset, organize it as follows:

```
data/
├── 5_EGP/
│   ├── img1.jpg
│   ├── img2.jpg
│   └── ...
├── 10_EGP/
│   ├── img1.jpg
│   ├── img2.jpg
│   └── ...
└── ...
```

If a dataset source is included in the notebook, instructions for download/acquisition will be provided inside.

---

## Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/bodzzzzz/Egyptian_New_Currency_2023_Classification_Model.git
   cd Egyptian_New_Currency_2023_Classification_Model
   ```

2. **Create and activate a Python virtual environment (recommended)**
   
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install required packages**

   Open `requirements.txt` (if provided), or use the following defaults for most image classification notebooks:
   
   ```bash
   pip install -r requirements.txt
   ```

   _OR manually:_

   ```bash
   pip install numpy pandas matplotlib scikit-learn tensorflow opencv-python notebook
   ```

---

## Usage

1. **Prepare the dataset:**
   - Place your image data in a `data/` directory, following the structure described above.

2. **Open the Jupyter Notebook:**

   ```bash
   jupyter notebook Egyptian_New_Currency_2023_Classification_Model.ipynb
   ```

3. **Run notebook cells sequentially:**
   - Read cell instructions for any required setup or configuration.
   - Train the model and visualize results.
   - Optionally use prediction functions for new banknote images.

---

## Project Structure

```
Egyptian_New_Currency_2023_Classification_Model/
├── Egyptian_New_Currency_2023_Classification_Model.ipynb  # Main notebook for workflow
├── data/                                                  # Banknote images (user-provided)
├── requirements.txt                                       # Dependencies (if provided)
├── README.md                                              # Project documentation
└── ...                                                    # Additional scripts/files as needed
```

---

## Model Details

- **Type:** Image Classification (Deep Learning or ML—see notebook)
- **Input:** RGB images of Egyptian banknotes (properly oriented, as per dataset)
- **Preprocessing:** Standardization, resizing, augmentation (as applicable)
- **Architecture:** Typically CNN-based (e.g., TensorFlow/Keras, PyTorch), details described in the notebook
- **Training Metrics:** Accuracy, Loss, Confusion Matrix
- **Evaluation:** Validation and (if labeled) test sets

---

## Results

- Training and validation history
- Performance metrics for each denomination
- Sample predictions with image outputs
- Error analysis (misclassifications, confusion matrix)

See the notebook or generated reports for details.

---

## Contributing

Feel free to open issues or submit pull requests for:
- Additional banknote data (other denominations, years)
- Improved model architectures
- Integration with hardware
- Documentation improvements

## License

This project is provided under the [MIT License](LICENSE). See the LICENSE file for details.

---

## Contact

For questions or collaboration:

- GitHub: [bodzzzzz](https://github.com/bodzzzzz)

---

**Enjoy exploring and applying the model!**
