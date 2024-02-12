
---
title: ManageDiabetesThroughDiet
emoji: 📊
colorFrom: green
colorTo: indigo
sdk: gradio
sdk_version: 4.18.0
app_file: app.py
pinned: false
license: mit
---


**Food-Glycemic-Index-Checker.ipynb**

This project helps people with diabetes make informed decisions about their food choices by using Google's Gemini Pro Vision model to:

1. Identify the type of fruit or food in an image.
2. Determine the glycemic index of the identified item.
3. Recommend whether the food is suitable for people with diabetes and, if so, the recommended quantity for consumption.

**How to use:**

1. **Upload an image of the food you want to eat.**
2. The model will analyze the image and provide you with the information mentioned above.

**Requirements:**

- Python 3.7+
- `google-generativeai` library
- `gradio` library

**Instructions:**

1. Install the required libraries:
   ```bash
   pip install google-generativeai gradio
   ```
2. Replace `your_actual_api_key` with your actual Google Generative AI API key in the code.
3. Run the Jupyter Notebook file `Food-Glycemic-Index-Checker.ipynb`.
4. Upload an image of the food you want to eat and click "Run".



Check out the configuration reference at https://huggingface.co/docs/hub/spaces-config-reference
