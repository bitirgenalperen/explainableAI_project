# PoliTo Explainable AI - Project

## Introduction:
Multimodal classification research has been gaining popularity, showing the benefits of combining data from multiple sources compared to traditional unimodal data. In recent years, many novel multimodal architectures have been proposed.However, these models are even more complex than the unimodal ones. Thus, their opacity is an even more challenging problem that poses a barrier to their applicability in real-world applications.

Recent advancements in XAI have introduced methods aimed at enhancing interpretability for multimodal models [4, 1, 3, 2]. Still, many gaps exist in this field. This project aims to develop XAI techniques tailored for multimodal models or propose new evaluation methods for XAI multimodal techniques. The focus is to increase the interpretability of the decision-making processes of these classifiers involving multiple modalities.

## The Goal of the Project
Firstly, the project aims to review existing explanation methods or XAI evaluation for multimodal classifiers. Secondly, the project must identify existing research gaps in the XAI literature for multimodal classifiers. The research gap can be for both XAI techniques or the evaluation of XAI techniques. Examples of proposals can be the investigation of techniques for generating explanations of XAI classifiers (e.g., feature-based, gradient-based, counterfactual, plain-text explanations, etc.) suitable for classifiers involving multiple modalities. Another example can be the implementation of XAI techniques for individual modalities (e.g., LIME, SHAP) for models involving multiple modalities. A possible output of this project can also be a library to democratize the use of XAI methods for multimodal classifiers, or new evaluation techniques for XAI-multimodal methods.

## Requirements
- Literature Review: Conduct a systematic review of existing XAI methods or evaluation methods for explaining the predictions of multimodal classifiers.
- Identification of Research Gaps: Identify key research gaps for improving existing XAI techniques or evaluation of XAI techniques for multimodal classifiers.
- Implementation: Select a specific research gap to address. Propose and implement a methodology to address the identified research gap. This may involve 1) proposing a novel XAI approach for multimodal classifiers, 2) improving an existing approach, 3) adapting an existing unimodal technique (e.g., SHAP) to the multimodal domain, 4) implementing a simple interface to apply existing XAI multimodal techniques with well-known libraries such as HuggingFace, or 5) propose XAI evaluations suitable for the multimodal domain.
- Evaluation: Assess the effectiveness and applicability of the newly implemented approach

## Project Roadmap

| Starting Date | Ending Date | Task                                                                                                 | Status     |
|---------------|-------------|------------------------------------------------------------------------------------------------------|------------|
| 01-06-2024    | 15-06-2024  | Literature Review: Conduct a systematic review of existing XAI methods or evaluation methods for explaining the predictions of multimodal classifiers. | In Progress  |
| 16-06-2024    | 30-06-2024  | Identification of Research Gaps: compare lime and mm-shap using the code and database | In Progress|
| 04-07-2024    | 10-07-2024  | Propose and implement a methodology to address the identified research gap that involves:       | Not Started|
|               |             | - Proposing a LIME integrated XAI approach for multimodal classifiers                                          |            |
|               |             | - Adapting LIME unimodal technique to the multimodal domain                      |            |
|               |             | - Supporting the proposed approach with resource datasets and codebases                                                                  |            |
|               |             | - Implementing an interface to apply existing XAI multimodal techniques with well-known libraries such as HuggingFace(?) |            |
|               |             | - By examining the existing evaluation metrics optimize the propesed and implemented multimodal structure                                   |            |
| 10-07-2024    | 15-07-2024  | Evaluate the effectiveness and applicability of the newly implemented approach                       | Not Started|
| 16-07-2024    | 18-07-2024  | Document the results and prepare a report on findings and recommendations                            | Not Started|
| 18-07-2024    | 22-07-2024  | Final review and adjustments based on feedback                                                      | Not Started|



