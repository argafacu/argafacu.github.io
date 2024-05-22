---
layout: archive
title: "Working Papers"
permalink: /working/
author_profile: true
---

### 2018 - 2024 
+ Compliance Machine Learning Estimator, joint with [Juan Carlos Escanciano.](https://sites.google.com/view/juancarlosescanciano/home) Draft coming soon. 
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


+ [A Fully Non-Parametric Approach for Forecasting with Binary Panel Data Models (2021)](https://drive.google.com/file/d/1D1bWW8OL7EMFqvkJ7WB8rtwnjeedCvvq/view?usp=share_link) (Master's Thesis under the supervision of [Raquel Carrasco](https://scholar.google.es/citations?user=pMpB2gsAAAAJ&hl=e) and [Jesús Gonzalo.](https://www.eco.uc3m.es/~jgonzalo/)).
<dl style="margin-top: -10px;">
  <dd>
    <details>
      <summary>
        Abstract
      </summary>
    This paper introduces a fully non-parametric approach for forecasting binary variables in a static panel data setting with strictly exogenous regressors, where N is large while T does not need to be large. The method does not make any assumption about the distribution of the errors of the model, the distribution of the individual effects, or even how the regressors and the associated parameters affect the dependent variable. The novelty of the technique relies on exploiting a sufficient statistic and using the fact that, under suitable conditions, this variable approximately follows the Poisson distribution. Built on this approximation, the approach applies the Tweedie's Formula, which allows identifying the one-step-ahead forecast of the outcome variable in this non-linear framework. The proposal can be easily extended to obtain predictions h-steps ahead. By means of numerous simulation exercises, the paper shows that the Tweedie's Forecast can achieve desirable forecast properties and be a satisfactory competitor against usual probit and logit models, regardless of numerous features of the data. Furthermore, this study applies the proposed approach to predict different health attributes (both physical and mental) for Spanish older adults, using grip strength as the predictor. Once again, the evidence indicates that the Tweedie's Forecast is able to systematically achieve good relative forecast accuracy.
    </details>
  </dd>
</dl>


+ [Productivity vs. Management: What Matters in the Export Process? (2018)](https://drive.google.com/file/d/1m-2sZ8UNMFSvLqU12fidA5H8K1TOKkxo/view?usp=sharing) (Bachelor's Thesis under the supervision of [María José Granado](https://face.unt.edu.ar/web/ieconomia/profesores/maria-jose-granado/)).
<dl style="margin-top: -10px;">
  <dd>
    <details>
      <summary>
        Abstract
      </summary>
      In this paper, both a theoretical and an empirical model to study the contribution of productivity and management practices on exporter status are presented. On the theoretical side, a multiple heterogeneity model is developed, where firms can differ in their levels of two dierent kinds of productivity: in cost and in management, in a context of monopolistic competition. With this, in the autarkic case, the model achieves two conditions (Zero Cut-Off Profitt Condition and Free Entry Condition) that firstly determine which firms enter and produce in the market. Then, by opening the economy to the rest of the world, the model not only shows which firms survive in the domestic market but also which ones export. Therefore, the most productive firms would not necessarily export, because export decision also depends on how efectively firms carry out a set of management practices to adapt their product to foreign demand. On the empirical side, productivity and management practices at firm level are measured by using several methods and specications to identify their efect on exporter status, exploiting the waves of The World Bank Enterprise Surveys of 2006, 2010 and 2017 for Argentina. The main results indicate that both productivity and management practices
affect positively the probability of being an exporter, and their effects are very similar in magnitude. Thanks to my work, I have identied some particular strategies firms should mainly focus on. Indeed, I suggest that obtaining ISO certications, offering training programs to employees and using services or programs to promote exports are important for being an exporter.
    </details>
  </dd>
</dl>
