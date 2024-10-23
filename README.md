# Finetuning-embedding-models
In this repository, I share the code used to fine-tune an open-source model using Hugging Face’s SentenceTransformers module ('TomArtsen'). I fine-tuned the all-MiniLM-L6-v2 model, a multilingual embedding model, as I was working with a multilingual dataset. The model is small and easy to train—I used the MPS device for this.

However, fine-tuning takes a considerable amount of time, especially for a decent result, since I updated all of the model's weights. I haven't yet experimented with the LoRA (Low-Rank Adaptation) method, specifically the LoraConfig ( https://huggingface.co/docs/peft/v0.8.0/en/task_guides/semantic-similarity-lora ) from Hugging Face, which could potentially improve training efficiency.
