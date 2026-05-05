# real_estate_llm
Fine-tuned TinyLlama-1.1B with LoRA for Bengaluru Real Estate QA using Unsloth
# Real-Estate Intelligence Assistant — LLM Fine-Tuning

Fine-tuned **TinyLlama-1.1B-Chat** using **LoRA (Unsloth)** on a 
Bengaluru real estate dataset to build a domain-specific QA assistant.

## 🔧 Tech Stack
- Model: TinyLlama-1.1B-Chat (4-bit quantized)
- Fine-tuning: LoRA via Unsloth + PEFT
- Training: SFTTrainer (TRL), EarlyStopping, 90/10 train/eval split
- UI: Gradio
- Data: 8 custom datasets (geo, market metrics, news, micromarket timeseries, etc.)

## 📂 Files
- `Real estate LLM model.ipynb` — Full fine-tuning pipeline (run on Google Colab)

## 🚀 How to Run
1. Open the notebook in Google Colab
2. Run Cell 1 → Restart Runtime → Run Cell 2 onwards
3. Upload your data files to `/content/`
4. I have added datasets with which i trained this model
