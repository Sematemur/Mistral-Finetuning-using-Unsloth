# Mistral-Finetuning-using-Unsloth
modeli ollamada local olarak kullanmak için, ollamayı indirdikten sonra terminale
"ollama run hf.co/sematemur/openai_gsm8k_finetune_mistral7b_"  yazabilirsiniz. 
[<u>Modeli Huggingface'de görmek için tıklayın :)</u>](https://huggingface.co/sematemur/openai_gsm8k_finetune_mistral7b_)

![image](https://github.com/user-attachments/assets/705c552a-12c0-41e9-bfb8-da8e7b878140)
![image](https://github.com/user-attachments/assets/f00b4972-6a7d-40fe-8448-a4c6d0d579f5)
![image](https://github.com/user-attachments/assets/e15e2a6e-bdac-4c53-9fc3-484f9c6f3f6f)

## Finetune bilgileri 
Projede "unsloth/mistral-7b-instruct-v0.3-bnb-4bit" modeli  "openai/gsm8k" veriseti ile finetune edildi. Bu finetune işlemini 25 epoch olarak yaptım. Unsloth kullanarak finetune işleminin daha hızlı olmasını sağlıyoruz. Burada LoRA ile modelimizi eğittik. LoRA ,tüm modeli yeniden eğitmeden sadece belirli parametreleri eğiterek daha hızlı eğitilmesini sağlar. 






