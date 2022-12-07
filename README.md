# Time-Series-Analysis
CNN, LSTM and RandomForest models are implemented on Jupyter environment. Download dataset and relevant Jupyter Notebook and run the code. 

For StemGNN; 
1. Download repo
2. open up terminal within StemGNN folder.
3. Run the following command in terminal "pip install -r requirement.txt" Python version should be lower than 3.9
4. Run the utils.ipynb in oder to preprocess hal.xlsx within dataset folder.
5. Run "python main.py --train True --evaluate True --dataset hal --epoch 100 --window_size 28 --horizon 5 --norm_method z_score --train_length 9  --test_length 1"

You might change --horizon argument to try for different future timestamps at your please. We have tried 5 days and 10 days in the paper.
