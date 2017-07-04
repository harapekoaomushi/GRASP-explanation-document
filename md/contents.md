GRASPによるMCDF計算
---
# GRASPが計算してくれること(MCDF法)
## 対角化について（連成振動子を使った例）
## 水素様原子の電子軌道
## 近似について
### 変分法
### 摂動論
## Hartree Fock 法
### Born Oppenherimer 近似
### 平均場近似
### スレーター行列式
### Lagrange multiplier
## Hartree Fock法を使ってShroedinger方程式を解く
### SCF法
## Hartree Fock法より高精度な第一原理計算(post Hartree Fock)
### 多配置Hartree Fock（水素様原子の電子軌道を基底として対角化する）
### MCDF
### CI法
### その他の方法

# GRASPを使って基底状態を計算する
http://jolissrch-inter.tokai-sc.jaea.go.jp/pdfdata/JAERI-Data-Code-2000-003.pdf
## 使う基底を選ぶ（コンフィグレーション状態関数一覧の生成）（gencsl）
## 角運動量結合係数の計算 (genmcp)
generating the energy expression for H(DC) 
1996-parpia-grasp92-package.pdfに多少の記述あり。
## 原子特性値(ISO)の計算

## 初期の動径成分波動関数を計算（erwf）
## SCF計算（平均エネルギーレベル計算）（rscf92）
## CI計算（コンフィグレーション相関計算）（rci92）
## 結果から何が分かるだろうか
* Beは1s(2)2s(2)で閉殻に近い感じなのになぜ毒性を持つのか？
* Beはなぜモース硬度が高いのか？（六方最密充填構造を取りやすい）
## おかしな計算結果の例
## 収束しないときの対処法

# GRASPが具体的にどのように実装されているか

# GRASPを少し実践的な用途に使ってみる
## 励起状態を計算する
## 中空原子を計算する
