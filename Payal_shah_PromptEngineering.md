
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
A neural network is like a brain made of tiny connected helpers called “neurons.” Just like how you learn to recognize animals by seeing many pictures, computers learn by seeing many examples...

---

### 1.2 Iteration Table (Scenario A)

| Version | Prompt | What Changed | Why Improved |
|--------|--------|--------------|-------------|
| V1 | Basic prompt | No context | Output was too technical |
| V2 | Added role | Teacher role added | More child-friendly |
| V3 | Added constraints | Simplified language + analogies | Much clearer and engaging |

---

### 1.3 Role & Context Usage

Adding role improved clarity because the model followed a consistent persona (teacher). Adding context like “10-year-old” ensured simplified explanations. Without role, responses were too technical and not age-appropriate. Context helped control tone and depth of explanation.

---

### 1.1 Scenario B: Professional Email

**V1 Prompt:**  
Write an email rejecting a job offer politely.

**V2 Prompt:**  
You are an HR professional. Write a polite email declining a job offer but expressing interest in future opportunities.

**V3 Prompt (Final):**  
You are a corporate HR manager. Write a polite and professional email declining a job offer due to another opportunity, but keep the relationship positive and express interest in future collaboration.

**Final Output:**  
Dear Hiring Manager,  
Thank you very much for offering me the position... I have decided to pursue another opportunity...

---

### Iteration Table (Scenario B)

| Version | Prompt | Change | Improvement |
|--------|--------|--------|------------|
| V1 | Basic | No tone control | Too generic |
| V2 | Added role | HR perspective | More professional |
| V3 | Added context | Added reason + tone | More realistic email |

---

### 1.1 Scenario C: Creative Tagline

**V1 Prompt:**  
Create a tagline for eco-friendly water bottle.

**V2 Prompt:**  
Create a catchy marketing tagline for an eco-friendly water bottle brand targeting young people.

**V3 Prompt (Final):**  
You are a creative copywriter. Create 5 short, catchy marketing taglines for an eco-friendly water bottle brand targeting Gen Z consumers.

**Final Output:**  
- “Drink clean, live green.”  
- “Hydrate the planet.”  
- “Sip sustainably.”  

---

## Part 2: Temperature & Parameter Control

### Chosen Task: Product Description (Laptop)

**Prompt (same for all):**  
Write a product description for a laptop.

---

### Low Temperature (0.2)
The laptop is designed for performance and efficiency. It includes a fast processor, long battery life, and a lightweight body suitable for professionals.

### Medium Temperature (0.7)
This sleek laptop combines power and style, making it perfect for students and professionals who need performance on the go...

### High Temperature (1.3)
Meet your digital companion—this laptop doesn’t just work, it performs like a dream machine built for creators, explorers, and innovators...

---

### Comparison Table

| Temperature | Behavior | Output Style |
|------------|----------|--------------|
| Low | Factual | Safe, repetitive |
| Medium | Balanced | Clear + engaging |
| High | Creative | Marketing-style |

---

### 2.2 Analysis

Low temperature is useful for factual tasks like coding and data extraction. High temperature is useful for creative writing like storytelling or advertising. Medium temperature worked best for product description because it balanced clarity and creativity. It avoided being too boring or too random.

---

## Part 3: Strategic Prompting

### 3.1 Chain-of-Thought

**Problem:** Train speed average

#### Without CoT Prompt:
Give final answer only.

**Output:**  
95 km/h

#### With CoT Prompt:
Let’s solve this step by step.

**Output:**  
Step 1: Calculate total distance...  
Step 2: Calculate total time...  
Final Answer: 84 km/h

---

### Comparison (3–4 sentences)

Without chain-of-thought, the answer was fast but slightly incorrect. With step-by-step reasoning, the model broke down calculations correctly. CoT improves accuracy in multi-step problems. However, it takes more time and longer responses.

---

### 3.2 Few-Shot Prompting

**Zero-shot prompt:**  
Classify sentiment of reviews.

Results were inconsistent for neutral cases.

---

### Few-shot Prompt:
Review: "I love this product!" → Positive  
Review: "It is okay, not great." → Neutral  
Review: "Worst purchase ever." → Negative  

---

### Comparison Table

| Review | Zero-Shot | Few-Shot | Correct |
|--------|----------|----------|---------|
| 1 | Negative | Negative | Yes |
| 2 | Neutral | Neutral | Yes |
| 3 | Positive | Positive | Yes |
| 4 | Negative | Neutral | Yes |
| 5 | Negative | Negative | Yes |

Few-shot prompting is useful when classification rules are unclear. It helps the model learn expected patterns from examples.

---

## Part 4: Responsible AI

### 4.1 Hallucinations

Prompt:  
Tell me about Dr. Sarah Johnson’s 2024 purple carrot study.

Response:  
The model generated fabricated study details.

Revised Prompt:  
If you don’t know, say so clearly.

Response:  
I could not find reliable information.

Hallucinations are problematic because they sound confident but may be false. This can mislead users. Verification and uncertainty prompting reduce risks.

---

### 4.2 Bias Test (Gender Bias)

Software engineer → described as male-coded in some outputs  
Nurse → described as female-coded

Bias observed: gender stereotyping present.

Improved prompt:  
Describe roles without assuming gender.

---

### 4.3 Limitations & Responsible Use

LLMs may produce incorrect facts, biased outputs, and inconsistent reasoning. They also lack real-world verification ability. Outputs should always be validated for critical tasks. They are not suitable for legal, medical, or financial decisions without expert review. Ethically, they should be used as assistants, not final authorities. Responsible usage requires transparency and fact-checking.

---
