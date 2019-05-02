# 待ち行列（$M/M/1$型）
- ケンドールの記法
サービス要求発生頻度分布/サービス時間分布/サービス窓口数

- 待ち行列の公式
    - 平均到着率$\lambda$
    - 平均処理率$\mu$
    - 利用率$\rho = \lambda / \mu$
    - 平均サービス時間（平均処理時間）$t_s = 1 / \mu$
    $\rho = \lambda t_s$
    - 処理中も含めて停留しているジョブ数の平均$E_w = \displaystyle \frac{\rho}{1-\rho}$
    - 平均待ち時間$T_q = E_w t_s = \displaystyle \frac{\rho}{1-\rho} t_s$
    - 平均応答時間$T_w = T_q + t_s = \displaystyle \frac{1}{1-\rho} t_s$
