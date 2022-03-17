# Processing of missing data by neural networks


This is the training code for our paper "*Processing of missing data by neural networks*".

In order to repeat the experiments from column "*our*":

 in Table 3 (except the first row):
    ```bash
        python3 rbfn.py --data_dir ./data_rbfn/heart/ --learning_rate 0.25 --batch_size 64 --training_epochs 800 --n_hidden_1 30 --n_distribution 3
    ```

