# rag_system
# Gemma & DistilBERT LoRA Projects

این ریپو شامل دو پروژه اصلی است:  
1. **Gemma-2B-IT LoRA Fine-Tuning** برای تولید متن با مدل بزرگ GEMMA.  
2. **DistilBERT LoRA Fine-Tuning** برای طبقه‌بندی احساسات (Sentiment Analysis) روی دیتاست IMDB.  

---

## 📦 پیش‌نیازها
- Python >= 3.9
- CUDA (برای GPU)
- بسته‌های Python:
```bash
pip install -U bitsandbytes accelerate transformers datasets peft torch pandas
