# Feature Engineering: Sentence & paragraph features：[https://www.kaggle.com/competitions/llm-detect-ai-generated-text](https://www.kaggle.com/code/hiarsl/feature-engineering-sentence-paragraph-features)

Notice: This is a short two-week project.
## Project Introdution:

**Data Set:** [Eassy of the students]([https://www.kaggle.com/uciml/default-of-credit-card-clients-dataset](https://www.kaggle.com/competitions/llm-detect-ai-generated-text/data)). 

**Dataset Overview**: The dataset consists of approximately 10,000 essays. These essays are a mix of two types: ones authored by students and others generated by various large language models (LLMs). The core challenge of the competition is to discern whether each essay was produced by a student or by an LLM.

**Essay Composition**: Each essay was composed in response to one of seven specific prompts. Students, as part of the task, were required to read one or more source texts and then write an essay as a response. For the essays generated by LLMs, the same source texts and prompts may or may not have been used as inputs.

**Training and Test Sets**:

**Training Set**: This set includes essays responding to two of the seven prompts. The majority of these essays are student-written, with a minimal number of LLM-generated essays included as examples. Participants in the competition are encouraged to create additional LLM-generated essays for use as extended training data.

**Test Set**: The remaining essays, responding to the other five prompts, constitute a hidden test set. The test set, which will be used for final evaluation, contains roughly 9,000 essays, both student-written and LLM-generated.

**Stakeholders:** Minzhi Huang, RunTian Li, Salva Umar, Yimei Yang.
