# Neutralizing Gender Bias in Word Embedding with Latent Disentanglement and Counterfactual Generation

## Environments
```shell script
python == 3.5.2
tensorflow-gpu == 1.15.0
gensim == 3.7.1
sklearn == 0.20.1
scipy == 1.2.1
```
## Run
Simply Run with the following script:```python3 main.py --align_type 'xxx'```
* CF-Debias -> --align_type 'none'
* CF-Debias -> --align_type 'linear'
* CF-Debias -> --align_type 'kernel'

## Results
For evaluation with Sembias Analogy Test, run bash file ```run_evaluation.sh```

the results from sembias_evaluation will be saved in the logs folder.







