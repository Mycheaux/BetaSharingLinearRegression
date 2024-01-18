# FeatureCloud Beta Sharing Federated Linear Regression
In this federated linear regression app, only exact or inexact weighted slopes and intercepts (betas or coefficients) and the total exact or inexact weight of each client are shared. 
The config file expects the following structure: 
train: train.csv
test: test.csv
target_value: target_label
sep: ','
max_iter: 1
exact: True
output: output.csv

Keep the exact parameter = True for sharing the exact value of weighted slopes and intercepts. If exact = False, it will add a noise term in the weighting.   


## Note: there is another standard linear regression app that shares XT·X and XT·Y. 
other linear regression app: https://github.com/FeatureCloud/fc-linear-regression

### References
<a id="1">[1]</a> 
Matschinske, J., Späth, J., Nasirigerdeh, R., Torkzadehmahani, R., Hartebrodt, A., Orbán, B., Fejér, S., Zolotareva,
O., Bakhtiari, M., Bihari, B. and Bloice, M., 2021.
The FeatureCloud AI Store for Federated Learning in Biomedicine and Beyond. arXiv preprint arXiv:2105.05734.
