# learngit
for git&amp;&amp;github's learn


其中前缀 10t-10n 表示在**Validation-Set**上产生F1分数最佳结果的hyper-parameter的时间窗口和package/sample的值。其他超参数的值在相应的csv文件中.

|Model|Samples|Accuracy|F1Score|Hyper-parameters|Validation Set|
|-----|-------|--------|-------|----------------|--------------|
|DOS2019-FLAD|42800|_**0.9421**_|_**0.9387**_|"{'batch_size': 1024, 'dropout': 0.5, 'kernels': 64, 'learning_rate': 0.05, 'regularization': Early-Stopping}"|./sample-dataset/10t-10n-DOS2019-dataset-val.hdf5|


|Total training time(second)|          
|---------------------------|
|1738|
