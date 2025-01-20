# 正誤表

| 該当ページ |  該当箇所 |  誤  |  正  | 補足 | 対応 | 
| ---- | ---- | ---- | ---- | ---- | ---- |
| p.29 | 15 行目 | $v \in v$ | $v \in V$ | |  |
| p.45 | 問題 2.1 の出力 | $v \in U$ | $v \in V_\text{U}$ | |  |
| p.52 | 式 (2.37) | $\boldsymbol{W} = \boldsymbol{V} \text{Diag}([\lambda_1, \ldots, \lambda_n]) \boldsymbol{V}^\top$| $(\boldsymbol{D} + \boldsymbol{W}) = \boldsymbol{V} \text{Diag}([\lambda_1, \ldots, \lambda_n]) \boldsymbol{V}^\top$ | |  |
| p.55 | アルゴリズム 2.2 手順 2  | $\boldsymbol{Z} = [\sqrt{\lambda_1} \boldsymbol{v}_1, \sqrt{\lambda_2} \boldsymbol{v}_2, \ldots, \sqrt{\lambda_d} \boldsymbol{v}_d]^\top$ | $\boldsymbol{Z} = [\sqrt{\lambda_1} \boldsymbol{v}_1, \sqrt{\lambda_2} \boldsymbol{v}_2, \ldots, \sqrt{\lambda_d} \boldsymbol{v}_d]$ | | 3 刷で修正  |
| p.70 | 下から 9 行目 | ユーザー $u$ の中間表現 $\boldsymbol{h}_v^{(2)}$ | ユーザー $u$ の中間表現 $\boldsymbol{h}_u^{(2)}$ | |  |
| p.70 | 下から 7 行目 | 第 2 層の表現 $\boldsymbol{h}_v^{(2)}$ | 第 2 層の表現 $\boldsymbol{h}_{v'}^{(2)}$ | |  |
| p.75, 76, 79, 86, 87, 124, 134, 135, 192, 222, 224, 228, 231, 236, 238 | 式 (3.8), (3.23), (3.24), (3.25), (3.38), (3.39), (5.1), (5.3), (5.20), (5,21), (5.25), (6.99), (7.3), (7.4), (7.12), (7.13), (7.19), (7.32), (7.33), (7.34), (7.56), (7.61), (7.63), (7.64), (7.65), アルゴリズム 3.2 | $\boldsymbol{W}$ | $\boldsymbol{W}^\top$ | 特徴行列や中間表現行列に重み行列を右から掛けるときには転置が必要です。※1 |  |
| p.76, p.130| 式 (3.14) と直下の説明、式 (5.18) と直下の説明 | Concat がセミコロン区切り | Concat はカンマ区切り | 他の箇所と合わせるため |  |
| p.78 | 式 (3.16) | $(1 - \boldsymbol{z}_v^{(l + 1)})$ | $(\boldsymbol{1} - \boldsymbol{z}_v^{(l + 1)})$ | |  |
| p.92, 317 | 1 行目, 索引 | Heterogeneous graph Attension Network | Heterogeneous graph Attention Network | | 5 刷で修正  |
| p.105 | 図 4.2 u の特徴 | $(0, 0)$ | $(0, 2)$ | |  |
| p.105 | 図 4.2 v の特徴 | $(0, 0)$ | $(2, 0)$ | |  |
| p.109 | 式 (4.16) | $j\colon (u, i) \not \in \mathcal{P}$ | $j\colon (u, j) \not \in \mathcal{P}$ | |  |
| p.129, p.131, p.133, p.137 | アルゴリズム 5.1 の 10 行目、アルゴリズム 5.2 の 11 行目、アルゴリズム 5.3 の 7 行目、アルゴリズム 5.4 の 9 行目 | $(\forall v \in V)$ | トル | |  |
| p.137 | アルゴリズム 5.4 の 3 行目 | | 行を削除 | |  |
| p.137 | アルゴリズム 5.4 の 5 行目 | $u_K$ | $u_{K_l}$ | |  |
| p.158 | 式 (6.31) | $(j = 0, 1, \ldots, k-1)$ | $(j = 1, \ldots, k-1)$ | |  |
| p.182 | 下から 6 行目 | $\boldsymbol{L}^{i+1}$ | $\boldsymbol{L}^{l+1}$ | |  |
| p.190 | 1 行目 | 各行が 1 | 各行の要素の和が 1 | |  |
| p.191 | 式 (6.93) | $\mathcal{E}$ | $E$ | |  |
| p.192 | 式 (6.95) 直後 | $(\theta_1, \theta_2)$ | $(\theta_0, \theta_1)$ | |  |
| p.212 | 式 (6.133) | $\boldsymbol{f}_1 \le \boldsymbol{f}_2 \le \ldots \le \boldsymbol{f}_n$ | $\frac{\boldsymbol{f}_1}{\sqrt{\text{deg}(1)}} \le \frac{\boldsymbol{f}_2}{\sqrt{\text{deg}(2)}} \le \ldots \le \frac{\boldsymbol{f}_n}{\sqrt{\text{deg}(n)}}$ | |  |
| p.222 | 定理 7.1 | $\boldsymbol{W} \in \mathbb{R}^{d \times d_{\text{out}}}$ | $\boldsymbol{W} \in \mathbb{R}^{d_{\text{out}} \times d}$ | ※1 との整合性を取るため |  |
| p.223 | 式 (7.9) 下から 2 行目と 3 行目 | $v \in E$ | $v \in V$ | |  |
| p.224 | 式 (7.11) の下 2 行目 | $(\boldsymbol{X} \boldsymbol{W}) \in \mathbb{R}^{n \times d}$ | $(\boldsymbol{X} \boldsymbol{W}^\top) \in \mathbb{R}^{n \times d_\text{out}}$ | |  |
| p.224 | 式 (7.13) $\stackrel{\text{(a)}}{=}$ の直後 | $\alpha_{i0}$ | $\alpha_{i1}$ | |  |
| p.225 | 定理 7.1 の証明下から 3 行目 | 特徴ベクトル $\boldsymbol{X} \in \mathbb{R}^{n \times d}$ | $(\boldsymbol{X} \boldsymbol{W}^\top) \in \mathbb{R}^{n \times d_\text{out}}$ | |  |
| p.230 | 下から 2 行目 | $\|1 - \lambda_j\| < r$ | $\|1 - \lambda_j\| \le r$ | |  |
| p.232 | 式 (7.42) の直下 | 式 (7.31), (7.32), (7.42) より | 式 (7.31), (7.34), (7.42) より | |  |
| p.239 | 下から 3 行目 | $\boldsymbol{W} \in \mathbb{R}^{n \times d_1}$ | $\boldsymbol{W} \in \mathbb{R}^{d_1 \times n}$ | ※1 との整合性を取るため |  |
| p.239 | 下から 2 行目 | $\boldsymbol{W}_i$ | $\boldsymbol{W}_{:,i}$ | ※1 との整合性を取るため |  |
| p.263 | 8.2.3 節 1 行目 | 定理 8.6 より | 定理 8.7 より | |  |
| p.270 | 式 (8.62) | $f(\pi \cdot x) = f(x) ~(\forall x \in \mathbb{R})$ | $f(\pi \cdot \boldsymbol{X}) = f(\boldsymbol{X}) ~(\forall \boldsymbol{X} \in \mathbb{R}^{n^k})$ | |  |
| p.272 | 2 行目 | $\boldsymbol{W} \in \mathbb{R}^{n^k}$ | $\boldsymbol{W}^f \in \mathbb{R}^{n^{l + k}}$ | |  |
| p.275 | 式 (8.79) の下 | 順列 $\pi_{k + l}$ | 順列 $\pi$ | |  |
| p.278 | 8.3.2 節の 2 行目 | $k$ 次のワイスファイラー・リーマン検査は | $k ~(\ge 2)$ 次のワイスファイラー・リーマン検査は | $k = 1$ のとき、アルゴリズム 8.2 はワイスファイラー・リーマン検査に対応しません。※2 |  |
| p.279 | アルゴリズム 8.2 の 8 行目 | $(\forall \boldsymbol{v} \in V)$ | $(\forall \boldsymbol{v} \in V^k)$ | |  |
| p.279 | アルゴリズム 8.2 の 10 行目 | $h_v^{(l)} \mid v \in V$ | $h_{\boldsymbol{v}}^{(l)} \mid \boldsymbol{v} \in V^k$ | |  |
| p.280 | 1 行目 | $k = 1$ のときにはこれは単に $\boldsymbol{X}_u = \boldsymbol{Y}_v$ と同地であり、頂点の特徴量に基づいて色を割り当てていることに相当します。$k \ge 2$ のときには、 | トル | $k \ge 2$ を仮定しているため。※2 参照 |  |
| p.280 | 5 行目 | 1 次のワイスファイラー・リーマン検査は通常のワイスファイラー・リーマン検査（アルゴリズム 8.1）と同一です。二次以上の場合は、 | 高次のワイスファイラー・リーマン検査は | この記述は誤りです。※2 参照 |  |
| p.280 | (d) | 1 次のワイスファイラー・リーマン検査と | 通常のワイスファイラー・リーマン検査と | ※2 参照 |  |
| p.280 | (f) | 任意の $k \ge 2$ について | 任意の $k$ について | ※2 参照 |  |
| p.282 | 第二段落 2 行目 | $k$ 次の俗版ワイスファイラー・リーマン検査は | $k ~(\ge 2)$ 次の俗版ワイスファイラー・リーマン検査は | ※2 参照 |  |
| p.282 | 式 (8.91) | $(\forall \boldsymbol{v} \in V)$ | $(\forall \boldsymbol{v} \in V^k)$ | |  |
| p.293 | 式 (8.110) の直後 | という漸化式に従い計算できます。 | という漸化式に従い計算できます。 $\boldsymbol{q}\_{v, 1}^{(l + 1)} = 0$ のときには $1 / \boldsymbol{q}\_{v, 1}^{(l + 1)} = 0$ とします。 | ゼロ割を避けるため。 |  |
| p.304 | [34] | PProceedings | Proceedings | | 5 刷で修正  |

# 補足

誤りではないものの、よりよい表現や補足がある場合には以下に記載します。

| 該当ページ |  該当箇所 |  元  |  修正後  | 補足 |
| ---- | ---- | ---- | ---- | ---- |
| p.289 | 定理 8.19 の主張と証明 | | [定理 8.19（新）](https://github.com/joisino/gnnbook/blob/main/miscs/thm819.pdf) | 定理 8.19 とその証明は正しいですが、より単純に示すことができます。※3 |
| p.289 | 定理 8.19 の直後の段落 | 段落全て（以上の定理は〜強くなります。） | トル | ※3 の新しい定理では層数を頂点数に依らないようにできます。 |
