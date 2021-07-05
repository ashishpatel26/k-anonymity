# Differential Privacy using K-Anonymity
## To-do list
- [x] Run 6 methods on 6 datasets 
- [x] Add L-diversity, Classic Mondrian (no hierarchies), Datafly algorithm
- [x] Make NCP loss a separated module
- [ ] Implement classification models (basic classifier, clustering)
- [ ] Run experiment on 6 datasets x 6 methods x 2 ML models
- [ ] Finish report
- [ ] (Improvement) T-closeness method, Igconito Algorithm
- [ ] (Optional) Simple Deanonymize Attack


## Reports:
Report edit link:
[![report](https://img.shields.io/badge/latex-%23008080.svg?style=for-the-badge&logo=latex&logoColor=white)](https://www.overleaf.com/4786864492ypscdyrmpwzd)


## Executing:
To anonymize dataset, run:
```
python anonymize.py --method=<model_type> --k=<k-anonymity> --dataset=<dataset_name>
```
- **model_type**: [mondrian | classic_mondrian | mondrian_ldiv | topdown | cluster | datafly]
- **dataset_name**: [adult | cahousing | cmc | mgm | informs | italia]



## References:
- Basic Mondrian, Top-Down Greedy, Cluster-based (https://github.com/fhstp/k-AnonML)
- L-Diversity (https://github.com/Nuclearstar/K-Anonymity, https://github.com/qiyuangong/Mondrian_L_Diversity)
- Classic Mondrian (https://github.com/qiyuangong/Mondrian)
- Datafly Algorithm (https://github.com/nazilkbahar/python-datafly)
- Normalized Certainty Penalty from [Utility-Based Anonymization for Privacy Preservation with
Less Information Loss](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.450.6140&rep=rep1&type=pdf)
- [Privacy in a Mobile-Social World](https://courses.cs.duke.edu//fall12/compsci590.3/slides/lec3.pdf)
- Code and idea based on [k-Anonymity in Practice: How Generalisation and Suppression Affect Machine Learning Classifiers](https://arxiv.org/abs/2102.04763)
