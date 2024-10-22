# AI Tinkerers October Hackathon Show & Tell 🧠
- A hackathon competition repository to develop LLM-as-Judge solution to automate the output scoring return by any Large Language Model.

# 💫 Getting Started
## Setting Up
1. Fork this repository.
2. Install dependencies with `pip install -r requirements.txt`.
3. PR for changes approval.

## Benchmarking
1. Refer to notebook - `03_benchmark_malaysian_mistral_llmasajudge_v2.ipynb` in `/notebooks-benchmarking-exercises`
2.  Login Weight & Bias to setup Weave logger. Get the API key to setup the project.
3. Change the `call_llm` function according to the model apply (OpenAI, Huggingface, Gemini, etc.)
4. Run the notebook for benchmarking.

# 📂 File Structure
```
.
├── datasets
├── miscellaneous
├── notebooks-benchmarking-exercises
├── notebooks-data-preparation
├── notebooks-finetuning-models
├── .gitignore
└── requirements.txt
```
## Detail 
- `datasets/ ` : Dataset use for finetune and benchmarking.
- `notebooks-benchmarking-exercises/` : Notebook for benchmarking.
- `notebooks-data-preparation/` : Notebok for finetune data preparation.
- `notebooks-finetuning-models/` : Notebook for model finetuning.

# 📈 Progress
- [x] Finetuning Mistral Model
- [ ] Benchmarking with OpenAI
- [ ] Becnhmarking with Gemini Flash
- [ ] Prompt engineering model improvement
- [ ] Deployment  
