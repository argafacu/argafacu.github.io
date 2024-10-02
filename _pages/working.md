---
layout: archive
title: "Working Papers"
permalink: /working/
author_profile: true
---

### 2018 - 2024 
+ Automatic Debiased Machine Learning of Structural Parameters with General Conditional Moments (2024).
<dl style="margin-top: -10px;">
  <dd>
    <details>
      <summary>
        Abstract
      </summary>
This paper proposes a method for conducting inference on finite-dimensional parameters in models defined by a finite number of conditional moment restrictions (CMRs), with possibly different conditioning variables and endogenous regressors. CMRs are allowed to depend on non-parametric components, which might be flexibly modeled using Machine Learning tools, and non-linearly on finite-dimensional parameters. Inference is based on constructing locally robust/orthogonal/debiased moments, in a data-driven way, extending these to accommodate CMRs. Those moments are less affected by regularization bias, which is relevant to machine learning first steps and typically invalidates standard inference. The key step in this construction is the estimation of Orthogonal Instrumental Variables (OR-IVs)—"residualized" functions of the conditioning variables, which are then combined to obtain a debiased moment. Our strategy exploits the CMRs implied by the model in a general way and thus can be applied to a wide range of settings, where the construction of orthogonal moments has remained unexplored, including highly non-linear and complex settings with CMRs, prominent in economics. We argue that computing OR-IVs necessarily requires solving potentially complicated functional equations, which depend on unknown terms. However, by imposing an approximate sparsity condition, our method automatically finds the solutions to those equations using a Lasso-type program and can thus be implemented straightforwardly. Based on this, we introduce a GMM estimator of finite-dimensional parameters in a two-step framework. We derive theoretical guarantees for our construction of orthogonal moments and show √n-consistency and asymptotic normality of the introduced estimator. Our Monte Carlo experiments and an empirical application on estimating firm-level production functions and productivity measures highlight the importance of relying on inference methods like the one proposed.
    </details>
  </dd>
</dl>

+ [On the Existence and Information of Orthogonal Moments (2023)](https://arxiv.org/abs/2303.11418), joint with [Juan Carlos Escanciano.](https://sites.google.com/view/juancarlosescanciano/home) [Supplementary Appendix](https://drive.google.com/file/d/1X8gtzjNk1g1mZxBONcD3vbVMuBKHQJDC/view?usp=sharing)
<dl style="margin-top: -10px;">
  <dd>
    <details>
      <summary>
        Abstract
      </summary>
Locally Robust (LR)/Orthogonal/Debiased moments have proven useful with machine learning first steps, but their existence has not been investigated for general parameters. In this paper, we provide a necessary and sufficient condition, referred to as Restricted Local Non-surjectivity (RLN), for the existence of such orthogonal moments to conduct robust
inference on general parameters of interest in regular semiparametric models. In addition, we study when score-type tests based on orthogonal moments are locally informative at
the parametric rate. We demonstrate the utility of our general results by characterizing orthogonal moments in a class of models with unobserved heterogeneity (UH). Orthogonality
for general smooth functionals of the distribution of UH is also characterized. As a second major application, we find orthogonal moments for general conditional moments models,
including the fully saturated two stage least squares, heterogeneous parameters in treatment effects, sample selection models, and popular models of demand for differentiated
products. We apply our results to the Oregon Health Experiment to study heterogeneous treatment effects of Medicaid on different health outcomes.
    </details>
  </dd>
</dl>

