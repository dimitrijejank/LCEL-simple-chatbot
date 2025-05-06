
# LangChain Expression Language (LCEL) Project

This project demonstrates the use of the **LangChain Expression Language (LCEL)** in building composable, chainable language model applications using OpenAI's APIs. It showcases how to build and execute structured chains of prompts and models in Python using LangChain's powerful expression syntax.

## 📚 Overview

The notebook `LCELfinal.ipynb` contains:

- A practical example of using LangChain's Expression Language (LCEL)
- Construction of chains using the `Runnable` interfaces
- Integration with OpenAI's GPT model
- Parameter handling (e.g., temperature, max_tokens)
- Seed-based generation control (if supported)
- Example inputs and outputs for testing chain behavior

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

- Python 3.8+
- An OpenAI API key
- `langchain`
- `openai`
- `ipython`
- `jupyter`

### Installation

1. Create a virtual environment (optional but recommended):
   ```bash
   conda create -n langchain_env python=3.10
   conda activate langchain_env
   ```

2. Install dependencies:
   ```bash
   pip install langchain openai ipython jupyter
   ```

3. Set your OpenAI API key as an environment variable:
   ```bash
   export OPENAI_API_KEY="your-api-key-here"  # Mac/Linux
   set OPENAI_API_KEY=your-api-key-here       # Windows
   ```

## 🧠 Usage

1. Open the notebook:
   ```bash
   jupyter notebook LCELfinal.ipynb
   ```

2. Run the cells step-by-step to see how LangChain's Expression Language chains prompts and models.

3. Customize parameters like `temperature`, `model_name`, and input prompts.

## 🛠 Features

- ✅ Modular chain construction
- ✅ Support for prompt templates
- ✅ Custom input/output mapping
- ✅ Seamless integration with OpenAI's `ChatOpenAI` model

## 🧪 Example

```python
chat = ChatOpenAI(
    model_name='gpt-4.1-mini',
    temperature=0,
    max_tokens=100
)
```

You can then use `Runnable` objects to build and execute chains in a composable way.

## 📄 License

This project is licensed under the MIT License.

---

> **Note:** This project is for educational and prototyping purposes. Ensure you follow OpenAI’s usage policies when deploying models in production.

## ✍️ Author

Dimitrije Janković – [GitHub Profile](https://github.com/dimitrijejank)
