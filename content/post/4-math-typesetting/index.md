---
title: 数学排版
description: 使用 KaTeX 进行数学排版
slug: 4-math-typesetting
date: 2024-01-01 20:30:00+0000
math: true
---

Stack 内置了对使用 [KaTeX](https://katex.org/) 进行数学排版的支持

**默认情况下，它在整个站点上未启用，** 但您可以通过在前面添加 `math: true` 来为单个帖子启用它。或者，您可以通过将 `math = true` 添加到 `config.toml` 中的 `params.article` 部分来启用它

## 内联数学

这是一个内联数学表达式： $\varphi = \dfrac{1+\sqrt5}{2}= 1.6180339887…$

```markdown
$\varphi = \dfrac{1+\sqrt5}{2}= 1.6180339887…$
```

## 块数学

$$
    \varphi = 1+\frac{1} {1+\frac{1} {1+\frac{1} {1+\cdots} } } 
$$

```markdown
$$
    \varphi = 1+\frac{1} {1+\frac{1} {1+\frac{1} {1+\cdots} } } 
$$
```

$$
    f(x) = \int_{-\infty}^\infty\hat f(\xi)\,e^{2 \pi i \xi x}\,d\xi
$$

```markdown
$$
    f(x) = \int_{-\infty}^\infty\hat f(\xi)\,e^{2 \pi i \xi x}\,d\xi
$$
```