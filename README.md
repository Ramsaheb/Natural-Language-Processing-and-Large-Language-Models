While working with Hugging Face transformer models, it is important to consider system hardware limitations—especially RAM and GPU capacity—before selecting a model.

Systems with more than 8 GB RAM/GPU can comfortably handle models in the 8–10 GB range.

For systems with 8 GB RAM or less, smaller model variants should be used. In this project, a GPT-2 model was selected to avoid memory overflow.

Even for moderate NLP tasks, training for 2–3 epochs can lead to out-of-memory errors on local machines. To address this, Google Colab was used for smoother execution and better resource management.

This implementation follows the “LLM from Scratch” YouTube series taught by Dr. Raj Dandekar, a well-known professor and founder of Visuara. The project is implemented using a single Jupyter Notebook that covers the complete pipeline—from dataset selection and preprocessing to model training and evaluation.

For clarity and deeper understanding, the notebook provided by Dr. Raj Dandekar has been used without modification, as it already presents a well-structured and comprehensive approach to building and evaluating large language models.
