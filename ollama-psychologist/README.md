# Dr. Ayesha – Local Clinical Psychologist (Ollama)

Yeh local AI psychologist hai. Data aapke laptop pe rehta hai.

## Run

```powershell
ollama run dr-ayesha
```

## Files

- `Modelfile` – system prompt + model settings
- Base model: `qwen2.5:7b`

## Rebuild (agar prompt change karo)

```powershell
cd D:\projects\prompt\ollama-psychologist
ollama create dr-ayesha -f Modelfile
```
