# pybtm

ツイートなど短文書に特化したトピックモデルの一種であるBiterm topic modelの実装です．  
この実装ではStochastic Collapsed Variational Bayes Zeroと呼ばれる推論アルゴリズムをミニバッチ学習に対応させており，従来のGibbs samplingと比較して効率的にトピックを学習できます．


## QuickStart
- run pybtm
```
sh run.sh
```

## Requirement
- numpy
- scipy

## Useful tool
- [pretweet.py](https://gist.github.com/FooQoo/c028e522d99b3209f58d035a89c802ee)
    - ツイートテキストに前処理を行うスクリプト

## Reference
- [Stochastic collapsed variational bayesian inference for biterm
topic model](https://ieeexplore.ieee.org/document/7727629)
    - IJCNN
    - Awaya et al.