# Human Emotion Recognition System

## Overview
This project involves training a deep learning model for facial emotion detection using the FER2013 dataset. Developed as part of the Statistical Machine Learning course during my Master’s program, this project focuses on detecting and classifying human emotions from facial images.

## Table of Contents
1. [Overview](#overview)
2. [Project Structure](#project-structure)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Tech Stack](#tech-stack)
6. [Dataset](#dataset)
7. [Contributing](#contributing)
8. [License](#license)
9. [Contact](#contact)

## Project Structure
```
Human_Emotion_Recognition_System/
│
├── SML_Project.ipynb         # Jupyter Notebook with code and analysis
├── requirements.txt          # List of dependencies
├── README.md                 # Project documentation
└── venv/                     # Virtual environment (optional)
```

## Installation

To set up the project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Pratik8399/Human_Emotion_Recognition_System.git
   cd Human_Emotion_Recognition_System
   ```

2. **Create a virtual environment** (optional but recommended):
   ```bash
   python -m venv venv
   ```

3. **Activate the virtual environment**:
   - **Windows**:
     ```bash
     venv\Scripts\activate
     ```
   - **macOS/Linux**:
     ```bash
     source venv/bin/activate
     ```

4. **Install the required packages**:
   ```bash
   pip install -r requirements.txt
   ```

5. **Launch the Jupyter Notebook**:
   ```bash
   jupyter notebook SML_Project.ipynb
   ```

## Usage

1. Follow the steps in the Jupyter Notebook (`SML_Project.ipynb`) to:
   - Load and preprocess the FER2013 dataset.
   - Train the deep learning model for emotion recognition.
   - Evaluate the model's performance using various metrics.

2. Customize the model and parameters as needed, and retrain to optimize performance.

## Tech Stack

- **Python**: Programming language used for model development.
- **Jupyter Notebook**: For documenting and running code interactively.
- **TensorFlow & Keras**: Deep learning libraries for building neural networks.
- **Pandas & NumPy**: Data manipulation and analysis.
- **Matplotlib & Seaborn**: Data visualization.

## Dataset

- **Dataset Name**: FER2013
- **Description**: The FER2013 dataset contains facial images labeled with different emotions like happy, sad, neutral, etc. It is used to train a convolutional neural network to recognize various facial expressions.
- **Source**: [FER2013 Dataset](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge)

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add a new feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or suggestions, feel free to reach out:

- **Name**: Pratik Dnyaneshwar Kale
- **Email**: [kalepratik8399@gmail.com](mailto:kalepratik8399@gmail.com)
- **LinkedIn**: [linkedin.com/in/pratik-kale32](https://linkedin.com/in/pratik-kale32)
- **GitHub**: [Pratik8399](https://github.com/Pratik8399)

---
