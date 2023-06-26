# Interpretable_ML_tabular_and_image

Employ popular model-agnostic interpretable machine learning methods, LIME and SHAP, to analyze and interpret the behaviors of models in the context of tabular data classification and image data classification tasks

:question: **Problem:** How to enhance the interpretability of powerful black-box models?

:key: **Importance:** Bridge the gap between complex machine learning models and human understanding, enhancing transparency, trust, and accountability in the decision-making process.

🎉 **Achievements:** Apply LIME and SHAP techniques to shed light on the black box nature of machine learning models, providing insights into how they make predictions for both tabular and image data classification problems.

💪 **Skills:** Python, Pytorch, Deep learning, XAI

:books: **Insights:** Inner workings of complex machine learning models, the identification of important features and patterns that drive their predictions, facilitating model debugging, feature engineering, and the identification of potential biases or limitations.

# Problem statement:
What is Interpretability? "Interpretability is the measure of how well a user can correctly and efficiently predict the model's results"

# Models 
## Intrinsically Interpretable Models
* Regression
* Decision Tree

## Model-Agnostic Methods

The benefit of using Model-Agnostic Methods:

The great advantage of model-agnostic interpretation methods over model-specific ones is their flexibility. Machine learning developers are free to use any machine learning model they like when the interpretation methods can be applied to any model. Anything that builds on an interpretation of a machine learning model, such as a graphic or user interface, also becomes independent of the underlying machine learning model.

### Global

* Partial Dependence Plot (PDP):
* Accumulated Local Effects (ALE) Plot:

### Local
* [Local Surrogate (LIME)](https://github.com/marcotcr/lime)
* [Shapley Values](https://github.com/slundberg/shap)

# Applications:

## Tabular data prediction:

### Dataset
[Stroke Prediction](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset)

### Pipeline

![tabular_pipeline](/img/cs_573_GRAPH-Data_pipeline.jpg)
|:--:| 
| Pipeline for tabular data |

### Result

![Lime_tabular](/img/lime_48796.png)
|:--:| 
| Lime: tabular data |

![SHAP_tabular](/img/shap_48796.png)
|:--:| 
| SHAP: tabular data |


## Image data classification

### Dataset
[Kaggle-Dog Breed Identification](https://www.kaggle.com/competitions/dog-breed-identification/data)

### Pipeline
![img_pipeline](/img/cs_573_GRAPH-Page-5.jpg)
|:--:| 
| Pipeline for image data |

### Result
![Lime_tabular](/img/lime_img.png)
|:--:| 
| Lime: image data |

![SHAP_tabular](/img/shap_img.png)
|:--:| 
| SHAP: image data |

# Links:
* [Slides](https://docs.google.com/presentation/d/1RywAZKnVACfEmtSENQAHf3tkPlEYDq6TLxLe4nfo-Sw/edit?usp=sharing)
* [Article](https://www.overleaf.com/read/kcdmtckrxrbp)
* [Note](https://docs.google.com/document/d/1GlCb5lqmUZLP6WN2IO16M0KV0wyLoc4n9E6AGacxIbI/edit?usp=sharing)

# Reference:
* [Interpretable Machine Learning-Christoph Molnar](https://christophm.github.io/interpretable-ml-book/)


