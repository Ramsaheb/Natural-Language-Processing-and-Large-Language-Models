# Project Description

While working with **Hugging Face transformer models**, it is important to consider **system hardware limitations**, especially **RAM and GPU capacity**, before selecting a model.

## Hardware Considerations

- Systems with **more than 8 GB RAM or GPU memory** can efficiently run models in the **8–10 GB size range**.
- Systems with **8 GB RAM or less** should use **smaller model variants**. In this project, the **GPT-2 model** was used to avoid memory-related issues.
- Even standard **NLP tasks** can cause **out-of-memory (OOM) errors** when trained for **2–3 epochs** on local machines. To handle this, **Google Colab** was used.

## Learning Reference

This project is based on the **“LLM from Scratch”** YouTube series taught by **Dr. Raj Dandekar**, a well-known professor and founder of **Visuara**.

## Implementation Details

- The complete workflow is implemented in a **single Jupyter Notebook**.
- It covers all stages from **dataset selection and preprocessing** to **model training and evaluation**.
- For better understanding and correctness, the **original notebook provided by Dr. Raj Dandekar** has been used **as-is**, as it already presents a **clear and well-structured pipeline**.
