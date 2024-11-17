
# Fraud Detection Dataset

This dataset contains information about loan applicants, including demographic, financial, and behavioral data. 
It is primarily designed for fraud detection tasks, helping to identify cases where loans might be fraudulent.

## Dataset Summary

- **Total Rows**: 74,825
- **Total Columns**: 122
- **File Size**: ~69.6 MB

## Column Description

### Key Columns:
- **SK_ID_CURR**: Unique identifier for each record.
- **TARGET**: Target variable indicating whether a record is fraudulent (1) or non-fraudulent (0).

### Demographic Features:
- **NAME_CONTRACT_TYPE**: Type of loan contract (e.g., "Cash loans").
- **CODE_GENDER**: Gender of the applicant ('M' or 'F').
- **FLAG_OWN_CAR**: Whether the applicant owns a car ('Y' or 'N').
- **FLAG_OWN_REALTY**: Whether the applicant owns real estate ('Y' or 'N').

### Financial Features:
- **AMT_INCOME_TOTAL**: Total annual income of the applicant.
- **AMT_CREDIT**: Total credit amount applied for.
- **AMT_ANNUITY**: Annuity of the loan.

### Behavioral Features:
- **AMT_REQ_CREDIT_BUREAU_YEAR**: Number of credit inquiries made by the applicant in the last year.
- **FLAG_DOCUMENT_X**: Binary flags indicating if specific documents were provided.

## Usage Instructions

This dataset is suitable for machine learning tasks such as fraud detection, anomaly detection, and predictive modeling. 
You can preprocess the dataset using Python libraries like `pandas` and build models using frameworks such as `TensorFlow` or `scikit-learn`.

### Example Code to Load the Dataset:
```python
import pandas as pd

# Load the dataset
file_path = 'fraudcsv (1).csv'
data = pd.read_csv(file_path)

# Display dataset info
print(data.info())
```

## Licensing and Acknowledgements

Please ensure that you have permission to use this dataset in your projects. Properly credit the source if applicable.

## Contact

For questions or further information, contact the dataset creator or repository maintainer.
