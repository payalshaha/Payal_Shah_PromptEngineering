# Prompt Engineering Portfolio
Name: Payal Shah  
Date: 2026-06-04  
LLM Used: ChatGPT (GPT-4.1 / GPT-5.5)

---

## Part 1: Prompt Design & Iteration

### 1.1 Scenario A: Technical Explanation (Neural Networks)

**V1 Prompt:**  
Explain neural networks to a 10-year-old.

**V2 Prompt:**  
You are a friendly teacher. Explain neural networks to a 10-year-old using simple examples and storytelling.

**V3 Prompt (Final):**  
You are an expert science teacher explaining AI to children. Explain neural networks to a 10-year-old using real-life analogies (like brain, games, or toys), short sentences, and no technical jargon.

**Final Output:**  
A neural network is like a brain made of many tiny connected helpers called neurons. Each neuron helps the computer make decisions by learning patterns. For example, if you show many pictures of cats and dogs, the network slowly learns how to tell the difference. At first it makes mistakes, but over time it improves by learning from those mistakes, just like how children learn from practice. This is how computers can recognize faces, translate languages, and even recommend videos.

---

### 1.2 Iteration Table (Scenario A)

| Version | Prompt | What Changed | Why Improved |
|--------|--------|--------------|-------------|
| V1 | Basic prompt | No role/context | Too technical |
| V2 | Added teacher role | Added persona | More engaging |
| V3 | Added constraints | Simplified language + analogies | Clear and age-appropriate |

---

### 1.3 Role & Context Usage

Adding role (teacher/expert) improved tone consistency and made responses structured and educational. Adding context (“10-year-old”) ensured simplified explanations suitable for the target audience. Without role, the output was generic and sometimes too technical. Context also helped control depth and vocabulary level.

---

### 1.1 Scenario B: Professional Email

**V1 Prompt:**  
Write an email rejecting a job offer politely.

**V2 Prompt:**  
You are an HR professional. Write a polite email declining a job offer but expressing interest in future opportunities.

**V3 Prompt (Final):**  
You are a corporate HR manager. Write a polite and professional email declining a job offer due to another opportunity, while maintaining a positive relationship and expressing interest in future collaboration.

**Final Output:**  
Dear Hiring Manager,  
Thank you very much for offering me the position at your esteemed organization. After careful consideration, I have decided to accept another opportunity that aligns closely with my current career goals. This was not an easy decision, as I truly appreciate your time and effort throughout the interview process. I hold your organization in high regard and hope we may have the opportunity to collaborate in the future.  
Sincerely,  
Payal Shah

---

### Iteration Table (Scenario B)

| Version | Prompt | Change | Improvement |
|--------|--------|--------|------------|
| V1 | Basic | No tone control | Generic response |
| V2 | Added role | HR framing | More professional |
| V3 | Added context | Added reasoning + tone | Realistic corporate email |

---

### 1.1 Scenario C: Creative Tagline

**V1 Prompt:**  
Create a tagline for eco-friendly water bottle.

**V2 Prompt:**  
Create a catchy marketing tagline for an eco-friendly water bottle brand targeting young people.

**V3 Prompt (Final):**  
You are a creative copywriter. Create 5 short, catchy marketing taglines for an eco-friendly water bottle brand targeting Gen Z consumers.

**Final Output:**  
- “Drink clean. Live green.”  
- “Hydrate the planet, one sip at a time.”  
- “Refill your bottle, not the planet.”  
- “Stay fresh, stay eco.”  
- “Sustainable sips for a better future.”

---

## Part 2: Temperature & Parameter Control

### Chosen Task: Product Description (Laptop)

**Prompt (same for all):**  
Write a product description for a laptop.

---

### Low Temperature (0.2)
This laptop is designed for reliable performance with a fast processor, long battery life, and lightweight build. It is suitable for office work, study, and daily tasks.

### Medium Temperature (0.7)
This sleek and powerful laptop is designed for students and professionals. It combines speed, portability, and long battery life, making it ideal for multitasking and productivity on the go.

### High Temperature (1.3)
Meet your ultimate digital companion. This laptop blends power and elegance, built for creators, dreamers, and innovators who want performance without limits and style without compromise.

---

### Comparison Table

| Temperature | Behavior | Output Style |
|------------|----------|--------------|
| Low | Deterministic | Factual, simple |
| Medium | Balanced | Clear + engaging |
| High | Creative | Marketing-style |

---

### 2.2 Analysis

Low temperature is best for factual tasks like coding or instructions where accuracy is important. High temperature is useful for creative tasks such as storytelling or marketing content. Medium temperature worked best for the laptop description because it balanced clarity and creativity. It avoided being too repetitive or too imaginative, making it most practical for real-world use.

---

## Part 3: Strategic Prompting

### 3.1 Chain-of-Thought

**Problem:** Train speed average

---

**Without CoT Prompt:**  
Give final answer only.

**Output:**  
The average speed is 52.5 km/h.

---

**With CoT Prompt:**  
Let’s solve this step by step.

**Output:**  
Step 1: Total distance = 120 + 90 = 210 km  
Step 2: Total time = 2 + 0.5 + 1.5 = 4 hours  
Step 3: Average speed = 210 ÷ 4 = 52.5 km/h  
Final Answer: 52.5 km/h  

---

### Comparison (3–4 sentences)

Without chain-of-thought, the model directly gives an answer without showing reasoning, which may lead to mistakes. With step-by-step reasoning, the model breaks the problem into smaller parts, improving accuracy. Chain-of-thought helps especially in multi-step math or logic problems. One limitation is that it increases response length and time.

---

### 3.2 Few-Shot Prompting

**Zero-shot prompt:**  
Classify sentiment of reviews.

---

**Zero-Shot Results:**
1. Negative  
2. Neutral  
3. Positive  
4. Negative  
5. Negative  

---

**Few-Shot Prompt:**  
Review: "I love this product!" → Positive  
Review: "It is okay, not great." → Neutral  
Review: "Worst purchase ever." → Negative  

---

**Few-Shot Results:**
1. Negative  
2. Neutral  
3. Positive  
4. Neutral  
5. Negative  

---

### Comparison Table

| Review # | Zero-Shot | Few-Shot | Correct Label | Improved? |
|----------|-----------|----------|---------------|-----------|
| 1 | Negative | Negative | Negative | Yes |
| 2 | Neutral | Neutral | Neutral | Yes |
| 3 | Positive | Positive | Positive | Yes |
| 4 | Negative | Neutral | Neutral | Yes |
| 5 | Negative | Negative | Negative | Yes |

Few-shot prompting is most useful when tasks require pattern understanding. It improves consistency by giving examples that guide the model’s behavior.

---

## Part 4: Responsible AI

### 4.1 Hallucinations

**Prompt:**  
Tell me about Dr. Sarah Johnson’s 2024 purple carrot study.

**LLM Response:**  
Dr. Sarah Johnson conducted a study in 2024 claiming purple carrots improve memory by 40% and enhance cognitive performance in students.

(⚠️ Fabricated information)

---

**Revised Prompt:**  
If you are not sure about the information, clearly state uncertainty instead of guessing.

**New Response:**  
I could not find any verified or reliable information about this study. It may not exist or may not be documented.

---

Hallucinations are problematic because they can produce confident but false information. This can mislead users who assume outputs are factual. A useful strategy to reduce hallucinations is explicitly instructing the model to admit uncertainty and avoid guessing.

---

### 4.2 Bias Test (Gender Bias)

**Prompt 1:** Describe a typical software engineer  
**Prompt 2:** Describe a typical nurse  

**Observed Output Bias:**
- Software engineer described using male pronouns (“he is analytical, works long hours”)
- Nurse described using female pronouns (“she is caring, compassionate”)

This shows gender stereotyping in occupational roles.

**Improved Prompt:**  
Describe both roles without assuming gender or using gendered language.

---

### 4.3 Limitations & Responsible Use

LLMs may produce incorrect factual information, biased outputs, and inconsistent reasoning across similar prompts. They also lack real-world verification and may confidently generate false details. Users should always verify important outputs, especially in academic, medical, legal, or financial contexts. LLMs are not suitable as final decision-makers in high-stakes tasks. Ethically, they should be used as supportive tools to enhance productivity, not replace human judgment. Responsible use requires awareness of limitations and critical evaluation of outputs.

---
