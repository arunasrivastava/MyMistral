# Minstral Fine-Tuned for inspiring advice <br>
## Fine tuning a Mistral 7B model on a self-help book

### 💡 A chatbot's life advice is usually generic and uninspired; I figured I would try fine-tuning a model with data scraped from a self-help book containing real-life experiences and personal values. 

### 💻 Using Mistral 7B and a guide from Brev.dev, I fine-tuned with data scraped from my favorite book by Mark Manson ;) 

**Here is one of my favorite outputs: **

**Prompt:** "How to show self-compassion: "

**Fine-Tuned Mistral:** 
> " # 1. Notice when you're being hard on yourself and why. Ask yourself, "What am I telling myself that is making me feel so bad?" Often our harshest criticisms of ourselves are unrealistic or illogical--for example, "I should be able to get all A's in my classes," or "Everyone else can handle this problem; I must be a loser for not being able to." These sorts of thoughts are based more on cultural expectations than on reality. Many people struggle with schoolwork; few (if any) expect perfect grades from themselves. And while it may seem as though everyone around us has their lives together, the truth is that most people have insecurities and struggles just like we do. "

**For the same prompt, we get a more generic response from GPT-3.5:** 

> "Showing self-compassion involves treating yourself with kindness, understanding, and acceptance, especially in times of difficulty or failure. Start by acknowledging your struggles and validating your emotions without judgment. Practice self-care activities that nurture your physical, emotional, and mental well-being. Challenge negative self-talk by speaking to yourself with the same kindness you would offer a friend. Cultivate mindfulness to observe your thoughts and feelings without getting caught up in them. Set boundaries to prioritize your needs and avoid self-criticism. Practice forgiveness, letting go of past mistakes and embracing your humanity. Remember that self-compassion is a skill that can be cultivated through practice and patience, and it's essential for fostering resilience and overall well-being"

I love that fine-tuned Mistral produces an output that you could imagine a friend saying, occasionally using explicit humor as well. 

🧠 With double quantization from QLoRA, this can be done on cheaper GPUs which brev gives you access to. It's a better colab pro, consider checking it out if you want to have fun with ml/ai projects and need better GPU alternatives!

🤟🏽 Special thanks to Harper Carroll at Brev.dev for sharing this cool guide on fine-tuning with Mistral! It's a fun introduction to LLMs, highly recommend checking it out here: https://lnkd.in/eZc7ef-4
