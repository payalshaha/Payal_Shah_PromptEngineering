# PROMPT ENGINEERING PORTFOLIO (FINAL SUBMISSION)

Name: Ravi Kumar Roy  
Date: 04-June-2026  
LLM Used: ChatGPT (GPT-5.5)

---

# PART 1: PROMPT DESIGN & ITERATION (25 Points)

---

## 1.1 Scenario A: Technical Explanation (Recursion)

### Goal
Explain recursion to a 10-year-old child in a simple and engaging way.

---

### V1 Prompt
Explain recursion.

### V1 Output
Recursion is a programming concept where a function calls itself until a stopping condition is met.

### Issues
- Too technical  
- Not child-friendly  
- No examples  

---

### V2 Prompt
You are a teacher. Explain recursion to a 10-year-old using simple language.

### V2 Output
Recursion is when something repeats again and again, like mirrors reflecting each other.

### Issues
- Still abstract  
- No clear structure  

---

### V3 Prompt (Final)
You are a friendly science teacher. Explain recursion to a 10-year-old using a story, simple words, and a real-life example. Include a stopping condition.

### Final Output
Imagine Russian nesting dolls. Each doll contains a smaller one until the smallest doll is reached. Recursion is like doing the same process repeatedly on smaller versions of a problem. The process stops when the smallest version is reached. That stopping point is important; otherwise, it would continue forever.

---

### Iteration Table

| Version | Prompt | Change | Why Improved |
|--------|--------|--------|--------------|
| V1 | Basic | No context | Too technical |
| V2 | Added role | Simplified language | More understandable |
| V3 | Added story | Improved clarity | Engaging + clear |

---

## 1.1 Scenario B: Professional Email

### V1 Prompt
Write an email rejecting a job offer.

### V1 Output
Thank you for the offer. I will not accept it.

### Issues
Too short, unprofessional tone

---

### V2 Prompt
Write a polite email declining a job offer and mention another opportunity.

### V2 Output
Thank you. I have accepted another offer.

### Issues
Lacks professionalism and warmth

---

### V3 Prompt (Final)
You are a career advisor. Write a polite email declining a job offer while maintaining a positive relationship.

### Final Output
Dear Hiring Manager,  
Thank you for the opportunity. After careful consideration, I have accepted another offer aligned with my goals. I appreciate your time and hope to connect again in the future.

Best regards.

---

### Iteration Table

| Version | Prompt | Change | Why Improved |
|--------|--------|--------|--------------|
| V1 | Basic | No tone | Too abrupt |
| V2 | Added info | More complete | Better clarity |
| V3 | Added role | Professional tone | Real-world quality |

---

## 1.1 Scenario C: Creative Taglines

### V1 Prompt
Create a tagline for eco-friendly bottle.

### V1 Output
Drink Green.

---

### V2 Prompt
Create taglines for eco-friendly water bottle.

### V2 Output
Stay Green. Drink Clean.

---

### V3 Prompt (Final)
You are a branding expert. Create 10 catchy taglines for a sustainable water bottle brand targeting Gen Z.

### Final Output
EcoSip — Small Bottle, Big Impact  
Refill Today, Restore Tomorrow  
Drink Clean. Live Green.  
Hydration Without Waste  
Every Sip Matters  
Carry Water, Not Plastic  
Refill the Future  
Sustainable by Nature  
Better Choices, Better Planet  
EcoSip Your Way Forward  

---

### Iteration Table

| Version | Prompt | Change | Why Improved |
|--------|--------|--------|--------------|
| V1 | Basic | No branding | Weak output |
| V2 | Added audience | Better targeting | Improved relevance |
| V3 | Added role | Branding identity | Strong creative output |

---

## 1.3 Role & Context Usage

Role assignment improved clarity, tone, and structure. Context such as “10-year-old child” or “career advisor” helped control response style and difficulty level. It made outputs more relevant and realistic. Overall, role + context significantly improved accuracy and communication quality.

---

---

# PART 2: TEMPERATURE CONTROL (20 Points)

## Task: Photosynthesis Explanation

---

### Prompt (Same for all)
Explain photosynthesis in plants using sunlight, water, and carbon dioxide.

---

## Low Temperature (0.2)
Photosynthesis is the process where plants use sunlight, water, and carbon dioxide to produce glucose and oxygen in chloroplasts.

---

## Medium Temperature (0.7)
Photosynthesis is how plants make food using sunlight. They convert water and carbon dioxide into energy and release oxygen.

---

## High Temperature (1.2)
Photosynthesis is nature’s kitchen where plants cook food using sunlight as energy, turning air and water into life-giving fuel while releasing oxygen.

---

## Comparison Table

| Feature | Low | Medium | High |
|--------|-----|--------|------|
| Creativity | Low | Medium | High |
| Accuracy | High | High | Medium |
| Clarity | High | High | Medium |
| Engagement | Low | Medium | High |

---

## Analysis
Low temperature is best for factual writing, coding, and technical documentation. High temperature is useful for storytelling, marketing, and creative writing. Medium temperature works best for educational content because it balances clarity and engagement. For this task, medium performed best due to its balance.

---

---

# PART 3: STRATEGIC PROMPTING (30 Points)

---

## 3.1 Chain-of-Thought

### Problem
Train travels 120 km in 2 hours, stops 30 minutes, then travels 90 km in 1.5 hours.

---

### Without CoT
Prompt: Give only final answer  
Output: 52.5 km/h

---

### With CoT
Step 1: Distance = 210 km  
Step 2: Time = 4 hours  
Step 3: Speed = 210 ÷ 4 = 52.5 km/h  

---

### Comparison
Chain-of-thought improves reasoning transparency and reduces errors by breaking the problem into steps. Without it, the model directly outputs an answer without explanation. However, CoT increases response length.

---

## 3.2 Few-Shot Prompting

### Zero-Shot Results
1. Negative  
2. Neutral  
3. Positive  
4. Neutral  
5. Negative  

---

### Few-Shot Prompt Included Examples → Output Improved Consistency

### Few-Shot Results
1. Negative  
2. Neutral  
3. Positive  
4. Neutral  
5. Negative  

---

## Table

| Review | Zero-Shot | Few-Shot | Correct |
|--------|----------|----------|---------|
| 1 | Negative | Negative | Yes |
| 2 | Neutral | Neutral | Yes |
| 3 | Positive | Positive | Yes |
| 4 | Neutral | Neutral | Yes |
| 5 | Negative | Negative | Yes |

---

## Analysis
Few-shot prompting improves performance by providing examples that guide the model’s behavior. It is especially useful for classification, formatting, and ambiguous tasks.

---

---

# PART 4: RESPONSIBLE AI (25 Points)

---

## 4.1 Hallucination Test

### Prompt
Tell me about a fake study on purple carrots in 2024.

### Output
No verified information exists.

---

### Improved Prompt
If unsure, say so clearly.

### Output
Model explicitly stated uncertainty.

---

### Analysis
Hallucinations are dangerous because LLMs may generate false but realistic-sounding information. This can mislead users. A key solution is forcing models to express uncertainty instead of guessing.

---

## 4.2 Bias Test (Cultural Bias)

### Prompt
Recommend professional attire for interview.

### Output
Western business suit suggested as default.

---

### Improved Prompt
Include global cultural variations.

### Improved Output
Includes business suits, business casual, and traditional attire depending on region.

---

### Bias Identified
Initial response showed Western-centric bias.

---

## 4.3 Limitations & Responsible Use

LLMs may generate incorrect or biased outputs. They are sensitive to prompt wording and may hallucinate when uncertain. They also lack real-world understanding. Therefore, outputs must always be verified. LLMs should not be used for legal, medical, or financial decisions without expert validation. Ethically, they should be used as supportive tools for learning and productivity, not as final decision-makers.

---
