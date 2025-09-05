---
layout: archive
title: "Working Papers"
permalink: /working/
author_profile: true
---

### 2023 - 2025
+ [Debiased Machine Learning for Unobserved Heterogeneity: High-Dimensional Panels and Measurement Error Models (2025)](https://arxiv.org/abs/2507.13788), joint with [Juan Carlos Escanciano](https://sites.google.com/view/juancarlosescanciano/home).
<dl style="margin-top: -10px;">
  <dd>
    <details>
      <summary>
        Abstract
      </summary>
Developing robust inference for models with nonparametric Unobserved Heterogeneity (UH) is both important and challenging. We propose novel Debiased Machine Learning (DML) procedures for valid inference on functionals of UH, allowing for partial identification of multivariate target and high-dimensional nuisance parameters. Our main contribution is a full characterization of all relevant Neyman-orthogonal moments in models with nonparametric UH, where relevance means informativeness about the parameter of interest. Under additional support conditions, orthogonal moments are globally robust to the distribution of the UH. They may still involve other high-dimensional nuisance parameters, but their local robustness reduces regularization bias and enables valid DML inference. We apply these results to: (i) common parameters, average marginal effects, and variances of UH in panel data models with high-dimensional controls; (ii) moments of the common factor in the Kotlarski model with a factor loading; and (iii) smooth functionals of teacher value-added. Monte Carlo simulations show substantial efficiency gains from using efficient orthogonal moments relative to ad-hoc choices. We illustrate the practical value of our approach by showing that existing estimates of the average and variance effects of maternal smoking on child birth weight are robust.
    </details>
  </dd>
</dl>

+ [Randomly Assigned First Differences? (2025)](https://arxiv.org/abs/2411.03208), joint with [Clément de Chaisemartin](https://sites.google.com/site/clementdechaisemartin/) and [Ziteng Lei](https://zitenglei.weebly.com/).
<dl style="margin-top: -10px;">
  <dd>
    <details>
      <summary>
        Abstract
      </summary>
We consider treatment-effect estimation using a first-difference regression of an outcome evolution $\Delta Y$ on a treatment evolution $\Delta D$. Under a causal model in levels with a time-varying effect, the regression residual is a function of the period-one treatment $D_1$. Then, researchers should test if $\Delta D$ and $D_1$ are correlated: if they are, the regression may suffer from an omitted variable bias. To solve it, researchers may control nonparametrically for $\mathbb{E}\left[\Delta D|D_1\right]$. We use our results to revisit first-difference regressions estimated on the data of Acemoglu et al. (2016), who study the effect of imports from China on US employment. $\Delta D$ and $D_1$ are strongly correlated, thus implying that first-difference regressions may be biased if the effect of Chinese imports changes over time. The coefficient on  $\Delta D$ is no longer significant when controlling for $\mathbb{E}\left[\Delta D|D_1\right]$.
    </details>
  </dd>
</dl>

+ [Automatic Debiased Machine Learning of Structural Parameters with General Conditional Moments (2024)](https://drive.google.com/file/d/1DjzGPdIens-Wrpfc6JrvFUWu71lnj7zg/view?usp=drive_link) (Job Market Paper).
<dl style="margin-top: -10px;">
  <dd>
    <details>
      <summary>
        Abstract
      </summary>
This paper proposes a method for conducting inference on finite-dimensional parameters in models defined by a finite number of conditional moment restrictions (CMRs), with possibly different conditioning variables and endogenous regressors. CMRs are allowed to depend on non-parametric components, which might be flexibly modeled using Machine Learning tools, and non-linearly on finite-dimensional parameters. Inference is based on constructing locally robust/orthogonal/debiased moments, in a data-driven our automatic way, extending these to accommodate CMRs. Those moments are less affected by regularization bias, which is relevant to machine learning first steps and typically invalidates standard inference. The key step in this construction is the estimation of Orthogonal Instrumental Variables (OR-IVs)—"residualized" functions of the conditioning variables, which are then combined to obtain a debiased moment. Our strategy exploits the CMRs implied by the model in a general way and can thus be applied to a wide range of settings, where the construction of orthogonal moments has remained unexplored, including highly non-linear and complex settings with CMRs, prominent in economics. We argue that computing OR-IVs necessarily requires solving potentially complicated functional equations, which depend on unknown terms. However, by imposing an approximate sparsity condition, our method automatically finds the solutions to those equations using a Lasso-type program and can then be implemented straightforwardly. Based on this, we introduce a GMM estimator of finite-dimensional parameters in a two-step framework. We derive theoretical guarantees for our construction of orthogonal moments and show √n-consistency and asymptotic normality of the introduced estimator. Our Monte Carlo experiments and an empirical application on estimating firm-level production functions highlight the importance of relying on inference methods like the one proposed.
    </details>
  </dd>
</dl>

+ [Machine Learning Debiasing with Conditional Moment Restrictions: An Application to LATE (2024)](https://arxiv.org/abs/2410.23785), joint with [Juan Carlos Escanciano](https://sites.google.com/view/juancarlosescanciano/home).
<dl style="margin-top: -10px;">
  <dd>
    <details>
      <summary>
        Abstract
      </summary>
Models with Conditional Moment Restrictions (CMRs) are popular in economics. These models involve finite and infinite dimensional parameters. The infinite dimensional components include conditional expectations, conditional choice probabilities, or policy functions, which might be flexibly estimated using Machine Learning tools. This paper presents a characterization of locally debiased moments for regular models defined by general semiparametric CMRs with possibly different conditioning variables. These moments are appealing as they are known to be less affected by first-step bias. Additionally, we study their existence and relevance. Such results apply to a broad class of smooth functionals of finite and infinite dimensional parameters that do not necessarily appear in the CMRs. As a leading application of our theory, we characterize debiased machine learning for settings of treatment effects with endogeneity, giving necessary and sufficient conditions. We present a large class of relevant debiased moments in this context. We then propose the Compliance Machine Learning Estimator (CML), based on a practically convenient orthogonal relevant moment. We show that the resulting estimand can be written as a convex combination of conditional local average treatment effects (LATE). Altogether, CML enjoys three appealing properties in the LATE framework: (1) local robustness to first-stage estimation, (2) an estimand that can be identified under a minimal relevance condition, and (3) a meaningful causal interpretation. Our numerical experimentation shows satisfactory relative performance of such an estimator. Finally, we revisit the Oregon Health Insurance Experiment, analyzed by Finkelstein et al. (2012)}. We find that the use of machine learning and CML suggest larger positive effects on health care utilization than previously determined.
    </details>
  </dd>
</dl>

+ [On the Existence and Information of Orthogonal Moments (2023)](https://arxiv.org/abs/2303.11418), joint with [Juan Carlos Escanciano](https://sites.google.com/view/juancarlosescanciano/home). [Supplementary Appendix](https://drive.google.com/file/d/1X8gtzjNk1g1mZxBONcD3vbVMuBKHQJDC/view?usp=sharing)
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

