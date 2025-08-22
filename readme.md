# Detecting Languages with Python: A Step-by-Step Guide

Unlock the power of **automatic language detection** in your datasets using Python.  
This tutorial demonstrates **language detection** using the `langdetect` library in a Jupyter Notebook:  
**Language-Detection-Tutorial.ipynb**


## Learning Objectives

By completing this tutorial, you will:

- **Understand the fundamentals of language detection**
- **Set up your Python environment** for language analysis
- **Build a language detection tool** using Python libraries
- **Evaluate detected languages** in datasets and real-world scenarios


## Target Audience

This guide is designed for:

- **Researchers** in social sciences and linguistics
- **Students and professionals** beginning with NLP
- **Data analysts** working with multilingual datasets
- **Anyone interested** in Python-based language detection


## Estimated Duration

**Approximately 1 hour**


## Use Cases

- **Survey Analysis:** Identify primary languages in multilingual survey responses
- **Media Studies:** Analyze language distribution in social media or news articles


## Setup Instructions

Install the required libraries:

```bash
pip install -r requirements.txt
```


> **Explore the full tutorial:**  
> See **Language-Detection-Tutorial.ipynb** for complete code and examples.


## Technical Overview

This tutorial utilizes the **`langdetect` library** (a port of Google's language-detection tool) to identify languages in text samples.  
All code is provided in a **Jupyter Notebook** for interactive learning and easy adaptation.

**Key Features:**

- **Language Detection:**  
    Use `langdetect.detect()` to predict language codes (e.g., `'en'`, `'fr'`, `'es'`)
- **Batch Processing:**  
    Apply detection across pandas DataFrame columns for efficient dataset analysis
- **Error Handling:**  
    Manage exceptions for empty or ambiguous text inputs
- **Visualization:**  
    Summarize language distributions with matplotlib for instant insights


## Key Takeaways

- **Efficiently process and analyze multilingual data** with pandas
- **Visualize language distributions** using matplotlib
- The **Jupyter Notebook** is a ready-to-use template for your own projects
- **Understanding language distribution** unlocks insights for research, analytics, and NLP


## Contact

For questions or feedback:  <susmita.gangopadhyay@gesis.org>
