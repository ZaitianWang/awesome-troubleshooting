# Hugging Face

## [HF-Mirror](https://hf-mirror.com/)

```bash
pip install -U huggingface_hub
```
```bash
export HF_ENDPOINT=https://hf-mirror.com
```
(写入 ~/.bashrc)
```bash
huggingface-cli download --resume-download gpt2 --local-dir gpt2
```
```bash
huggingface-cli download --repo-type dataset --resume-download wikitext --local-dir wikitext
```

