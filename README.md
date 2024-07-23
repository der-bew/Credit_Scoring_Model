# Credit Scoring Model

This repository contains the implementation of a credit scoring model, including data preprocessing, exploratory data analysis (EDA), feature engineering, and model building. The project is structured to ensure modularity and clarity, with specific folders and scripts dedicated to different stages of the workflow.

## Folder Structure
```
Credit_Scoring_Model/
├── .dvc/
├── data/
├── notebooks/
│ ├── EDA.ipynb
│ ├── feature_engineering_and_model_building.ipynb
├── src/
│ ├── handler.py
│ ├── visualizer.py
├── tests/
├── .dvcignore
├── .gitignore
├── LICENSE
├── README.md
├── requirements.txt
```

### Folders and Files

- `.dvc/`:
  - Contains files related to Data Version Control (DVC) for managing data files.
  
- `data/`:
  - Directory where raw and processed data files are stored.

- `notebooks/`:
  - `EDA.ipynb`: Jupyter Notebook for exploratory data analysis.
  - `feature_engineering_and_model_building.ipynb`: Jupyter Notebook for feature engineering and model building.

- `src/`:
  - `handler.py`: Script for handling data loading, preprocessing, and transformations.
  - `visualizer.py`: Script for generating visualizations.

- `tests/`:
  - Directory for unit tests to ensure the correctness of the code.

- `.dvcignore`:
  - Specifies which files and directories to ignore in DVC tracking.

- `.gitignore`:
  - Specifies which files and directories to ignore in Git tracking.

- `LICENSE`:
  - License file for the project.

- `README.md`:
  - This file, providing an overview and instructions for the project.

- `requirements.txt`:
  - List of Python dependencies required for the project.

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Python 3.8 or higher
- [DVC](https://dvc.org/doc/install) for data version control
- [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) for version control

### Installation

1. Clone the repository:
```
git clone https://github.com/der-bew/Credit_Scoring_Model.git
cd Credit_Scoring_Model
```
2. Install the required Python packages
```
pip install -r requirements.txt
```
### Usage

  1. Data Preparation:
        - Place your raw data files in the data/ directory.
        - Use DVC to manage your data versions.

  2. Exploratory Data Analysis:
        - Open notebooks/EDA.ipynb in Jupyter Notebook to perform EDA on the dataset.

  3. Feature Engineering and Model Building:
        - Open notebooks/feature_engineering_and_model_building.ipynb to perform feature engineering and build the credit scoring model.

  4. Running Scripts:
       - Use the scripts in the src/ directory for data handling and visualization.

  5. Testing:
       - Run unit tests located in the tests/ directory to ensure code correctness.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure that your code adheres to the existing style and includes relevant tests.
## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/der-bew/Credit_Scoring_Model/edit/main/LICENSE) file for details.

## Acknowledgements

  - This project uses various open-source libraries and tools. We thank their respective authors and maintainers.

For any questions or issues, please open an issue in this repository.

