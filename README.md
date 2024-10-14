# learngit
for git&amp;&amp;github's learn


其中前缀 10t-10n 表示在**Validation-Set**上产生F1分数最佳结果的hyper-parameter的时间窗口和package/sample的值。其他超参数的值在相应的csv文件中.

|Model|Samples|Accuracy|F1Score|Hyper-parameters|Validation Set|
|-----|-------|--------|-------|----------------|--------------|
|DOS2019-FLAD|677|0.9261|0.9256|"{'batch_size': 1024, 'dropout': 0.5, 'kernels': 64, 'learning_rate': 0.1, 'regularization': None}"|./sample-dataset/10t-10n-DOS2019-dataset-val.hdf5|
