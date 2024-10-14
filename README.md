# learngit
for git&amp;&amp;github's learn


Where the prefix 10t-10n indicates the values of hyperparameters ```time window``` and ```packets/sample``` that produced the best results in terms of F1 score on the validation set. The values of the other hyperparameters are reported in the ```csv``` file:

|Model|Samples|Accuracy|F1Score|Hyper-parameters|Validation Set|
|-----|-------|--------|-------|----------------|--------------|
|DOS2019-LUCID|677|0.9261|0.9256|"{'batch_size': 1024, 'dropout': 0.5, 'kernels': 64, 'learning_rate': 0.1, 'regularization': None}"|./sample-dataset/10t-10n-DOS2019-dataset-val.hdf5|
