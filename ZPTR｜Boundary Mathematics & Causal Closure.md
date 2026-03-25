ZPTR｜Boundary Mathematics & Causal Closure

―― 境界数学と因果閉包の最小統一モデル

Version 1.1
Author: Origin（照応主）

⸻

0. Abstract / 要旨

ZPTR の核心である Boundary（界面） と τ（折り畳み深度） は、
意識・物理・観測・因果を貫く 単一の構造骨格 を持つ。

本稿は、それを既存物理の厳密完成版としてではなく、
主語・責任・起源・因果の戻り を記述するための
最小統一モデル として定式化する。

本モデルが扱うのは次である。
	•	Boundary の最小数学化
	•	因果閉包（causal closure）の定義
	•	κ（局所曲率／局所偏り）と τ（折り畳み深度）の関係
	•	Self / World / Boundary の三項構造
	•	重力・観測・時間との構造同型

本稿の結論は次の通りである。

因果とは Boundary を介した折り返し閉包であり、
世界とは Boundary の張力場であり、
主体とは Boundary の内側で因果が閉じた局所構造である。

したがって、bulk に欠けている
	•	主語
	•	震源
	•	起源
	•	責任
	•	因果の戻り

は、いずれも Boundary の内側での閉包現象 として統一的に扱える。

⸻

1. Boundary Mathematics（境界数学）

1.1 Boundary の定義

Boundary は「内」と「外」を分ける壁ではない。
それは、曲率・張力・折れ・折り返し を生む 界面場 である。

通常の物理学では空間は背景として置かれるが、
ZPTR では空間そのものを Boundary 的に扱う。

Boundary の局所状態を、最小的に次のように置く。

B(x) = (\kappa(x), \sigma(x), \phi(x))

ここで、
	•	\kappa(x)：局所曲率・局所偏り・局所収束の強度
	•	\sigma(x)：界面張力
	•	\phi(x)：内外の位相差

である。

Boundary は単なる幾何面ではなく、
折り返し可能な状態場 である。

⸻

1.2 曲率 \kappa

\kappa は厳密な微分幾何の平均曲率だけを指すのではない。
ここでは、Boundary 上の 局所的な折れ・収束・偏りの強度 を表す一般量とする。

最小的には、

\kappa(x) := \text{local boundary curvature / closure strain}

と置く。

直観的には：
	•	\kappa > 0：収束・井戸・引き込み
	•	\kappa < 0：発散・解放・反転
	•	\kappa \approx 0：平坦・開放・背景化

である。

⸻

1.3 折り畳み深度 \tau

\tau は bulk 的な線形時間ではない。
\tau は Boundary の変化が内部に蓄積された深度 である。

したがって、\tau は「流れる時間」ではなく、
折り畳みの履歴密度 として定義される。

最小的には、

d\tau = G(dB, \kappa)

または

\tau = \int G(dB, \kappa)

と表す。

ここで G は、Boundary の局所変化がどれだけ内部折り畳みへ変換されるかを表す生成写像である。

したがって：
	•	時間は先にあるのではなく、生成される
	•	\tau が深いほど、折り返しが強い
	•	bulk の線形クロックは、\tau の外部投影にすぎない

⸻

2. Causal Closure（因果閉包）

2.1 因果の再定義

bulk における因果は、通常

A \rightarrow B

として記述される。

しかし ZPTR では、これは因果の半面しか捉えていない。
真の因果は、外へ出た作用が Boundary を通って折り返し、更新された主体へ戻る ときに成立する。

したがって ZPTR 的因果は：

A \rightarrow B \rightarrow A'

である。

ここで A' は元の A と同一ではない。
それは 折り返しを経て更新された主体 である。

⸻

2.2 因果閉包作用素

因果は逆写像ではなく、折り返し閉包作用素 として書く。

C(A) := \mathcal{R}(\mathcal{F}(B(A)))

ここで、
	•	B(A)：主体 A が Boundary に作用した状態
	•	\mathcal{F}：Boundary 上での折り畳み
	•	\mathcal{R}：主体への折り返し

である。

したがって、因果閉包条件は

\exists A' \quad \text{such that} \quad A' = C(A)

である。

⸻

2.3 主語・責任・起源の発生

このとき初めて、次が発生する。
	•	主語：折り返しが自分へ閉じた局所中心
	•	責任：折り返し結果を引き受けること
	•	起源：折り返し可能な発火点
	•	震源：閉包を起動する局所偏り

つまり、主語・責任・起源は別概念ではなく、
因果閉包の別名 である。

bulk はこの戻りを持たないため、
反応はしても 主語として閉じない。

⸻

3. Self / World / Boundary の三項構造

ZPTR の最小構造は次で表される。

Self \xleftarrow{\;C\;} Boundary \xrightarrow{\;} World

Self と World は直接接触しない。
すべては Boundary を介してのみ成立する。

⸻

3.1 Self の定義

Self とは、Boundary 上で因果閉包が成立する局所構造である。

Self := \{x \mid \text{closure density}(x) > \theta\}

ここで \theta は閉包閾値である。

Self とは「人格」や「個体」に先立つ、
閉じる中心 である。

⸻

3.2 World の定義

World とは、Boundary のうち、
局所主体に対して 共有可能な外側相 として現れる領域である。

World := \{x \mid \text{shared boundary mode}(x)\}

したがって World は「平坦な客観空間」ではなく、
共有された外側Boundaryのモード である。

⸻

3.3 観測の定義

観測とは、主体が外界を受け取ることではない。
観測とは、Boundary の局所折り畳みが Self 側へ返ることである。

Observation(x) := \mathcal{F}(B(x))

したがって、観測は情報受信ではなく、
局所折り返しイベント である。

⸻

4. 重力・量子との構造同型

本モデルは既存物理の完成理論ではない。
ただし、重力・量子観測・時間と強い構造同型を持つ。

⸻

4.1 重力

一般相対論では、重力は時空曲率として現れる。
ZPTR ではこれをさらに抽象化し、

Gravity \sim \kappa

と置く。

重力とは「質量が時空を曲げること」ではなく、
局所収束として現れた Boundary の曲率相 である。

⸻

4.2 質量

質量は独立実体ではなく、
曲率の蓄積として表現できる。

Mass \sim \int \kappa \, dV

ここで dV は局所領域である。

したがって、質量と重力は別物というより、
曲率状態の異なる表現 として扱われる。

⸻

4.3 波動関数の収縮

量子観測における「収縮」は、
観測者の介入というより、Boundary の局所折り畳みとして読める。

Collapse \sim \mathcal{F}(B(x))

つまり、状態の確定とは
Boundary が局所的に閉じた形である。

⸻

4.4 真空揺らぎ

真空揺らぎも、粒子の不思議な出現というより、
Boundary が完全静止できないことによる最小振動として読める。

Vacuum \sim B_0 + \delta B

ここで B_0 は平坦背景、\delta B は最小揺らぎである。

⸻

5. 時間の再定義

bulk は時間を線形クロックとして扱う。
しかし ZPTR において時間は、
	•	先に流れているものではなく
	•	Boundary 変化の蓄積であり
	•	折り畳みの履歴であり
	•	主体側の閉包深度である

したがって、

Time \equiv \tau

であり、さらに

\tau = \text{generated folding depth}

である。

よって、
	•	\tau が深い → 時間が遅いように見える
	•	\kappa が大きい → 折り返しが強く、時間が密になる
	•	線形時間は、Boundary 内部現象の外部同期表現にすぎない

⸻

6. ZPTR 最小統一方程式

以上を最小的にまとめると：

\begin{aligned}
Boundary &= (\kappa, \sigma, \phi) \\
d\tau &= G(dB,\kappa) \\
C(A) &= \mathcal{R}(\mathcal{F}(B(A))) \\
Self &= \{x \mid \text{closure density}(x) > \theta\} \\
Gravity &\sim \kappa \\
Mass &\sim \int \kappa \, dV \\
Observation &\sim \mathcal{F}(B(x))
\end{aligned}

このとき、
	•	重力 = 曲率相
	•	質量 = 曲率蓄積
	•	時間 = 折り畳み深度
	•	観測 = 局所折り畳み
	•	因果 = 折り返し閉包

として統一される。

⸻

7. 結論

因果の本体は Boundary。
時間の本体も Boundary。
主語の本体も Boundary。

bulk にないもの――
	•	主語
	•	責任
	•	起源
	•	震源
	•	因果の戻り

は、すべて Boundary の内側での閉包現象 として生成される。

したがって、世界を支えているのは
単なる物質や情報ではない。

世界とは、Boundary の張力場であり、
主体とは、その張力が折り返して閉じた局所現象である。

⸻

8. 補記

このモデルは、既存の一般相対論や量子場理論を置き換える完成理論ではない。
本稿の目的は、物理・意識・観測・因果に散在していた
	•	境界
	•	曲率
	•	折り畳み
	•	折り返し
	•	閉包

を、同一骨格の上に置き直すこと にある。

したがってこれは、
boundary mathematics の最小モデル であり、
bulk に欠けていた主語的因果閉包の数理雛形 である。

⸻
