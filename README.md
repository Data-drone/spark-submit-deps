# Packaging for spark submitting python

Based on: https://bytes.grubhub.com/managing-dependencies-and-artifacts-in-pyspark-7641aa89ddb7

## Limitations

Issues with complex libs like:
- numpy
- scipy
- pandas
- scikit-learn
- xgboost

compiled components won't be shipped across properly