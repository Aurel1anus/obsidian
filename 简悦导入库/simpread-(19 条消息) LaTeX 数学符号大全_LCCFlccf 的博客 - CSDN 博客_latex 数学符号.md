> 本文由 [简悦 SimpRead](http://ksria.com/simpread/) 转码， 原文地址 [blog.csdn.net](https://blog.csdn.net/LCCFlccf/article/details/89643585)

本篇博文介绍一些常用的 [LaTeX](https://so.csdn.net/so/search?q=LaTeX&spm=1001.2101.3001.7020) 符号，方便使用时查询。  

### 文章目录

*   *   *   *   *   [1. 操作符](#####1_2)
                *   [2. 关系符](#2_22)
                *   [3. 希腊字母](#3_52)
                *   *   [小写](#_53)
                    *   [大写](#_64)
                    *   [加粗](#_70)
                    *   [空心字母](#_76)
                *   [4. 箭头](#4_81)
                *   [5. 点](#5_104)
                *   [6. 上标](#6_111)
                *   [7. 其他](#7_128)
                *   [8. 命令符](#8_147)
                *   [9. 跨行或跨列的符号:](#9_164)
                *   [换行符号 '\\\\' 与空格符号'\quad'](#___quad_190)

##### 1. 操作符

<table><thead><tr><th>Symbol</th><th>Command</th><th>Symbol</th><th>Command</th><th>Symbol</th><th>Command</th></tr></thead><tbody><tr><td>± \pm ±</td><td>\pm</td><td>∓ \mp ∓</td><td>\mp</td><td>× \times ×</td><td>\times</td></tr><tr><td>÷ \div ÷</td><td>\div</td><td>⋅ \cdot ⋅</td><td>\cdot</td><td>∗ \ast ∗</td><td>\ast</td></tr><tr><td>⋆ \star ⋆</td><td>\star</td><td>† \dagger †</td><td>\dagger</td><td>‡ \ddagger ‡</td><td>\ddagger</td></tr><tr><td>⨿ \amalg ⨿</td><td>\amalg</td><td>∩ \cap ∩</td><td>\cap</td><td>∪ \cup ∪</td><td>\cup</td></tr><tr><td>⊎ \uplus ⊎</td><td>\uplus</td><td>⊓ \sqcap ⊓</td><td>\sqcap</td><td>⊔ \sqcup ⊔</td><td>\sqcup</td></tr><tr><td>∨ \vee ∨</td><td>\vee</td><td>∧ \wedge ∧</td><td>\wedge</td><td>⊕ \oplus ⊕</td><td>\oplus</td></tr><tr><td>⊖ \ominus ⊖</td><td>\ominus</td><td>⊗ \otimes ⊗</td><td>\otimes</td><td>∘ \circ ∘</td><td>\circ</td></tr><tr><td>∙ \bullet ∙</td><td>\bullet</td><td>⋄ \diamond ⋄</td><td>\diamond</td><td>⊲ \lhd ⊲</td><td>\lhd</td></tr><tr><td>⊳ \rhd ⊳</td><td>\rhd</td><td>⊴ \unlhd ⊴</td><td>\unlhd</td><td>⊵ \unrhd ⊵</td><td>\unrhd</td></tr><tr><td>⊘ \oslash ⊘</td><td>\oslash</td><td>⊙ \odot ⊙</td><td>\odot</td><td>◯ \bigcirc ◯</td><td>\bigcirc</td></tr><tr><td>◃ \triangleleft ◃</td><td>\triangleleft</td><td>◊ \Diamond ◊</td><td>\Diamond</td><td>△ \bigtriangleup △</td><td>\bigtriangleup</td></tr><tr><td>▽ \bigtriangledown ▽</td><td>\bigtriangledown</td><td>□ \Box □</td><td>\Box</td><td>▹ \triangleright ▹</td><td>\triangleright</td></tr><tr><td>$\setminus $</td><td>\setminus</td><td>≀ \wr ≀</td><td>\wr</td><td>x \sqrt{x} x <svg width="400em" height="1.08em" viewBox="0 0 400000 1080" preserveAspectRatio="xMinYMin slice"><path d="M95,702c-2.7,0,-7.17,-2.7,-13.5,-8c-5.8,-5.3,-9.5,
-10,-9.5,-14c0,-2,0.3,-3.3,1,-4c1.3,-2.7,23.83,-20.7,67.5,-54c44.2,-33.3,65.8,
-50.3,66.5,-51c1.3,-1.3,3,-2,5,-2c4.7,0,8.7,3.3,12,10s173,378,173,378c0.7,0,
35.3,-71,104,-213c68.7,-142,137.5,-285,206.5,-429c69,-144,104.5,-217.7,106.5,
-221c5.3,-9.3,12,-14,20,-14H400000v40H845.2724s-225.272,467,-225.272,467
s-235,486,-235,486c-2.7,4.7,-9,7,-19,7c-6,0,-10,-1,-12,-3s-194,-422,-194,-422
s-65,47,-65,47z M834 80H400000v40H845z"></path></svg>​</td><td>\sqrt{x}</td></tr><tr><td>x ∘ x^{\circ} x∘</td><td>x^{\circ}</td><td>▽ \triangledown ▽</td><td>\triangledown</td><td>x n \sqrt[n]{x} nx <svg width="400em" height="1.08em" viewBox="0 0 400000 1080" preserveAspectRatio="xMinYMin slice"><path d="M95,702c-2.7,0,-7.17,-2.7,-13.5,-8c-5.8,-5.3,-9.5,
-10,-9.5,-14c0,-2,0.3,-3.3,1,-4c1.3,-2.7,23.83,-20.7,67.5,-54c44.2,-33.3,65.8,
-50.3,66.5,-51c1.3,-1.3,3,-2,5,-2c4.7,0,8.7,3.3,12,10s173,378,173,378c0.7,0,
35.3,-71,104,-213c68.7,-142,137.5,-285,206.5,-429c69,-144,104.5,-217.7,106.5,
-221c5.3,-9.3,12,-14,20,-14H400000v40H845.2724s-225.272,467,-225.272,467
s-235,486,-235,486c-2.7,4.7,-9,7,-19,7c-6,0,-10,-1,-12,-3s-194,-422,-194,-422
s-65,47,-65,47z M834 80H400000v40H845z"></path></svg>​</td><td>\sqrt[n]{x}</td></tr><tr><td>a x a^x ax</td><td>a^x</td><td>a x y z a^{xyz} axyz</td><td>a^{xyz}</td><td></td><td></td></tr></tbody></table>

##### 2. 关系符

<table><thead><tr><th>Symbol</th><th>Command</th><th>Symbol</th><th>Command</th><th>Symbol</th><th>Command</th></tr></thead><tbody><tr><td>≤ \le ≤</td><td>\le</td><td>≥ \ge ≥</td><td>\ge</td><td>≠ \neq ​=</td><td>\neq</td></tr><tr><td>∼ \sim ∼</td><td>\sim</td><td>≪ \ll ≪</td><td>\ll</td><td>≫ \gg ≫</td><td>\gg</td></tr><tr><td>≐ \doteq ≐</td><td>\doteq</td><td>≃ \simeq ≃</td><td>\simeq</td><td>⊂ \subset ⊂</td><td>\subset</td></tr><tr><td>⊃ \supset ⊃</td><td>\supset</td><td>≈ \approx ≈</td><td>\approx</td><td>≍ \asymp ≍</td><td>\asymp</td></tr><tr><td>⊆ \subseteq ⊆</td><td>\subseteq</td><td>⊇ \supseteq ⊇</td><td>\supseteq</td><td>≅ \cong ≅</td><td>\cong</td></tr><tr><td>⌣ \smile ⌣</td><td>\smile</td><td>⊏ \sqsubset ⊏</td><td>\sqsubset</td><td>⊐ \sqsupset ⊐</td><td>\sqsupset</td></tr><tr><td>≡ \equiv ≡</td><td>\equiv</td><td>⌢ \frown ⌢</td><td>\frown</td><td>⊑ \sqsubseteq ⊑</td><td>\sqsubseteq</td></tr><tr><td>⊒ \sqsupseteq ⊒</td><td>\sqsupseteq</td><td>∝ \propto ∝</td><td>\propto</td><td>⋈ \bowtie ⋈</td><td>\bowtie</td></tr><tr><td>∈ \in ∈</td><td>\in</td><td>∋ \ni ∋</td><td>\ni</td><td>≺ \prec ≺</td><td>\prec</td></tr><tr><td>≻ \succ ≻</td><td>\succ</td><td>⊢ \vdash ⊢</td><td>\vdash</td><td>⊣ \dashv ⊣</td><td>\dashv</td></tr><tr><td>⪯ \preceq ⪯</td><td>\preceq</td><td>⪰ \succeq ⪰</td><td>\succeq</td><td>⊨ \models ⊨</td><td>\models</td></tr><tr><td>⊥ \perp ⊥</td><td>\perp</td><td>∥ \parallel ∥</td><td>\parallel</td><td></td><td></td></tr><tr><td>∣ \mid ∣</td><td>\mid</td><td>≏ \bumpeq ≏</td><td>\bumpeq</td><td>\</td><td></td></tr></tbody></table>

只要将 not 放在符号前面或者在 \ 和单词之间插入一个 n ，就可以形成许多这些关系的否定形式，这里有一些例子，加上一些其他的否定，它也适用于许多其他的。

<table><thead><tr><th>Symbol</th><th>Command</th><th>Symbol</th><th>Command</th><th>Symbol</th><th>Command</th></tr></thead><tbody><tr><td>∤ \nmid ∤</td><td>\nmid</td><td>≰ \nleq ≰</td><td>\nleq</td><td>≱ \ngeq ≱</td><td>\ngeq</td></tr><tr><td>≁ \nsim ≁</td><td>\nsim</td><td>≆ \ncong ≆</td><td>\ncong</td><td>∦ \nparallel ∦</td><td>\nparallel</td></tr><tr><td>&lt;̸ \not&lt; ​&lt;</td><td>\not&lt;</td><td>&gt;̸ \not&gt; ​&gt;</td><td>\not&gt;</td><td>≠ \not= ​=</td><td>\not= or \neq</td></tr><tr><td>≰ \not\le ​≤</td><td>\not\le</td><td>≱ \not\ge ​≥</td><td>\not\ge</td><td>≁ \not\sim ​∼</td><td>\not\sim</td></tr><tr><td>≉ \not \approx ​≈</td><td>\not\approx</td><td>≇ \not\cong ​≅</td><td>\not\cong</td><td>≢ \not\equiv ​≡</td><td>\not\equiv</td></tr><tr><td>∦ \not\parallel ​∥</td><td>\not\parallel</td><td>≮ \nless ≮</td><td>\nless</td><td>≯ \ngtr ≯</td><td>\ngtr</td></tr><tr><td>⪇ \lneq ⪇</td><td>\lneq</td><td>⪈ \gneq ⪈</td><td>\gneq</td><td>⋦ \lnsim ⋦</td><td>\lnsim</td></tr><tr><td>≨ \lneqq ≨</td><td>\lneqq</td><td>≩ \gneqq ≩</td><td>\gneqq</td><td></td><td></td></tr></tbody></table>

##### 3. 希腊字母

###### 小写

<table><thead><tr><th>Symbol</th><th>Command</th><th>Symbol</th><th>Command</th><th>Symbol</th><th>Command</th><th>Symbol</th><th>Command</th></tr></thead><tbody><tr><td>α \alpha α</td><td>\alpha</td><td>β \beta β</td><td>\beta</td><td>γ \gamma γ</td><td>\gamma</td><td>δ \delta δ</td><td>\delta</td></tr><tr><td>ϵ \epsilon ϵ</td><td>\epsilon</td><td>ε \varepsilon ε</td><td>\varepsilon</td><td>ζ \zeta ζ</td><td>\zeta</td><td>η \eta η</td><td>\eta</td></tr><tr><td>θ \theta θ</td><td>\theta</td><td>ϑ \vartheta ϑ</td><td>\vartheta</td><td>ι \iota ι</td><td>\iota</td><td>κ \kappa κ</td><td>\kappa</td></tr><tr><td>λ \lambda λ</td><td>\lambda</td><td>μ \mu μ</td><td>\mu</td><td>ν \nu ν</td><td>\nu</td><td>ξ \xi ξ</td><td>\xi</td></tr><tr><td>π \pi π</td><td>\pi</td><td>ϖ \varpi ϖ</td><td>\varpi</td><td>ρ \rho ρ</td><td>\rho</td><td>ϱ \varrho ϱ</td><td>\varrho</td></tr><tr><td>σ \sigma σ</td><td>\sigma</td><td>ς \varsigma ς</td><td>\varsigma</td><td>τ \tau τ</td><td>\tau</td><td>υ \upsilon υ</td><td>\upsilon</td></tr><tr><td>ϕ \phi ϕ</td><td>\phi</td><td>φ \varphi φ</td><td>\varphi</td><td>χ \chi χ</td><td>\chi</td><td>ψ \psi ψ</td><td>\psi</td></tr><tr><td>ω \omega ω</td><td>\omega</td><td></td><td></td><td></td><td></td><td></td><td></td></tr></tbody></table>

###### 大写

<table><thead><tr><th>Symbol</th><th>Command</th><th>Symbol</th><th>Command</th><th>Symbol</th><th>Command</th><th>Symbol</th><th>Command</th></tr></thead><tbody><tr><td>Γ \Gamma Γ</td><td>\Gamma</td><td>Δ \Delta Δ</td><td>\Delta</td><td>Θ \Theta Θ</td><td>\Theta</td><td>Λ \Lambda Λ</td><td>\Lambda</td></tr><tr><td>Ξ \Xi Ξ</td><td>\Xi</td><td>Π \Pi Π</td><td>\Pi</td><td>Σ \Sigma Σ</td><td>\Sigma</td><td>Υ \Upsilon Υ</td><td>\Upsilon</td></tr><tr><td>Φ \Phi Φ</td><td>\Phi</td><td>Ψ \Psi Ψ</td><td>\Psi</td><td>Ω \Omega Ω</td><td>\Omega</td><td>∇ \nabla ∇</td><td>\nabla</td></tr></tbody></table>

###### 加粗

在公式中的字母加粗：

<table><thead><tr><th>Symbol</th><th>Command</th></tr></thead><tbody><tr><td>m \bold m m</td><td>$ \bold m $</td></tr></tbody></table>

###### 空心字母

<table><thead><tr><th>Symbol</th><th>Command</th></tr></thead><tbody><tr><td>M \mathbb{M} M</td><td>$ \mathbb{M} $</td></tr><tr><td>R \mathbb{R} R</td><td>$ \mathbb{R} $</td></tr></tbody></table>

##### 4. 箭头

<table><thead><tr><th>Symbol</th><th>Command</th><th>Symbol</th><th>Command</th></tr></thead><tbody><tr><td>← \gets ←</td><td>\gets</td><td>→ \to →</td><td>\to</td></tr><tr><td>← \leftarrow ←</td><td>\leftarrow</td><td>⇐ \Leftarrow ⇐</td><td>\Leftarrow</td></tr><tr><td>→ \rightarrow →</td><td>\rightarrow</td><td>⇒ \Rightarrow ⇒</td><td>\Rightarrow</td></tr><tr><td>↔ \leftrightarrow ↔</td><td>\leftrightarrow</td><td>⇔ \Leftrightarrow ⇔</td><td>\Leftrightarrow</td></tr><tr><td>↦ \mapsto ↦</td><td>\mapsto</td><td>↩ \hookleftarrow ↩</td><td>\hookleftarrow</td></tr><tr><td>↼ \leftharpoonup ↼</td><td>\leftharpoonup</td><td>↽ \leftharpoondown ↽</td><td>\leftharpoondown</td></tr><tr><td>⇌ \rightleftharpoons ⇌</td><td>\rightleftharpoons</td><td>⟵ \longleftarrow ⟵</td><td>\longleftarrow</td></tr><tr><td>⟸ \Longleftarrow ⟸</td><td>\Longleftarrow</td><td>⟶ \longrightarrow ⟶</td><td>\longrightarrow</td></tr><tr><td>⟹ \Longrightarrow ⟹</td><td>\Longrightarrow</td><td>⟷ \longleftrightarrow ⟷</td><td>\longleftrightarrow</td></tr><tr><td>⟺ \Longleftrightarrow ⟺</td><td>\Longleftrightarrow</td><td>⟼ \longmapsto ⟼</td><td>\longmapsto</td></tr><tr><td>↪ \hookrightarrow ↪</td><td>\hookrightarrow</td><td>⇀ \rightharpoonup ⇀</td><td>\rightharpoonup</td></tr><tr><td>⇁ \rightharpoondown ⇁</td><td>\rightharpoondown</td><td>⇝ \leadsto ⇝</td><td>\leadsto</td></tr><tr><td>↑ \uparrow ↑</td><td>\uparrow</td><td>⇑ \Uparrow ⇑</td><td>\Uparrow</td></tr><tr><td>↓ \downarrow ↓</td><td>\downarrow</td><td>⇓ \Downarrow ⇓</td><td>\Downarrow</td></tr><tr><td>↕ \updownarrow ↕</td><td>\updownarrow</td><td>⇕ \Updownarrow ⇕</td><td>\Updownarrow</td></tr><tr><td>↗ \nearrow ↗</td><td>\nearrow</td><td>↘ \searrow ↘</td><td>\searrow</td></tr><tr><td>↙ \swarrow ↙</td><td>\swarrow</td><td>↖ \nwarrow ↖</td><td>\nwarrow</td></tr></tbody></table>

(对于不喜欢键入长串字母的人，\iff 和 \ implies 可以分别替代 \ Longleftrightarrow 和 \ longrighttarrow)

##### 5. 点

<table><thead><tr><th>Symbol</th><th>Command</th><th>Symbol</th><th>Command</th></tr></thead><tbody><tr><td>⋅ \cdot ⋅</td><td>\cdot</td><td>⋮ \vdots ⋮</td><td>\vdots</td></tr><tr><td>… \dots …</td><td>\dots</td><td>⋱ \ddots ⋱</td><td>\ddots</td></tr><tr><td>⋯ \cdots ⋯</td><td>\cdots</td><td>KaTeX parse error: Undefined control sequence: \iddots at position 1: \̲i̲d̲d̲o̲t̲s̲</td><td>\iddots</td></tr></tbody></table>

##### 6. 上标

<table><thead><tr><th>Symbol</th><th>Command</th><th>Symbol</th><th>Command</th><th>Symbol</th><th>Command</th></tr></thead><tbody><tr><td>x ^ \hat{x} x^</td><td>\hat{x}</td><td>x ˇ \check{x} xˇ</td><td>\check{x}</td><td>x ˙ \dot{x} x˙</td><td>\dot{x}</td></tr><tr><td>x ˘ \breve{x} x˘</td><td>\breve{x}</td><td>x ˊ \acute{x} xˊ</td><td>\acute{x}</td><td>x ¨ \ddot{x} x¨</td><td>\ddot{x}</td></tr><tr><td>x ˋ \grave{x} xˋ</td><td>\grave{x}</td><td>x ~ \tilde{x} x~</td><td>\tilde{x}</td><td>x ˚ \mathring{x} x˚</td><td>\mathring{x}</td></tr><tr><td>x ˉ \bar{x} xˉ</td><td>\bar{x}</td><td>x ⃗ \vec{x} x<svg width="0.471em" height="0.714em" style="width:0.471em" viewBox="0 0 471 714" preserveAspectRatio="xMinYMin"><path d="M377 20c0-5.333 1.833-10 5.5-14S391 0 397 0c4.667 0 8.667 1.667 12 5
3.333 2.667 6.667 9 10 19 6.667 24.667 20.333 43.667 41 57 7.333 4.667 11
10.667 11 18 0 6-1 10-3 12s-6.667 5-14 9c-28.667 14.667-53.667 35.667-75 63
-1.333 1.333-3.167 3.5-5.5 6.5s-4 4.833-5 5.5c-1 .667-2.5 1.333-4.5 2s-4.333 1
-7 1c-4.667 0-9.167-1.833-13.5-5.5S337 184 337 178c0-12.667 15.667-32.333 47-59
H213l-171-1c-8.667-6-13-12.333-13-19 0-4.667 4.333-11.333 13-20h359
c-16-25.333-24-45-24-59z"></path></svg></td><td>\vec{x}</td><td></td><td></td></tr></tbody></table>

当对 i 和 j 应用上标时，可以使用 \ imath 和 \ jmath 来防止点干扰上标:

<table><thead><tr><th>Symbol</th><th>Command</th><th>Symbol</th><th>Command</th></tr></thead><tbody><tr><td>ȷ ⃗ \vec{\jmath} ȷ <svg width="0.471em" height="0.714em" style="width:0.471em" viewBox="0 0 471 714" preserveAspectRatio="xMinYMin"><path d="M377 20c0-5.333 1.833-10 5.5-14S391 0 397 0c4.667 0 8.667 1.667 12 5
3.333 2.667 6.667 9 10 19 6.667 24.667 20.333 43.667 41 57 7.333 4.667 11
10.667 11 18 0 6-1 10-3 12s-6.667 5-14 9c-28.667 14.667-53.667 35.667-75 63
-1.333 1.333-3.167 3.5-5.5 6.5s-4 4.833-5 5.5c-1 .667-2.5 1.333-4.5 2s-4.333 1
-7 1c-4.667 0-9.167-1.833-13.5-5.5S337 184 337 178c0-12.667 15.667-32.333 47-59
H213l-171-1c-8.667-6-13-12.333-13-19 0-4.667 4.333-11.333 13-20h359
c-16-25.333-24-45-24-59z"></path></svg>​</td><td>\vec{\jmath}</td><td>ı ~ \tilde{\imath} ı~</td><td>\tilde{\imath}</td></tr></tbody></table>

\tilde 和 \ hat 有很宽的版本，可以让你强调一个表达:

<table><thead><tr><th>Symbol</th><th>Command</th><th>Symbol</th><th>Command</th></tr></thead><tbody><tr><td>7 + x ^ \widehat{7+x} 7+x <svg width="100%" height="0.3em" viewBox="0 0 2364 300" preserveAspectRatio="none"><path d="M1181 0h2l1171 176c6 0 10 5 10 11l-2 23c-1 6-5 10
-11 10h-1L1182 67 15 220h-1c-6 0-10-4-11-10l-2-23c-1-6 4-11 10-11z"></path></svg>​</td><td>\widehat{7+x}</td><td>a b c ~ \widetilde{abc} abc<svg width="100%" height="0.286em" viewBox="0 0 1033 286" preserveAspectRatio="none"><path d="M344 55.266c-142 0-300.638 81.316-311.5 86.418
-8.01 3.762-22.5 10.91-23.5 5.562L1 120c-1-2-1-3-1-4 0-5 3-9 8-10l18.4-9C160.9
 31.9 283 0 358 0c148 0 188 122 331 122s314-97 326-97c4 0 8 2 10 7l7 21.114
c1 2.14 1 3.21 1 4.28 0 5.347-3 9.626-7 10.696l-22.3 12.622C852.6 158.372 751
 181.476 676 181.476c-149 0-189-126.21-332-126.21z"></path></svg></td><td>\widetilde{abc}</td></tr></tbody></table>

##### 7. 其他

<table><thead><tr><th>Symbol</th><th>Command</th><th>Symbol</th><th>Command</th><th>Symbol</th><th>Command</th></tr></thead><tbody><tr><td>∞ \infty ∞</td><td>\infty</td><td>△ \triangle △</td><td>\triangle</td><td>∠ \angle ∠</td><td>\angle</td></tr><tr><td>ℵ \aleph ℵ</td><td>\aleph</td><td>ℏ \hbar ℏ</td><td>\hbar</td><td>ı \imath ı</td><td>\imath</td></tr><tr><td>ȷ \jmath ȷ</td><td>\jmath</td><td>ℓ \ell ℓ</td><td>\ell</td><td>℘ \wp ℘</td><td>\wp</td></tr><tr><td>ℜ \Re ℜ</td><td>\Re</td><td>ℑ \Im ℑ</td><td>\Im</td><td>℧ \mho ℧</td><td>\mho</td></tr><tr><td>′ \prime ′</td><td>\prime</td><td>∅ \emptyset ∅</td><td>\emptyset</td><td>∇ \nabla ∇</td><td>\nabla</td></tr><tr><td>√ \surd √</td><td>\surd</td><td>∂ \partial ∂</td><td>\partial</td><td>⊤ \top ⊤</td><td>\top</td></tr><tr><td>⊥ \bot ⊥</td><td>\bot</td><td>⊢ \vdash ⊢</td><td>\vdash</td><td>⊣ \dashv ⊣</td><td>\dashv</td></tr><tr><td>∀ \forall ∀</td><td>\forall</td><td>∃ \exists ∃</td><td>\exists</td><td>¬ \neg ¬</td><td>\neg</td></tr><tr><td>♭ \flat ♭</td><td>\flat</td><td>♮ \natural ♮</td><td>\natural</td><td>♯ \sharp ♯</td><td>\sharp</td></tr><tr><td>\ \backslash \</td><td>\backslash</td><td>□ \Box □</td><td>\Box</td><td>◊ \Diamond ◊</td><td>\Diamond</td></tr><tr><td>♣ \clubsuit ♣</td><td>\clubsuit</td><td>♢ \diamondsuit ♢</td><td>\diamondsuit</td><td>♡ \heartsuit ♡</td><td>\heartsuit</td></tr><tr><td>♠ \spadesuit ♠</td><td>\spadesuit</td><td>⋈ \Join ⋈</td><td>\Join</td><td>■ \blacksquare ■</td><td>\blacksquare</td></tr><tr><td>✓ \checkmark ✓</td><td>\checkmark</td><td>R \mathbb{R} R</td><td>\mathbb{R}</td><td>© \copyright c◯</td><td>\copyright</td></tr><tr><td>£ \pounds £</td><td>\pounds</td><td>□ \square □</td><td>\square</td><td>∪ \cup ∪</td><td>\cup</td></tr><tr><td>★ \bigstar ★</td><td>\bigstar</td><td>∈ \in ∈</td><td>\in</td><td></td><td></td></tr></tbody></table>

##### 8. 命令符

有些符号用于命令中，因此需要以特殊的方式处理它们。

<table><thead><tr><th>Symbol</th><th>Command</th><th>Symbol</th><th>Command</th><th>Symbol</th><th>Command</th><th>Symbol</th><th>Command</th></tr></thead><tbody><tr><td>\ \backslash \</td><td>\backslash</td><td>&amp; \&amp; &amp;</td><td>\&amp;</td><td>% \% %</td><td>\%</td><td># \# #</td><td>\#</td></tr><tr><td>_ \_ _</td><td>\_</td><td>{ \{ {</td><td>\{</td><td>} \} }</td><td>\}</td><td></td><td></td></tr></tbody></table>

您可能会注意到，如果使用其中任何一个来排版垂直较大的表达式，比如

(\frac{a}{x} )^2  
得到的表达式的括号的大小不对  
( a x ) 2 (\frac{a} {x} )^2 (xa​)2

如果我们把 \ left 和 \ right 放在相关的括号前，我们会得到一个更漂亮的表达式:  
\left(\frac{a}{x} \right)^2 会得到  
( a x ) 2 \left(\frac{a}{x} \right)^2 (xa​)2

##### 9. 跨行或跨列的符号:

<table><thead><tr><th>symbol</th><th>command</th></tr></thead><tbody><tr><td>{ x + y = 3 2 x + y = 5 \left\{<span class="MathJax MathJax_FullWidth" id="MathJax-Element-1-Frame" tabindex="0" data-mathml="<math xmlns=&quot;http://www.w3.org/1998/Math/MathML&quot; display=&quot;block&quot;><mtable columnalign=&quot;left&quot; rowspacing=&quot;4pt&quot; columnspacing=&quot;1em&quot;><mtr><mtd><mi>x</mi><mo>+</mo><mi>y</mi><mo>=</mo><mn>3</mn></mtd></mtr><mtr><mtd><mn>2</mn><mi>x</mi><mo>+</mo><mi>y</mi><mo>=</mo><mn>5</mn></mtd></mtr></mtable></math>" role="presentation" style="position: relative;"><nobr aria-hidden="true">x+y=32x+y=5</nobr><math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><mtable columnalign="left" rowspacing="4pt" columnspacing="1em"><mtr><mtd><mi>x</mi><mo>+</mo><mi>y</mi><mo>=</mo><mn>3</mn></mtd></mtr><mtr><mtd><mn>2</mn><mi>x</mi><mo>+</mo><mi>y</mi><mo>=</mo><mn>5</mn></mtd></mtr></mtable></math><script type="math/tex; mode=display" id="MathJax-Element-1">\begin{array}{l}x+y=3\\2x+y=5\end{array}</script>\right. {x+y=32x+y=5​</span></td><td>\left{<span class="MathJax" id="MathJax-Element-2-Frame" tabindex="0" data-mathml="<math xmlns=&quot;http://www.w3.org/1998/Math/MathML&quot; display=&quot;block&quot;><mtable columnalign=&quot;left&quot; rowspacing=&quot;4pt&quot; columnspacing=&quot;1em&quot;><mtr><mtd><mi>x</mi><mo>+</mo><mi>y</mi><mo>=</mo><mn>3</mn><mtext mathcolor=&quot;red&quot;>\2</mtext><mi>x</mi><mo>+</mo><mi>y</mi><mo>=</mo><mn>5</mn></mtd></mtr></mtable></math>" role="presentation" style="text-align: center; position: relative;"><nobr aria-hidden="true">x+y=3\2x+y=5</nobr><math xmlns="http://www.w3.org/1998/Math/MathML" display="block"><mtable columnalign="left" rowspacing="4pt" columnspacing="1em"><mtr><mtd><mi>x</mi><mo>+</mo><mi>y</mi><mo>=</mo><mn>3</mn><mtext mathcolor="red">\2</mtext><mi>x</mi><mo>+</mo><mi>y</mi><mo>=</mo><mn>5</mn></mtd></mtr></mtable></math><script type="math/tex; mode=display" id="MathJax-Element-2">\begin{array}{l}x+y=3\2x+y=5\end{array}</script>\right.</span></td></tr><tr><td>⌈ x y ⌉ \left\lceil\frac{x}{y}\right\rceil ⌈yx​⌉</td><td>\left\lceil\frac{x}{y}\right\rceil</td></tr><tr><td>⌊ x y ⌋ \left\lfloor\frac{x}{y}\right\rfloor ⌊yx​⌋</td><td>\left\lfloor\frac{x}{y}\right\rfloor</td></tr><tr><td>a 0 + a 1 + a 2 + ⋯ + a n ⏟ x \underbrace{a_0+a_1+a_2+\cdots+a_n}_{x} x <svg width="400em" height="0.548em" viewBox="0 0 400000 548" preserveAspectRatio="xMinYMin slice"><path d="M0 6l6-6h17c12.688 0 19.313.3 20 1 4 4 7.313 8.3 10 13
 35.313 51.3 80.813 93.8 136.5 127.5 55.688 33.7 117.188 55.8 184.5 66.5.688
 0 2 .3 4 1 18.688 2.7 76 4.3 172 5h399450v120H429l-6-1c-124.688-8-235-61.7
-331-161C60.687 138.7 32.312 99.3 7 54L0 41V6z"></path></svg><svg width="400em" height="0.548em" viewBox="0 0 400000 548" preserveAspectRatio="xMidYMin slice"><path d="M199572 214
c100.7 8.3 195.3 44 280 108 55.3 42 101.7 93 139 153l9 14c2.7-4 5.7-8.7 9-14
 53.3-86.7 123.7-153 211-199 66.7-36 137.3-56.3 212-62h199568v120H200432c-178.3
 11.7-311.7 78.3-403 201-6 8-9.7 12-11 12-.7.7-6.7 1-18 1s-17.3-.3-18-1c-1.3 0
-5-4-11-12-44.7-59.3-101.3-106.3-170-141s-145.3-54.3-229-60H0V214z"></path></svg><svg width="400em" height="0.548em" viewBox="0 0 400000 548" preserveAspectRatio="xMaxYMin slice"><path d="M399994 0l6 6v35l-6 11c-56 104-135.3 181.3-238 232-57.3
 28.7-117 45-179 50H-300V214h399897c43.3-7 81-15 113-26 100.7-33 179.7-91 237
-174 2.7-5 6-9 10-13 .7-1 7.3-1 20-1h17z"></path></svg>a0​+a1​+a2​+⋯+an​​​</td><td>\underbrace{a_0+a_1+a_2+\cdots+a_n}_{x}</td></tr><tr><td>a 0 + a 1 + a 2 + ⋯ + a n ⏞ x \overbrace{a_0+a_1+a_2+\cdots+a_n}^{x} a0​+a1​+a2​+⋯+an​ <svg width="400em" height="0.548em" viewBox="0 0 400000 548" preserveAspectRatio="xMinYMin slice"><path d="M6 548l-6-6v-35l6-11c56-104 135.3-181.3 238-232 57.3-28.7 117
-45 179-50h399577v120H403c-43.3 7-81 15-113 26-100.7 33-179.7 91-237 174-2.7
 5-6 9-10 13-.7 1-7.3 1-20 1H6z"></path></svg><svg width="400em" height="0.548em" viewBox="0 0 400000 548" preserveAspectRatio="xMidYMin slice"><path d="M200428 334
c-100.7-8.3-195.3-44-280-108-55.3-42-101.7-93-139-153l-9-14c-2.7 4-5.7 8.7-9 14
-53.3 86.7-123.7 153-211 199-66.7 36-137.3 56.3-212 62H0V214h199568c178.3-11.7
 311.7-78.3 403-201 6-8 9.7-12 11-12 .7-.7 6.7-1 18-1s17.3.3 18 1c1.3 0 5 4 11
 12 44.7 59.3 101.3 106.3 170 141s145.3 54.3 229 60h199572v120z"></path></svg><svg width="400em" height="0.548em" viewBox="0 0 400000 548" preserveAspectRatio="xMaxYMin slice"><path d="M400000 542l
-6 6h-17c-12.7 0-19.3-.3-20-1-4-4-7.3-8.3-10-13-35.3-51.3-80.8-93.8-136.5-127.5
s-117.2-55.8-184.5-66.5c-.7 0-2-.3-4-1-18.7-2.7-76-4.3-172-5H0V214h399571l6 1
c124.7 8 235 61.7 331 161 31.3 33.3 59.7 72.7 85 118l7 13v35z"></path></svg>​x​</td><td>\overbrace{a_0+a_1+a_2+\cdots+a_n}^{x}</td></tr><tr><td>arg ⁡ m a x 1 ≤ k ≤ n λ k λ k + 1 \arg \underset{1\leq k \leq n} {max} \frac{\lambda_k}{\lambda_{k+1}} arg1≤k≤nmax​λk+1​λk​​</td><td>\arg \underset{1\leq k \leq n} {max} \frac{\lambda_k}{\lambda_{k+1}}</td></tr></tbody></table>

\left 和 \ right 也可以用来调整下列符号的大小:

<table><thead><tr><th>Symbol</th><th>Command</th><th>Symbol</th><th>Command</th><th>Symbol</th><th>Command</th></tr></thead><tbody><tr><td>↑ \uparrow ↑</td><td>\uparrow</td><td>↓ \downarrow ↓</td><td>\downarrow</td><td>↕ \updownarrow ↕</td><td>\updownarrow</td></tr><tr><td>⇑ \Uparrow ⇑</td><td>\Uparrow</td><td>⇓ \Downarrow ⇓</td><td>\Downarrow</td><td>⇕ \Updownarrow ⇕</td><td>\Updownarrow</td></tr></tbody></table>

<table><thead><tr><th>Symbol</th><th>Command</th><th>Symbol</th><th>Command</th><th>Symbol</th><th>Command</th></tr></thead><tbody><tr><td>∑ \sum ∑</td><td>\sum</td><td>∫ \int ∫</td><td>\int</td><td>∮ \oint ∮</td><td>\oint</td></tr><tr><td>∏ \prod ∏</td><td>\prod</td><td>∐ \coprod ∐</td><td>\coprod</td><td>⋂ \bigcap ⋂</td><td>\bigcap</td></tr><tr><td>⋃ \bigcup ⋃</td><td>\bigcup</td><td>⨆ \bigsqcup ⨆</td><td>\bigsqcup</td><td>⋁ \bigvee ⋁</td><td>\bigvee</td></tr><tr><td>⋀ \bigwedge ⋀</td><td>\bigwedge</td><td>⨀ \bigodot ⨀</td><td>\bigodot</td><td>⨂ \bigotimes ⨂</td><td>\bigotimes</td></tr><tr><td>⨁ \bigoplus ⨁</td><td>\bigoplus</td><td>⨄ \biguplus ⨄</td><td>\biguplus</td><td></td><td></td></tr></tbody></table>

##### 换行符号 ’ \\’ 与空格符号’\quad’

<table><thead><tr><th>Symbol</th><th>Command</th></tr></thead><tbody><tr><td>a = 1 b = 2 a=1\\b=2 a=1b=2</td><td>$ a=1 \\ b=2 $</td></tr><tr><td>a b a \qquad b ab</td><td>$ a \qquad b $</td></tr><tr><td>a b a \quad b ab</td><td>$ a \quad b $</td></tr><tr><td>a &nbsp; b a \ b a&nbsp;b</td><td>$ a\ b $</td></tr><tr><td>a    b a \; b ab</td><td>$ a; b $</td></tr><tr><td>a   b a \, b ab</td><td>$ a\ b $</td></tr><tr><td>a b ab ab</td><td>$ ab $</td></tr><tr><td>a  ⁣ b a \! b ab</td><td>$ a! b $</td></tr></tbody></table>

参考：  
https://artofproblemsolving.com/wiki/index.php/LaTeX:Symbols  
https://artofproblemsolving.com/wiki/index.php/LaTeX:Commands