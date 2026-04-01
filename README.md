# CSI5388_LLM_SQL_Injector_Generator

# Running the SQL Injection Payload Generator

## 1. Install Python Dependencies

Install the required packages using pip:

```bash
pip install google-genai transformers huggingface_hub kagglehub sqlglot pandas
```

## 2. Set API Keys

```bash
export HF_API_KEY=your_huggingface_api_key
export GEMINI_API_KEY=your_gemini_api_key
```

Windows:
```bash
set HF_API_KEY=your_huggingface_api_key
set GEMINI_API_KEY=your_gemini_api_key
```

#3. Navigate to the project directory

```bash
cd path/to/project/folder
```

#4. Run the script

```bash
python phase1_llm_generate_payloads.py
```
