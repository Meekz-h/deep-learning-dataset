# Task 3 
## Requirements
Python 3.11–3.12 recommended, Jupyter, TensorFlow, NumPy, pandas, matplotlib, scikit-learn. Install with python -m pip install -r requirements_task3_revised.txt.
## Dataset
Run Task 2 preprocessing first. Place prepared_cifar10.npz in prepared_data/ or the notebook directory. The actual folder preprocessing script stores lowercase keys: x_train, y_train, x_val, y_val, x_test, test_ids, class_names. This notebook also supports uppercase X aliases. Data is already normalized to [0,1]; the notebook does not normalize it twice. The original test data is unlabeled; sampleSubmission.csv labels are placeholders.
## Run
Open task3.ipynb in Jupyter or VS Code, select a TensorFlow-capable kernel, and run all cells. The default includes four random-search tuning trials, which can take substantial time. Set RUN_TUNING = False for a faster baseline run. Save the executed notebook.
## Outputs
task3_outputs/ contains model summaries, layer breakdown, learning curves, validation metrics, confusion matrix, trained .keras models, tuning results, and test_predictions.csv.
## Export HTML / PDF
After executing and saving the notebook, use jupyter nbconvert --to html task3.ipynb --output task3.html. For PDF, print the HTML to PDF or use nbconvert with a configured PDF engine. Do not export an unexecuted notebook as evidence of results.

