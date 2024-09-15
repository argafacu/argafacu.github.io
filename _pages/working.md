---
layout: archive
title: "Working Papers"
permalink: /working/
author_profile: true
---

### 2018 - 2024 
+ [Automatic Debiased Machine Learning of Structural Parameters with General Conditional Moments (2024).](https://drive.google.com/file/d/1DjzGPdIens-Wrpfc6JrvFUWu71lnj7zg/view?usp=sharing)
<dl style="margin-top: -10px;">
  <dd>
    <details>
      <summary>
        Abstract
      </summary>
This paper proposes a method for conducting inference on a finite-dimensional parameter in models defined by a finite number of conditional moment restrictions (CMRs), with possibly different conditioning variables and endogenous regressors. CMRs are allowed to depend on non-parametric components, which might be flexibly  modeled using Machine Learning tools, and non-linearly on finite-dimensional parameters. Inference is based on constructing locally robust/orthogonal/debiased moments, in a data-driven way, extending these to accommodate CMRs. Those moments are less affected by regularization bias, which is relevant to machine learning first steps and typically invalidates standard inference. The key step in this construction is the estimation of Orthogonal Instrumental Variables (OR-IVs)—"residualized" functions of the conditioning variables,  which are then combined to obtain a debiased moment. Our strategy exploits the CMRs implied by the model in a general way, and thus can be applied to a wide range of settings, where the construction of orthogonal moments has remained unexplored, including highly non-linear and complex settings with CMRs, prominent in economics.  We argue that computing OR-IVs necessarily require solving potentially complicated functional equations, which depends on unknown terms. However, by imposing an approximate sparsity condition, our method automatically finds the solutions to those equations using a Lasso-type program and thus can be implemented straightforwardly. Based on this, we introduce a GMM estimator of a finite-dimensional parameter in a two-step framework. We derive theoretical guarantees for our construction of orthogonal moments and show √n-consistency and asymptotic normality of the introduced estimator. Our Monte Carlo experiments and an empirical application on the estimation of firm-level production functions and productivity measures highlight the importance of relying on inference methods like the one proposed.
    </details>
  </dd>
</dl>

+ Compliance Machine Learning Estimator, joint with [Juan Carlos Escanciano.](https://sites.google.com/view/juancarlosescanciano/home) Draft coming soon.
<dl style="margin-top: -10px;">
  <dd>
    <details>
      <summary>
        Abstract
      </summary>
Methods relying on instrumental variables (IVs) are known to be useful for learning treatment effects in experiments where treatment randomization is not possible. Often, the researcher can use a large class of potentially valid IVs, but is there an <em>optimal</em> choice? If so, which one? In this paper, we argue that a measure of the "strength" of the instrument as predictor of the treatment, conditional on pre-treatment characteristics, leads to an estimator that enjoys three <em>key</em> properties: (1) local orthogonality, (2) identification of the parameter of interest under the minimal conditions, and (3) meaningful nonparametric interpretation in terms of conditional local treatment effects, even if defiers are not completely ruled out in the population. In the common situation where the treatment variable is binary, such strength is linked to the probability of complying with the treatment. Therefore, we name this estimator <em>Compliance Machine Learning Estimator (CML)</em>. If the researcher's criterion of optimality involves these three attributes, then CML is the optimal choice. We provide theoretical guarantees that support the use of off-the-shelf routines to conduct standard inference on CML, when machine learning tools are used to construct the IV. We study the relative performance of this estimator through a Monte Carlo exercise. Finally, we revisit the Oregon Health Insurance Experiment, analyzed by Finkelstein et al. (2012). We find that the use of machine learning and CML suggest larger positive effects on health care utilization than previously determined.
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

