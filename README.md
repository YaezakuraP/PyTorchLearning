# PyTorchLearning
PyTorchの学習で作成したコードを備忘録的にアップします．

## 1.SimplePerception_LogicGate.ipynb
### 概要
単純パーセプトロンで論理回路を学習するプログラム．
単純パーセプトロンがどのように線形分離問題を解くのかを視覚的に実感できます．

学習の際は，学習データセットのxとyの値を任意のものに変更してください．
また，モデルを多層パーセプトロンに書き換えることで，XOR回路も学習し，視覚化することができます．

![image](https://github.com/YaezakuraP/PyTorchLearning/assets/119919608/1e23bc7d-f1f9-4cbb-b8d0-cf394141fa5a)
and回路を学習して視覚化したところ．右上になると値が急激に大きくなることがわかる



### 必要なパッケージ
- torch
- matplotlib
- numpy
- tqdm
