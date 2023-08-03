# Experimental Local Auto GPT

# Where to get Models
1. Go to hugging face
2. Find a GGML Model e.g. https://huggingface.co/anon8231489123/gpt4-x-alpaca-13b-native-4bit-128g/blob/main/gpt4-x-alpaca-13b-ggml-q4_1-from-gptq-4bit-128g/ggml-model-q4_1.bin
3. You now have two options
    1. Download the repo (all hugging face pages are git repos) and use LFS to git clone the files (since they are big)
    2. Or , you can click on the section “files” and down load via your browser

Example working model `llama-2-7b.ggmlv3.q2_K.bin`: https://huggingface.co/TheBloke/Llama-2-7B-GGML/tree/main

# Running test model

Command `./main -m models/7b/llama-2-7b.ggmlv3.q2_K.bin -p "the sky is"`