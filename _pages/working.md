---
layout: archive
title: "Working Papers"
permalink: /working/
author_profile: true
---

### 2018 - 2024 
+ [Debiasing with General Conditional Moments and High-Dimensional First Stages (2024).](https://drive.google.com/file/d/1FcaENurMO6LjXsmTFH4ZA9l6okjgQiBZ/view?usp=sharing)
<dl style="margin-top: -10px;">
  <dd>
    <details>
      <summary>
        Abstract
      </summary>
This paper proposes a method to conduct inference on a finite-dimensional parameter in models defined by a finite number of conditional moment restrictions (CMRs), with possibly different conditioning variables and endogenous regressors. Those conditional moments are allowed to depend on non-parametric components, which might be modeled flexibly using Machine Learning tools. Inference is based on locally robust/orthogonal/debiased moments, extended to the case with CMRs. These moments are less affected by regularization bias, which is relevant to machine learning first steps and typically invalidates standard inference.  Under weak smoothness conditions, we exploit the CMRs implied by the model in a general way. Thus, our strategy can be applied uniformly in various contexts where the construction of orthogonal moments has not been explored, such as non-linear GMM settings, models with missing data, production functions at the firm level, dynamic discrete choice models, and many others. Our approach converts a given function of the conditioning variables into a valid instrument that yields a debiased moment, justifying their use over other "ad-hoc" choices of instruments often used in applied work. We argue that this will necessarily require solving functional equations involving unknown terms directly linked to the particular model at hand. However, by imposing an approximate sparsity condition, our method automatically finds the solutions to those equations using a Lasso-type program and thus can be implemented straightforwardly in the same way, regardless of the particular model. Based on this, we introduce a GMM estimator of a finite-dimensional parameter in a Two-Step setting. We derive theoretical guarantees for our construction of orthogonal moments and show the asymptotic normality of the introduced estimator.
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
Methods relying on instrumental variables (IVs) are known to be useful for learning treatment effects in experiments where treatment randomization is not possible. Often, the researcher can use a large class of potentially valid IVs, but is there an <em>optimal</em> choice? If so, which one? In this paper, we argue that a measure of the "strength" of the instrument as predictor of the treatment, conditional on pre-treatment characteristics, leads to an estimator that enjoys three \textit{key} properties: (1) local orthogonality, (2) identification of the parameter of interest under the minimal conditions, and (3) meaningful nonparametric interpretation in terms of conditional local treatment effects, even if defiers are not completely ruled out in the population. In the common situation where the treatment variable is binary, such strength is linked to the probability of complying with the treatment. Therefore, we name this estimator *Compliance Machine Learning Estimator (CML)*. If the researcher's criterion of optimality involves these three attributes, then CML is the optimal choice. We provide theoretical guarantees that support the use of off-the-shelf routines to conduct standard inference on CML, when machine learning tools are used to construct the IV. We study the relative performance of this estimator through a Monte Carlo exercise. Finally, we revisit the Oregon Health Insurance Experiment, analyzed by Finkelstein et al. (2012). We find that the use of machine learning and CML suggest larger positive effects on health care utilization than previously determined.
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

