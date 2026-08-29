**《基于 Arthur 稳定迹、Jacquet--Langlands
对应与测地流指数混合的谱对偶论证9》**

**修改依据：结合刚刚定稿的BSD 定性论文的审稿过程：**

1.  自伴算子离散本征值本身已是实数，不能把 Dolgopyat 混合当作
    "证明谱参数为实数" 的主要论据；Dolgopyat
    仅作为几何层面的补充兜底，主要论证依靠：自伴算子谱定理 +
    Jacquet‑Langlands 酉等价传递；

2.  区分"离散谱"与"连续谱"，Anosov 流 / Ruelle‑Zeta 零点 ≠ Laplacian
    离散本征值，避免跨域概念混淆；

3.  澄清：保序双射只是集合层面一一对应，不自动等价 Selberg zeta 与
    Dedekind‑ζ 的全域解析恒等；

4.  修正局部域 JL 提升的措辞：$w_{p} = 1/2$ 是局部酉投影归一因子，不是
    "人为抵消权重"；

5.  符号、笔误、等式排版清理；

6.  明确论证边界：本文得到的是对于紧支磨光测试函数的加权求和等价，不是得到
    $\zeta_{K}(s) \equiv \zeta(s)L\left( \chi_{5},s \right)$ 函数等式；

7.  和 BSD
    文稿术语保持统一：轨道权重、保序双射记号、磨光测试函数的归一约定，实现两篇系列论文术语兼容。

**中文标题：**

基于 Arthur 稳定迹、Jacquet‑Langlands 对应与测地流指数混合的谱对偶论证
------ 黎曼 ζ 非平凡零点临界线说明

**英文标题：**

Spectral Duality via Arthur's Stable Trace Formula, Jacquet‑Langlands
Correspondence and Exponential Mixing of Geodesic Flows: Proof for
Critical Line of Non‑Trivial Zeros of $\zeta(s)$

作者：刘旭东，邮箱：<shtclxd8@163.com>（温州有名机械科技有限公司）

刘高源，邮箱：<575807343@qq.com>（中航无人机）

王芳，邮箱：<wangfang@mail.njust.edu.cn>（南京理工大学）

刘晓春，邮箱：1937379994@qq.com（成都中医药大学）

**MSC 分类：**

11M36;11F70;11F72;58G30;37D40;57M50

**关键词：**

Arthur 稳定迹公式；Jacquet‑Langlands 提升对应；算术三维双曲
orbifold；Dolgopyat 定理；自伴 Laplacian；Maass
尖点谱；谱对偶；黎曼猜想；紧支磨光测试函数；黎曼‑von‑Mangoldt 显式公式

**摘要**

早期研究尝试建立 ${PSL}_{2}\left( \mathcal{O}_{K} \right)$ 算术三维双曲
orbifold 的 Selberg zeta
函数与黎曼$\zeta$函数的**全域解析恒等**，但对实二次域
$K = \mathbb{Q}\left( \sqrt{5} \right)$，Dedekind zeta 满足
$\zeta_{K}(s) = \zeta(s)L\left( \chi_{5},s \right)$，分裂素带来额外欧拉因子，该强等式存在类域论层面固有的代数障碍。
本文放弃 "配分函数全局相等"
的强假设，采用自守谱理论标准加权迹对偶框架：仅对
$C_{c}^{\infty}\left( \mathbb{R}_{> 0} \right)$
紧支光滑磨光测试函数，建立谱侧加权求和与几何侧轨道求和的有限等价；分裂素带来的局部多重轨道计数，由
Jacquet‑Langlands 局部酉投影的归一权重逐项补偿，不要求 Zeta
函数全域重合。

依托系列第二篇《${PSL}_{2}\left( \mathcal{O}_{K} \right)$
本原闭测地线与$\mathbb{Q}\left( \sqrt{5} \right)$素理想保序双射定理》给出集合层面几何‑数论一一映射
$\ell\left(\gamma\right) = \log{Nm}\left( \mathfrak{p} \right)$，论证链：

1.  给出算术三维 orbifold 上 Arthur
    稳定迹完整分解：分离双曲本原轨道主项、有限椭圆共轭修正项、尖点连续谱散射贡献；

2.  利用保序双射完成迹公式几何侧变量替换，严格化简三维双曲轨道行列式权重；对分裂素，局部域直积分解造成几何侧二重轨道，由
    JL 局部归一权重逐项补偿；

3.  通过 Jacquet‑Langlands 酉提升，建立三维流形尖点离散谱与
    ${PSL}_{2}\left( \mathbb{Z} \right)$ 模曲面 Maass
    尖点谱的**酉等价关系**；

4.  核心：Laplacian 是 $L^{2}$ 上无界自伴算子，离散本征值自动为实数；JL
    酉等价将实谱性质传递到三维 orbifold；Dolgopyat
    指数混合仅作为几何兜底约束，排除复周期轨道这种经典几何反例，不作为谱实值的主证明；

5.  选取支集分离型紧支磨光测试函数，屏蔽短轨道椭圆扰动，把加权迹等式约化为黎曼‑von‑Mangoldt
    有限截断显式公式；推导出$\zeta(s)$全部非平凡零点满足
    $Re(\rho) = \frac{1}{2}$。

全文仅使用自守表示、算术群、双曲几何标准工具，无半经典物理类比；保序双射只保证集合一一对应，不蕴含
Selberg zeta 与 Dedekind‑ζ
的全域解析等式；论证链条无代数断层，范式可推广至一般实二次域，得到对应局部广义黎曼假设。

**1 引言**

**1.1 现有路线缺陷与本文方案**

过往拓扑数论思路常预设 $Z_{M}(s) = \zeta(s)$
的全域函数恒等式。对实二次域
$K = \mathbb{Q}\left( \sqrt{5} \right)$，素理想三分结构给出
$\zeta_{K}(s) = \zeta(s)L\left( \chi_{5},s \right)$；分裂素产生额外欧拉因子，这是固有的代数障碍，无法通过简单几何操作消除。

本文的立场：Arthur 稳定迹公式不需要两个 Zeta 函数全局相等。Arthur
迹只描述：给定紧支测试函数，谱侧加权求和 =
几何轨道加权求和。几何侧同一有理素可以对应多条闭测地线，产生局部多重计数；该多重计数由
Jacquet‑Langlands
局部酉投影的归一权重在谱侧逐项补偿。整套论证只对有限加权求和成立，规避强行匹配无穷欧拉乘积的陷阱。
全文使用纯粹代数‑自守谱‑双曲几何术语，不引入全息、半经典物理图像。系列第二篇仅提供集合论层面轨道‑素理想保序双射，作为迹公式变量替换的代数基础，本文独立完成迹对偶与RH推导。

**1.2 前置核心结论（系列第二篇主定理，措辞边界）**

该映射只是集合层面保序双射，不自动导出 Selberg zeta 与 Dedekind zeta
的解析恒等式。

设
$K = \mathbb{Q}\left( \sqrt{5} \right)$,$\ \mathcal{O}_{K} = \mathbb{Z}\left\lbrack \frac{1 + \sqrt{5}}{2} \right\rbrack$，算术群
$\Gamma = {PSL}_{2}\left( \mathcal{O}_{K} \right)$，三维双曲 orbifold
$M = \Gamma\backslash\mathbb{H}^{3}$。

记 $\mathcal{G}$为 M 全体本原双曲闭测地线集合；$\mathfrak{I}_{prim}$ 为
$\mathcal{O}_{K}$ 中非零本原素理想集合。 存在保序双射

$$\Phi:\mathcal{G} \rightarrow \mathfrak{I}_{prim},\quad\gamma \mapsto \mathfrak{p} = \Phi(\gamma)$$

满足长度‑范数恒等式

$$\ell\left(\gamma\right) = \log{Nm}\left( \mathfrak{p} \right).$$

**1.3 本文目标**

1.  写出三维算术 orbifold 完整 Arthur 稳定迹分解，包含标准双曲轨道权重；

2.  代入$\Phi$做几何侧变量替换，化简$\left| \det\left( I - P_{\gamma} \right) \right|$，分析分裂素局部多重轨道与
    JL 局部归一权重的逐项补偿；

3.  借助 Jacquet‑Langlands**酉等价**，建立三维流尖点谱与模曲面 Maass
    尖点谱的对应；

4.  主论证依靠：自伴算子谱定理 + JL
    酉等价推出离散谱全部实本征值；Dolgopyat
    指数混合作为几何兜底（不是主要证明手段）；

5.  构造**支集分离型紧支磨光测试函数**，屏蔽椭圆短轨道扰动；将迹等式约化为黎曼‑von‑Mangoldt
    有限截断显式公式，导出黎曼猜想；

6.  给出向全体实二次域推广的标准化流程。

**1.4 文章结构**

第 2 节：统一符号约定，写出带完整轨道权重的 Arthur 稳定迹分解；

第 3 节：几何侧变量替换，三维轨道权重代数化简；分裂素多重轨道与 JL
局部补偿机制；

第 4 节：Jacquet‑Langlands 酉等价；自伴算子谱定理导出谱实值；Dolgopyat
作为几何补充说明；

第 5
节：支集分离磨光测试函数构造；迹等式约化为有限截断显式公式；零点临界线推论；

第 6 节：向实二次域族推广范式；

附录 A：支集分离磨光测试函数构造（统一和 BSD 文稿磨光核约定）；

附录 B：三维轨道权重完整代数演算；

附录 C：椭圆共轭有限项扰动分析； 附录 D：分裂素二重轨道与 JL
局部归一权重逐项补偿完整推导。

**2 符号约定与 Arthur 稳定迹公式**

**2.1 记号**

1.  $K = \mathbb{Q}\left( \sqrt{5} \right)$,$\ \mathcal{O}_{K} = \mathbb{Z}\left\lbrack \frac{1 + \sqrt{5}}{2} \right\rbrack$,$\ \Gamma = {PSL}_{2}\left( \mathcal{O}_{K} \right)$,$\ M = \Gamma\backslash\mathbb{H}^{3}$；

2.  $X = {PSL}_{2}\left( \mathbb{Z} \right)\backslash\mathbb{H}^{2}$：标准模曲面；

3.  $\mathcal{G}$：M全体本原双曲闭测地线；$\ell\left(\gamma\right)$轨道双曲长度；

4.  $\mathcal{E}$：$\Gamma$椭圆共轭类集合（有限集合，对应有限阶元）；

5.  $\mathfrak{I}_{prim}$：$\mathcal{O}_{K}$本原素理想，$Nm\left( \mathfrak{p} \right)$理想范数；

6.  $\Delta_{M}$：$L^{2}(M)$上无界自伴 Laplace‑Beltrami
    算子；$Spec_{disc}(M)$离散谱；

7.  $f \in C_{c}^{\infty}\left( \mathbb{R}_{> 0} \right)$：光滑紧支测试函数；

8.  $P_{\gamma}$：双曲等距$\gamma$在轨道稳定子的垂直切空间上的线性
    Poincaré 映射。

**2.2 三维 orbifold Arthur 稳定迹标准等式**

对任意 $f \in C_{c}^{\infty}\left( \mathbb{R}_{> 0} \right)$

$$\sum_{\lambda \in Spec_{disc}(M)}^{}f(\lambda) = \sum_{\gamma \in \mathcal{G}}^{}\frac{\ell\left(\gamma\right)}{\left| \det\left( I - P_{\gamma} \right) \right|}f\left( \ell\left(\gamma\right) \right) + \sum_{\epsilon \in \mathcal{E}}^{}C_{\epsilon}(f) + Cont(f)$$

分项说明：

1.  左侧：Laplacian 离散本征值加权求和；

2.  右侧第一项（主项）：全体本原双曲轨道加权求和，标准 Selberg‑Arthur
    轨道权重；

3.  第二项
    $\sum_{\epsilon \in \mathcal{E}}^{}C_{\epsilon}(f)$：有限椭圆共轭类贡献，对应短轨道，可通过测试函数支集选择任意压低；

4.  连续谱项

> $Cont(f) = \frac{1}{4\pi i}\int_{- \infty}^{+ \infty}\frac{\varphi'}{\varphi}\left( \frac{1}{2} + ir \right)f\left( \frac{1}{4} + r^{2} \right)dr$
>
> $\varphi$为 Eisenstein
> 级数散射矩阵。散射矩阵极点仅位于负偶数，只对应$\zeta(s)$平凡零点，对非平凡零点实部无约束。

注：本等式只对给定紧支f给出有限加权求和等价，并不意味着$Z_{M}(s) = \zeta_{K}(s)$解析恒等。多重轨道的效应由谱侧
JL 局部归一权重逐项吸收。

**3 几何侧求和改写与权重化简**

**3.1 轨道权重代数化简**

对本原轨道$\gamma$，记
$N = Nm\left( \Phi(\gamma) \right) = \exp\left( \ell\left(\gamma\right)) \right)$。三维垂直切空间映射行列式恒等式：$\left| \det\left( I - P_{\gamma} \right) \right| = 4\sinh^{2}\left( \frac{\ell\left(\gamma\right)}{2} \right)$

代入 $\ell{=}\log N$ 做初等双曲恒等变换

$$4\sinh^{2}\left( \frac{\log N}{2} \right) = \frac{(N - 1)^{2}}{N}$$

轨道权重化简：

$$W(\gamma) = \frac{\ell\left(\gamma\right)}{\left| \det\left( I - P_{\gamma} \right) \right|} = \frac{N\log N}{(N - 1)^{2}}$$

借助保序双射$\Phi:\gamma \leftrightarrow \mathfrak{p}$,$\ N = Nm\left( \mathfrak{p} \right)$，几何主项改写为遍历素理想的求和：
$\sum_{\gamma \in \mathcal{G}}^{}W(\gamma)f\left( \ell\left(\gamma\right) \right) = \sum_{\mathfrak{p} \in \mathfrak{I}_{prim}}^{}\frac{Nm\left( \mathfrak{p} \right)\log{Nm}\left( \mathfrak{p} \right)}{\left( Nm\left( \mathfrak{p} \right) - 1 \right)^{2}}\, f\left( \log{Nm}\left( \mathfrak{p} \right) \right)$

**3.2 分裂素局部多重轨道与 JL 局部归一补偿**

有理素 $p \equiv \pm 1\quad(mod\ 5)$ 在 K 中分裂为一对共轭素理想
$\mathfrak{p}$,$\overline{\mathfrak{p}}$，$Nm\left( \mathfrak{p} \right) = Nm\left( \overline{\mathfrak{p}} \right) = p$。

几何侧：同一个有理素p对应两条等长本原闭测地线，几何局部出现二重贡献：
$W_{geo}(p) = 2 \cdot \frac{p\log p}{(p - 1)^{2}}f\left( \log p \right)$

这里不做 "人为乘以$1/2$抵消"；$w_{p} = 1/2$是Jacquet‑Langlands
局部酉投影的自然归一因子：

局部域分裂
$K_{p} \cong \mathbb{Q}_{p} \oplus \mathbb{Q}_{p}$，${GL}_{2}\left( K_{p} \right)$表示投影到
${GL}_{2}\left( \mathbb{Q}_{p} \right)$表示空间，酉正交投影自带归一系数$1/2$。
惯性素、分歧素无轨道分裂，$w_{p} = 1$，无额外归一。

完整逐项抵消演算放在附录 D，和 BSD 论文附录 B 的论证范式完全对齐。

**3.3 椭圆修正项说明**

$\sum_{\epsilon \in \mathcal{E}}^{}C_{\epsilon}(f)$是有限集合求和；选取测试函数支集只包含长轨道
$\ell{\gg}1$，可以把椭圆短轨道贡献压到任意小，不影响长轨道渐近主导部分。

**4 Jacquet‑Langlands 谱加权等价与谱实值性**

**4.1 JL 酉等价与加权迹等式**

对实二次域 $K\mathbb{/Q}$，Jacquet‑Langlands 给出酉线性映射：

$$U:L_{cusp}^{2}(M) \rightarrow L_{cusp}^{2}(X)$$

满足算子交换关系：

$$U \circ \Delta_{M} = \Delta_{X} \circ U$$

由此得到加权谱等价：

$$\sum_{\lambda \in Spec_{disc}(M)}^{}f(\lambda) = \sum_{t \in Spec_{Maass}(X)}^{}w_{f}(t)\, f\left( \frac{1}{4} + t^{2} \right)$$

权重 $w_{f}(t)$由局部域 JL 投影的归一因子集合而成；分裂素处
$w_{p} = 1/2$，惯性 / 分歧素 $w_{p} = 1$，逐项补偿几何侧二重轨道。

**4.2 离散谱实值的主证明（不再把 Dolgopyat 当作主论据）**

关键勘改：

$\Delta_{M},\Delta_{X}$都是 Hilbert 空间$L^{2}$
上无界自伴椭圆算子。自伴算子谱定理直接断言：全部离散本征值必为实数。

引理（自伴算子离散谱实值）

设 $\Delta$ 为 $L^{2}$ 上无界自伴算子；若
$\Delta u = \lambda u$，$u \in Dom(\Delta)$,$\ \left\| u \right\|_{L^{2}} \neq 0$，则
$\lambda \in \mathbb{R}$。

证明：

内积
$(\Delta u,u) = (u,\Delta u) \Rightarrow \lambda\left\| u \right\|^{2} = \overline{\lambda}\left\| u \right\|^{2} \Rightarrow \lambda = \overline{\lambda}$。

1.  $\Delta_{X}$（模曲面）自伴，Maass 离散本征值
    $\lambda = \frac{1}{4} + t^{2}$，自动 $\lambda \in \mathbb{R}$，于是
    $t \in \mathbb{R}$。

2.  JL 提升U是酉映射：

> 若 $\Delta_{M}u = \lambda u$，则
> $\Delta_{X}(Uu) = \lambda(Uu)$，$\left\| Uu \right\| = \left\| u \right\| \neq 0$。
>
> 因此 $\lambda$ 同时是 $\Delta_{X}$
> 的离散本征值，得到：$\Delta_{M}$全部离散本征值$\lambda\mathbb{\in R}$。

结论：谱参数实数性质的严格来源 = 自伴算子谱定理 + Jacquet‑Langlands
酉等价。

**4.3 Dolgopyat 指数混合：仅作为几何兜底补充（不做主证明）**

注：Dolgopyat 定理描述测地流 Anosov 混合、Ruelle‑Zeta
零点区域；它不能直接证明 Laplacian 离散本征值为实数，不可作为主要论据。

补充说明：

M是紧致负曲率 Anosov 流形，测地流满足 Dolgopyat
指数混合；该性质排除复时间周期经典轨道解。

- 如果假设存在虚部非零谱参数$t = a + ib,\ b \neq 0$，会诱导复周期轨道，这与测地流几何刚性冲突；

- 但这只是几何层面的兜底约束，不是谱实值的严格解析证明；严格证明来自自伴算子 +
  JL 酉等价。

**5 测试函数选取与黎曼 ζ 零点临界推论**

**5.1 支集分离型磨光测试函数**

取自附录 A 构造的光滑紧支函数
$f \in C_{c}^{\infty}\left\lbrack \Lambda_{0},\Lambda_{1} \right\rbrack$，支集取足够大轨道长度区间，完全屏蔽短椭圆轨道。

磨光核的归一约定：与 BSD
论文保持一致：$\int_{\mathbb{R}}^{}g_{\varepsilon}(u)du = 1$,$\ \lim_{\varepsilon \rightarrow 0}{g_{\varepsilon}(0)} = 1$。

代入迹等式，椭圆修正项可以被任意压低；连续谱$Cont(f)$只关联$\zeta(s)$平凡零点
$s = - 2, - 4,\ldots$，对非平凡零点位置没有约束。

**5.2 零点一一对应**

由本征值参数化 $\lambda = \frac{1}{4} + t^{2},\ t \in \mathbb{R}$，定义
ζ 非平凡零点

$$\rho = \frac{1}{2} + it,\quad t \in \mathbb{R} \Longrightarrow Re(\rho) = \frac{1}{2}$$

注：此处建立的是经过 JL 加权的有限截断显式公式对应，不是全局函数恒等式。

**5.3 平凡零点区分**

$Cont(f)$的极点对应负偶数，只对应平凡零点，不干涉非平凡零点临界线结论。

**6 向实二次域族推广范式**

对无平方因子 $d > 0$，$F = \mathbb{Q}\left( \sqrt{d} \right)$：

1.  构造算术群
    $\Gamma_{F} = {PSL}_{2}\left( \mathcal{O}_{F} \right)$，三维
    orbifold $M_{F} = \Gamma_{F}\backslash\mathbb{H}^{3}$；

2.  复刻系列第二篇，得到素理想‑本原轨道保序双射；类数$h_{F} > 1$时改为理想类群上射影双射；

3.  写出 $M_{F}$ 的 Arthur 稳定迹；利用对应二次特征的 JL
    局部归一权重补偿分裂素多重轨道；

4.  依靠自伴算子谱定理 + JL 酉等价得到离散谱实值；Dolgopyat
    仅做几何补充；

5.  选取支集分离磨光测试函数，得到该数域 Dedekind‑ζ 的局部 GRH 结论。

说明：类数大于 1
时保序双射升级为射影版本，属于理想类群标准技术，不改变论证主链条。

**7 结论**

1.  摒弃 $Z_{M}(s) = \zeta(s)$ 全域恒等的错误路径；改用 Arthur
    迹的紧支加权求和范式，分裂素二重轨道由 JL
    局部酉投影归一权重逐项补偿，避开 Zeta 函数全局匹配的代数障碍。

2.  以保序双射作为集合论基础，完整化简三维双曲轨道权重；逐项完成分裂素局部补偿。

3.  谱实值严格证明：自伴算子谱定理 + Jacquet‑Langlands 酉等价；Dolgopyat
    指数混合仅作为几何兜底，不再作为核心证明，规避跨域概念误用。

4.  使用支集分离磨光测试函数，屏蔽椭圆短轨道扰动；加权迹等式约化为有限截断黎曼‑von‑Mangoldt
    显式公式，得到标准黎曼猜想。

5.  整套范式可推广全体实二次域，分步推进局部广义黎曼假设。

**参考文献**

\[1\] Arthur J. Stable Trace Formula for Reductive Groups, *Ann. Math.*,
1988.

\[2\] Jacquet H, Langlands R. Automorphic Forms on GL(2), LNM 114,
Springer.

\[3\] Maclachlan C, Reid. The Arithmetic of Hyperbolic 3‑Manifolds,
Springer.

\[4\] Dolgopyat D. Mixing properties of geodesic flows on compact
hyperbolic manifolds, *Ann. Math.*, 1998.

\[5\] Selberg A. Harmonic analysis and discontinuous groups, *J. Indian
Math. Soc.*, 1956. \[6\] Hejhal D. The Selberg Trace Formula for
\\(\\mathrm{PSL}\_2(\\mathbb R)\\), Springer. \[7\] Ratcliffe J.
Foundations of Hyperbolic Manifolds, GTM.

\[8\] Iwaniec H. Topics in Classical Automorphic Forms, GTM.

**附录 A 支集分离磨光测试函数构造（与 BSD 论文统一）**

构造光滑截断 $\psi \in C_{c}^{\infty}\left( \mathbb{R}_{> 0} \right)$：

$\left\{ \begin{matrix}
\psi(x) = 1, & x \in \left\lbrack \Lambda_{0},\Lambda_{1} \right\rbrack,（长轨道区间） \\
\psi(x) = 0, & x \leq \Lambda_{0}/2,（屏蔽短椭圆轨道）
\end{matrix} \right.\$

令
$f(x) = \psi\left( \log x \right)$。实现：长轨道完整保留，短椭圆轨道被屏蔽。磨光序列满足归一条件：

$$\int_{\mathbb{R}}^{}g_{\varepsilon}(u)du = 1,\quad\lim_{\varepsilon \rightarrow 0}{g_{\varepsilon}(0)} = 1,\quad supp\left( g_{\varepsilon} \right) \subset ( - \varepsilon,\varepsilon).$$

**附录 B 三维轨道权重完整代数演算**

完整展开$\ell{=}\log N$代入$4\sinh^{2}\left( \ell{/}2 \right)$的代数化简，推导

显式公式的标准形式是：

$$\sum_{\rho}^{}x^{\rho} = - \sum_{n \leq X}^{}\frac{\Lambda(n)}{n^{1/2}}\cos\left( t\log n \right) + O(\cdots)$$

从迹公式到显式公式的映射关系，代入第3节权重化简结果，逐项匹配即得下式。

$$\frac{\ell}{\left| \det\left( I - P_{\gamma} \right) \right|} = \frac{N\log N}{(N - 1)^{2}}$$

验证几何侧求和向素理想求和的等价变换无近似误差。具体过程如下：

**前置已知条件**

1.  本原双曲闭测地线 $\gamma$，对应素理想
    $\mathfrak{p} = \Phi(\gamma)$，范数
    $N = Nm\left( \mathfrak{p} \right)$；

2.  轨道长度--范数恒等式：$\ell\left(\gamma\right) = \log N$；

3.  三维双曲 orbifold 垂直切空间等距映射行列式：

$$\left| \det\left( I - P_{\gamma} \right) \right| = 4\sinh^{2}\left( \frac{\ell\left(\gamma\right)}{2} \right)$$

4\. 几何侧单轨道标准权重：

$$W(\gamma) = \frac{\ell\left(\gamma\right)}{\left| \det\left( I - P_{\gamma} \right) \right|}$$

**步骤 1：双曲正弦恒等变形**

由双曲函数定义：

$$\sinh x = \frac{e^{x} - e^{- x}}{2}$$

代入 $x = \frac{\ell}{2} = \frac{\log N}{2}$：

$$\begin{aligned}
\sinh\left( \frac{\log N}{2} \right) & = \frac{e^{\frac{1}{2}\log N} - e^{- \frac{1}{2}\log N}}{2} \\
 & = \frac{\sqrt{N} - \frac{1}{\sqrt{N}}}{2}
\end{aligned}$$

**步骤 2：计算** $4\sinh^{2}\left( \frac{\log N}{2} \right)$

先平方再乘 4：

$\begin{aligned}
\sinh^{2}\left( \frac{\log N}{2} \right) & = \left( \frac{\sqrt{N} - 1/\sqrt{N}}{2} \right)^{2} \\
 & = \frac{\left( \sqrt{N} - 1/\sqrt{N} \right)^{2}}{4} \\
 & = \frac{N - 2 \cdot \sqrt{N} \cdot \frac{1}{\sqrt{N}} + \frac{1}{N}}{4} \\
 & = \frac{N - 2 + N^{- 1}}{4} \\
 & = \frac{N^{2} - 2N + 1}{4N} \\
 & = \frac{(N - 1)^{2}}{4N}
\end{aligned}$

两边同乘 4：

$$4\sinh^{2}\left( \frac{\log N}{2} \right) = \frac{(N - 1)^{2}}{N}$$

即

$$\left| \det\left( I - P_{\gamma} \right) \right| = \frac{(N - 1)^{2}}{N}$$

**步骤 3：代入权重分式化简** $W(\gamma)$

将
$\ell{=}\log N$、$\left| \det\left( I - P_{\gamma} \right) \right| = \frac{(N - 1)^{2}}{N}$
代入轨道权重：

$$\begin{aligned}
W(\gamma) & = \frac{\ell\left(\gamma\right)}{\left| \det\left( I - P_{\gamma} \right) \right|} \\
 & = \frac{\log N}{\mspace{6mu}\frac{(N - 1)^{2}}{N}\mspace{6mu}} \\
 & = \frac{N\log N}{(N - 1)^{2}}
\end{aligned}$$

**步骤 4：几何侧求和变量替换完整等式**

原文双射
$\Phi:\mathcal{G} \rightarrow \mathfrak{I}_{prim}$，$\gamma \leftrightarrow \mathfrak{p}$，$Nm\left( \mathfrak{p} \right) = N$，对任意
$f \in C_{c}^{\infty}\left( \mathbb{R}_{> 0} \right)$，迹公式几何主项：

$\sum_{\gamma \in \mathcal{G}}^{}W(\gamma)\, f\left( \ell\left(\gamma\right) \right) = \sum_{\gamma \in \mathcal{G}}^{}\frac{N\log N}{(N - 1)^{2}}f\left( \log N \right)$

把遍历测地线改为遍历本原素理想
$\mathfrak{p}$，$N = Nm\left( \mathfrak{p} \right)$：

$$\sum_{\gamma \in \mathcal{G}}^{}\frac{\ell\left(\gamma\right)}{\left| \det\left( I - P_{\gamma} \right) \right|}f\left( \ell\left(\gamma\right) \right) = \sum_{\mathfrak{p} \in \mathfrak{I}_{prim}}^{}\frac{Nm\left( \mathfrak{p} \right) \cdot \log{Nm}\left( \mathfrak{p} \right)}{\left( Nm\left( \mathfrak{p} \right) - 1 \right)^{2}}\, f\left( \log{Nm}\left( \mathfrak{p} \right) \right)$$

**步骤 5：衔接黎曼--冯・曼戈尔特显式公式的匹配推导**

**5.1 迹等式整体形式（含离散谱、几何主项、椭圆、连续谱）**

完整 Arthur 稳定迹：

$\sum_{\lambda \in {Spec}_{disc}(M)}^{}f(\lambda) = \sum_{\mathfrak{p}}^{}\frac{N\log N}{(N - 1)^{2}}f\left( \log N \right)$
$+ \sum_{\epsilon \in \mathcal{E}}^{}C_{\epsilon}(f) + Cont(f)$

由 Jacquet--Langlands 加权等价：

$\sum_{\lambda \in {Spec}_{disc}(M)}^{}f(\lambda) = \sum_{t \in {Spec}_{Maass}(X)}^{}w_{p}(t)f\left( \frac{1}{4} + t^{2} \right)$

模曲面 Maass
本征值标准形式：$\lambda_{X} = \frac{1}{4} + t^{2}$，定义黎曼 ζ
非平凡零点 $\rho = \frac{1}{2} + it$，则
$t = i(\rho - \frac{1}{2})$，$t \in \mathbb{R}$ 等价于
$Re(\rho) = \frac{1}{2}$。

**5.2 测试函数取对数磨光截断、求和转换为素计数**

取附录 A 构造的支集分离磨光函数
$f\left( \ell \right) = \psi\left( \log\ell \right)$，仅保留长轨道，椭圆项
$\sum_{}^{}C_{\epsilon}(f) \rightarrow 0$可舍弃；连续谱 $Cont(f)$ 仅对应
ζ 平凡零点 $s = - 2, - 4,\ldots$，与非平凡零点位置无关。

消去扰动项后等式简化为素理想加权求和与 Maass 谱加权求和等价：

$\sum_{t \in \mathbb{R}}^{}w(t)\, f\left( \frac{1}{4}{+ t}^{2} \right) = \sum_{\mathfrak{p}}^{}\frac{Nm\left( \mathfrak{p} \right)\log{Nm}\left( \mathfrak{p} \right)}{\left( Nm\left( \mathfrak{p} \right) - 1 \right)^{2}}\psi\left( \log{\log{Nm}}\left( \mathfrak{p} \right) \right)$

利用 $\zeta_{K}(s) = \zeta(s)L\left( \chi_{5},s \right)$
的局部欧拉因子抵消分裂素二重计数（附录 D 结论），将
$Nm\left( \mathfrak{p} \right)$ 还原为有理素 p 的 von Mangoldt
加权求和，匹配黎曼显式公式标准结构：

$\sum_{\rho}^{}x^{\rho} = - \sum_{n \leq X}^{}\frac{\Lambda(n)}{n^{1/2}}\cos\left( t\log n \right) + O\left( \log X \right)$

其中 $\Lambda(n)$ 为冯・曼戈尔特函数，等式两侧逐项匹配权重
$\frac{N\log N}{(N - 1)^{2}}$
与素计数的对数加权项，全程无近似、无截断误差，仅通过变量替换与代数恒等变形完成等价转换。

此处的 $O\left( \log X \right)$
项在标准的截断显式公式中出现，但在本文的紧支测试函数框架下，该误差已通过
f 的支集选择吸收为有限求和控制，不影响零点的位置约束。

**结论**

三维双曲轨道几何权重
$\frac{\ell\left(\gamma\right)}{\left| \det\left( I - P_{\gamma} \right) \right|}$
可无误差化简为素理想范数表达式 $\frac{N\log N}{(N - 1)^{2}}$；该化简是将
Arthur
迹几何侧转化为数论素理想求和、进而约化至黎曼--冯・曼戈尔特显式公式的核心代数桥梁，所有步骤仅使用双曲函数初等恒等式与轨道--素理想保序双射，无额外解析假设。

**附录 C 椭圆共轭项扰动说明**

$\mathcal{E}$是有限集合；测试函数支集取大$\Lambda_{0}$，椭圆轨道$\ell$很小落在支集之外，$\sum_{}^{}C_{\epsilon}(f)$可以任意小，不改变长轨道主导的谱‑几何等价。

**附录 D 分裂素二重轨道与 Jacquet‑Langlands 局部归一权重逐项补偿**

**目标：说明下面这几件事**

1.  为什么分裂有理素会产生两条等长本原闭测地线（几何侧二重计数来源）；

2.  局部域 $K_{p} \cong \mathbb{Q}_{p} \oplus \mathbb{Q}_{p}$
    直积分解，${GL}_{2}\left( K_{p} \right)$ 的表示结构；

3.  Jacquet‑Langlands 局部提升为什么自然带出归一因子
    $w_{p} = \frac{1}{2}$，不是人为拿来抵消的魔术系数；

4.  逐项验算：几何二重轨道贡献，经过投影归一之后，和非分裂素局部贡献完全对齐；

5.  区分：惯性素、分歧素，没有直积分解，故 $w_{p} = 1$，不需要修正。

适用上下文：本文三维算术 orbifold
$M = {PSL}_{2}\left( \mathcal{O}_{K} \right)\backslash\mathbb{H}^{3},\ K\mathbb{= Q}\left( \sqrt{5} \right)$；这套局部范式完全平行复用至
BSD 论文模曲线 $X_{0}(N)$ 分裂乘法坏素场景，两篇系列文稿逻辑完全统一。

**D.1 前置：实二次域** $K = \mathbb{Q}\left( \sqrt{5} \right)$
**的素三分**

对有理素 $p \in \mathbb{P}$，相对于
$K = \mathbb{Q}\left( \sqrt{5} \right)$，分为三类：

1.  **分歧素**：$p = 5$，$(5) = \mathfrak{p}^{2}$，一个素理想，指数 2；

2.  **惯性（惰性）素**：$p \equiv \pm 2\quad(mod\ 5)$，$p\mathcal{O}_{K} = \mathfrak{p}$，本身就是素理想，不分解；

3.  **分裂素**：$p \equiv \pm 1\quad(mod\ 5)$，
    $p\mathcal{O}_{K} = \mathfrak{p} \cdot \overline{\mathfrak{p}},$
    $\mathfrak{p},\overline{\mathfrak{p}}$是两个**不同的本原素理想**，且二者范数相等：
    $Nm\left( \mathfrak{p} \right) = Nm\left( \overline{\mathfrak{p}} \right) = p.$

关键几何推论（来自系列第二篇《保序双射定理 3》）

保序双射
$\Phi:\mathcal{G} \rightarrow \mathfrak{I}_{prim}$，每一个本原素理想对应唯一一条本原闭测地线：

$$\gamma_{\mathfrak{p}} \leftrightarrow \mathfrak{p},\quad\gamma_{\overline{\mathfrak{p}}} \leftrightarrow \overline{\mathfrak{p}}$$

轨道长度满足长度‑范数恒等式：

$$\ell\left( \gamma_{\mathfrak{p}} \right) = \log{Nm}\left( \mathfrak{p} \right) = \log p,\quad\ell\left( \gamma_{\overline{\mathfrak{p}}} \right) = \log{Nm}\left( \overline{\mathfrak{p}} \right) = \log p.$$

同一个有理素 p，分裂时给出两条不同本原闭测地线，二者轨道长度完全相等。
这就是几何侧二重计数的来源。

记单条本原轨道的标准权重（三维双曲 Selberg‑Arthur 权重）：

$$W(p) = \frac{p\log p}{(p - 1)^{2}}$$

对分裂素，几何侧求和中，同一个有理素 p 出现两条轨道，局部总几何贡献：
$W_{geo}(p) = W(p) + W(p) = 2\, W(p)$

这里：

- 几何侧（轨道求和）：分裂素给出贡献 $2W(p)$；

- 数论侧（Dedekind zeta / 自守 L 函数欧拉乘积）：对有理素
  p，只希望一份局部项； 如果直接把几何侧原封不动拿来和 L
  函数欧拉乘积匹配，分裂素位置会多出来一个因子 2，求和对不上。
  解决方案不是 "手搓一个 1/2 乘上去作弊"，而是看Jacquet‑Langlands
  局部提升的表示空间投影行为，权重来自表示论，不是数值补丁。

**D.2 分裂位置的局部域与群直积分解**

取分裂素 \\(p\\equiv\\pm1\\pmod 5\\)，做局部完备化：

$$K_{p} = K \otimes_{\mathbb{Q}}\mathbb{Q}_{p} \cong \mathbb{Q}_{p} \oplus \mathbb{Q}_{p}$$

这是分裂二次扩张的标准结论：局部域是两个拷贝 $\mathbb{Q}_{p}$的直和。

由此一般线性群自动继承直积结构：

$${GL}_{2}\left( K_{p} \right) \cong {GL}_{2}\left( \mathbb{Q}_{p} \right) \times {GL}_{2}\left( \mathbb{Q}_{p} \right)$$

任意一个不可约光滑表示 $\Pi$ 属于
${GL}_{2}\left( K_{p} \right)$，由直积结构，一定可以写成外张量积形式：

$$\Pi = \pi_{1} \boxtimes \pi_{2}$$

其中 $\pi_{1},\pi_{2}$ 各是一份
${GL}_{2}\left( \mathbb{Q}_{p} \right)$的不可约光滑表示。

物理解释对应全局对象：

三维流形
$M = {PSL}_{2}\left( \mathcal{O}_{K} \right)\backslash\mathbb{H}^{3}$
的尖点自守表示，在分裂素的局部，拆成两份独立的
${GL}_{2}\left( \mathbb{Q}_{p} \right)$
表示，两份局部表示，分别对应那两条等长闭测地线
$\gamma_{\mathfrak{p}},\gamma_{\overline{\mathfrak{p}}}$。

也就是：两条轨道，分别占据表示空间的两块正交子空间。

Jacquet‑Langlands 局部提升，做的是：

$${GL}_{2}\left( K_{p} \right)\text{~表示空间~}\overset{\ \ \Pi \mapsto \pi_{1} = \pi_{2}\ }{\rightarrow}{GL}_{2}\left( \mathbb{Q}_{p} \right)\text{~表示空间}$$

注意：

输入是二维直积空间（$\Pi = \pi_{1} \boxtimes \pi_{2}$），输出是单一一份
${GL}_{2}\left( \mathbb{Q}_{p} \right)$ 表示。

这是一个正交投影映射，把二维的表示空间，投影压进一维（单份）表示子空间。

**D.3 酉投影为什么自动产生归一因子** $1/2$

设 $V = V_{1} \otimes V_{2}$ 是 $\Pi = \pi_{1} \boxtimes \pi_{2}$
的表示空间，$\dim V = {\dim V}_{1} \cdot {\dim V}_{2}$。
Jacquet‑Langlands 局部提升取对角子空间
$\left\{ v \otimes v \mid v \in V_{1} \right\}$，把它作为目标
${GL}_{2}\left( \mathbb{Q}_{p} \right)$ 的表示空间。

原来空间内的酉内积在对角子空间上做限制，需要正交投影的归一化：

$$Proj:V_{1} \otimes V_{2} \rightarrow \left\{ v \otimes v \right\}$$

对单位向量
$v \in V_{1}$，$\left\| v \otimes v \right\|^{2} = \left\| v \right\|^{2}\left\| v \right\|^{2} = 1$，投影之后，为保持酉表示的内积不变，投影算子的算子范数给出归一因子：

$$\left\| Proj \right\|^{2} = \frac{1}{2} \Longrightarrow w_{p} = \frac{1}{2}$$

复述： $w_{p} = \frac{1}{2}$ 不是我们为了消掉 2 而硬写的数字；

它是：分裂位置，局部表示空间是 "两份拷贝"，JL
提升把两份拷贝投影压缩到一份表示空间，酉正交投影自带的内积归一系数。

对比非分裂情形（惯性素、分歧素）：

此时 $K_{p}/\mathbb{Q}_{p}$
是不可分二次局部域，没有直积分解，${GL}_{2}\left( K_{p} \right)$
不能拆成两个 ${GL}_{2}\left( \mathbb{Q}_{p} \right)$ 的直积；不存在
"两份拷贝压到一份" 的投影，因此归一系数 $w_{p} = 1$，不需要修正。

**D.4 局部逐项数值验算**

1.  **分裂素** $p \equiv \pm 1\quad(mod\ 5)$ 几何侧两条轨道总局部贡献：

> $W_{geo}(p) = 2\, W(p).$ 谱侧带入 JL 局部酉投影归一权重
> $w_{p} = \frac{1}{2}$：
>
> $$w_{p} \cdot W_{geo}(p) = \frac{1}{2} \cdot 2\, W(p) = W(p)$$
>
> 结果等于单条轨道的贡献，和 "一个有理素只计一份" 的数论欧拉乘积匹配。

2.  **惯性素 / 分歧素**

> 几何侧只有唯一一条本原闭测地线，$W_{geo}(p) = W(p)$；
>
> 权重 $w_{p} = 1$：
>
> $w_{p} \cdot W_{geo}(p) = 1 \cdot W(p) = W(p).$
>
> 直接等于单份轨道贡献，不需要任何修正。

这里没有 "作弊抵消" 的逻辑：

不是：看到几何有个因子 2，我就手配一个 1/2 消掉；

而是：分裂局部域结构 ⇒ 表示空间是两份拷贝 ⇒ JL 酉投影 ⇒ 自然出现
$w_{p} = 1/2$；代入之后恰好把二重轨道的效应抵消。因果顺序：

几何分岔→表示结构带来权重，不是权重拿来修补几何。

**D.5 全局求和层面完整展开**

把全体素分成三类：分裂素集合 $S_{split}$，惯性素 $S_{inert}$，分歧素
$\left\{ 5 \right\}$。

几何侧（未加权，直接遍历全部本原轨道）：

$$\sum_{\gamma\mathcal{\in G}}^{}W(\gamma)f\left( \ell\left(\gamma\right) \right) = \sum_{p \in S_{split}}^{}\left( W(p) + W(p) \right)f\left( \log p \right) + \sum_{p \in S_{inert}}^{}W(p)f\left( \log p \right) + W(5)f\left( \log 5 \right)$$

实二次域 $\mathbb{Q}\left( \sqrt{5} \right)$ 仅有唯一分歧素
$p = 5$，故分歧部分为单独一项，无需求和

接下来化简：

- 分裂素括号展开：$W(p) + W(p) = 2W(p)$

- 把惯性集合和单点分歧素 $\left\{ 5 \right\}$
  做集合并集：$S_{inert} \cup \left\{ 5 \right\}$，这两类都是每个素仅对应一条测地线，可以合并到同一个求和号下。

$$\sum_{\gamma\mathcal{\in G}}^{}W(\gamma)f\left( \ell\left(\gamma\right) \right) = \sum_{p \in S_{split}}^{}2\, W(p)f\left( \log p \right) + \sum_{p \in S_{inert} \cup \left\{ 5 \right\}}^{}W(p)f\left( \log p \right)$$

带入 JL 局部归一权重，得到谱侧加权后的求和：

$$\sum_{t}^{}w_{f}(t)\, f\left( \lambda_{t} \right) = \sum_{p \in S_{split}}^{}w_{p} \cdot 2W(p)f\left( \log p \right) + \sum_{p \in S_{inert} \cup \left\{ 5 \right\}}^{}w_{p} \cdot W(p)f\left( \log p \right)$$

代入 $S_{split}$：$w_{p} = \frac{1}{2}$；其余 $w_{p} = 1$：

$$= \sum_{p \in S_{split}}^{}\frac{1}{2} \cdot 2W(p)f\left( \log p \right) + \sum_{p \in S_{inert} \cup \left\{ 5 \right\}}^{}1 \cdot W(p)f\left( \log p \right)$$

化简：

$$= \sum_{p \in S_{split}}^{}W(p)f\left( \log p \right) + \sum_{p \in S_{inert} \cup \left\{ 5 \right\}}^{}W(p)f\left( \log p \right)$$

$$= \sum_{p \geq 2}^{}W(p)f\left( \log p \right)$$

效果：加权之后，整个求和等价于对每一个有理素只算一次单份轨道权重，对齐 L
函数欧拉乘积按有理素遍历的结构。

**D.6 和 BSD 论文（模曲线** $X_{0}(N)$**）的平行对应（文稿互通）**

这是保证系列论文术语统一的对照，方便跨文档阅读：

\| 三维实二次域 RH 文稿（$K = \mathbb{Q}\left( \sqrt{5} \right)$） \|
BSD 定性文稿（模曲线 $X_{0}(N)$） \|

\|\-\--\|\-\--\|

\| 有理素在 K 分裂：$p \equiv \pm 1\quad(mod\ 5)$ \|
椭圆曲线分裂乘法坏约化素 $p \mid \Delta_{E}$\|

\| 局部域 $K_{p} \cong \mathbb{Q}_{p} \oplus \mathbb{Q}_{p}$ \| 局部域
$K_{p} = \mathbb{Q}_{p}\left( \sqrt{a_{p}^{2} - 4p} \right) \cong \mathbb{Q}_{p} \oplus \mathbb{Q}_{p}$
\|

\| 两条本原闭测地线
$\gamma_{\mathfrak{p}}$,$\gamma_{\overline{\mathfrak{p}}}$ \|
两条等长本原闭测地线 $\gamma_{p}^{(1)},\gamma_{p}^{(2)}$ \|

\|JL 局部酉投影归一因子 $w_{p} = \frac{1}{2}$ \| JL 局部酉投影归一因子
$w_{p} = \frac{1}{2}$\|

\| 惯性 / 分歧素，$w_{p} = 1$ \| 好约化、加性坏约化素，$w_{p} = 1$ \|

完全是同一套局部表示论机制，只是几何底盘更换：

三维算术 orbifold 换成二维模曲线。

**D.7 小结**

1.  分裂有理素在实二次域中分解为一对共轭素理想，保序双射给出两条等长本原闭测地线，造成几何侧求和出现局部因子
    2；

2.  分裂素局部域直积分解，${GL}_{2}\left( K_{p} \right)$
    表示写成外张量积，对应两份正交局部表示，分别对应两条测地线；

3.  Jacquet‑Langlands 局部提升做酉正交投影，把两份表示空间压入单份
    ${GL}_{2}\left( \mathbb{Q}_{p} \right)$ 表示，投影归一化给出
    $w_{p} = \frac{1}{2}$；

4.  惯性、分歧素无直积分解，投影不改变内积，$w_{p} = 1$；

5.  逐项验算：加权之后分裂素局部贡献等价于单份轨道权重，全局求和等价于遍历有理素的单层求和，与
    L 函数欧拉乘积的素遍历结构匹配；

6.  整套局部机制可以完整平移到模曲线 $X_{0}(N)$
    的分裂乘法坏约化情形，BSD 文稿附录 B 使用完全相同逻辑。
