# DTA: Development Trend-based Evaluating of OSS Repository Activity

## Usage Instructions

1. Install Python 3.8:
   It is recommended to use Anaconda to create a virtual environment. Install the required packages with the following command:

```python
pip install -r requirements.txt
```

2. Train and Evaluate the Model:
   We provide scripts necessary for training the data. You can run the test script using the following command. This script will train and test the dataset located at:
   dataset/language/Detail_repo/TypeScript/vscode_all_roll_ewma_span28_normalize.csv

```bash
bash ./scripts/long_term_forecast/test.sh
```

3. Results Output:

Results Output:

- The predicted results will be saved in the results folder.
- Visualization results will be stored in the test_results folder.
- Test error metrics will be recorded in result_long_term_forecast.txt.

4. Statistical Records:
   The **workresult** folder contains statistical summaries of experimental results, such as test errors, scores, and average slopes.

