# Install
```
pip install surprise
pip install lightfm
```

# Models
## Requirement
* UCF-s
* UCF-p
* ICF-s
* ICF-p
* MF
* FM
* BPR-MF
* BPR-FM
* GBDT+LR
* XGB+LR
* FNN
* IPNN
* OPNN
* PIN
* CCPM
* NeuMF
* WD
* DeepCross
* NFM
* DeepFM

## 5 choose 3
* AFM
* xDeepFM
* DIN

# Evaluation Metrics
1. RMSE (real-valued)
2. Recall@10(binary)
3. NDCG@10(binary)

# Data Filtering
remove users whose interactions \< 3 .

# Data Splitting
* 5-Fold CV
* train: 70%
* validate: 10% 
* test: 20%