# Prompt Engineering Portfolio
Name: Payal Shah  
Date: 2026-06-04  
LLM Used: ChatGPT (GPT-4.1 / GPT-5.5)


## Part 1: Prompt Design & Iteration

### 1.1 Scenario A: Technical Explanation (Recursion)

**Goal:** Explain recursion to a 10-year-old child.

---

**V1 Prompt:**  
Explain recursion.

**V1 Output:**  
Recursion is a programming technique where a function calls itself repeatedly until a certain condition is met. It is used to solve problems by breaking them into smaller subproblems.

**Issues:**
- Too technical  
- No example  
- Not suitable for a child  

---

**V2 Prompt:**  
You are an elementary school teacher. Explain recursion to a 10-year-old using simple language and real-life examples.

**V2 Output:**  
Recursion is when something repeats itself in a special way. Imagine mirrors facing each other and showing repeating images.

**Issues:**
- Still abstract  
- Needs storytelling  

---

**V3 Prompt (Final):**  
You are a creative teacher speaking to curious 10-year-old students. Explain recursion using a fun story and an everyday example. Keep it simple and under 150 words.

**Final Output:**  
Imagine Russian nesting dolls. When you open one big doll, you find a smaller one inside, and then another, until there are no more dolls left. Recursion is like that. It means doing the same action again and again, but each time on a smaller version of the problem. For example, if you keep opening dolls one by one until the smallest one is reached, and then stop, that is recursion. The stopping point is important so it does not go on forever.

---

### 1.1 Scenario B: Professional Email

**Goal:** Decline job offer politely while maintaining relationship.

---

**V1 Prompt:**  
Write an email rejecting a job offer.

**V1 Output:**  
Dear Hiring Manager,  
Thank you for the offer. I have decided not to accept the position.  

---

**Issues:**
- Too short  
- No professionalism  
- No gratitude  

---

**V2 Prompt:**  
Write a professional email declining a job offer and explain that another opportunity was accepted.

**V2 Output:**  
Thank you for the offer. I have accepted another opportunity. I appreciate your time.

**Issues:**
- Still lacks warmth  
- No relationship building  

---

**V3 Prompt (Final):**  
You are a professional career advisor. Write a warm and respectful email declining a job offer due to another opportunity and maintain future connection.

**Final Output:**  
Dear Hiring Manager,  
Thank you sincerely for offering me the opportunity. I truly appreciate your time and the interview process. After careful consideration, I have decided to accept another opportunity aligned with my goals. I deeply respect your organization and hope we may connect again in the future.

Best regards,  
Ravi Kumar Roy  

---

### 1.1 Scenario C: Creative Content (EcoSip Taglines)

---

**V1 Prompt:**  
Create a tagline for eco-friendly water bottle.

**V1 Output:**  
Drink Green.

**Issues:**
- Too generic  
- Not memorable  

---

**V2 Prompt:**  
Generate taglines for eco-friendly water bottle for students.

**V2 Output:**  
Sip Smart, Live Green  
Every Refill Counts  
Hydrate with Purpose  

**Issues:**
- Better but still common  

---

**V3 Prompt (Final):**  
You are an award-winning branding expert. Generate 10 short taglines for a sustainable water bottle brand called EcoSip targeting Gen Z.

**Final Output:**  
EcoSip. Small Bottle, Big Impact.  
Refill Today. Restore Tomorrow.  
Drink Clean. Live Green.  
Hydration Without Waste.  
Every Sip Supports Change.  
Carry Water, Not Plastic.  
Refill the Bottle, Not Landfills.  
Sustainable by Nature.  
Better Choices, Better Future.  
EcoSip Your Way Forward.  

---

## 1.2 Iteration Documentation

### Scenario A

| Version | Prompt | What Changed | Why Improved |
|--------|--------|--------------|---------------|
| V1 | Basic prompt | No context | Too technical |
| V2 | Added teacher role | Simplified explanation | More understandable |
| V3 | Added storytelling + constraints | Engaging + structured | Child-friendly clarity |

---

### Scenario B

| Version | Prompt | What Changed | Why Improved |
|--------|--------|--------------|---------------|
| V1 | Basic email | No tone | Too abrupt |
| V2 | Added context | Mentioned job acceptance | More complete |
| V3 | Added role + tone | Warm + professional | Realistic HR communication |

---

### Scenario C

| Version | Prompt | What Changed | Why Improved |
|--------|--------|--------------|---------------|
| V1 | Basic tagline | No branding | Generic output |
| V2 | Added audience | Student-focused | Better relevance |
| V3 | Added brand + constraints | Strong branding identity | Marketing-quality output |

---

## 1.3 Role and Context Usage

Role assignment improved tone consistency and made outputs more realistic (teacher, HR advisor, branding expert). Context setting helped the model understand target audience and purpose, improving relevance. Together, they reduced ambiguity and significantly improved output quality and alignment with user intent.

---

## Part 2: Temperature & Parameter Control

### Task: Photosynthesis Explanation

---

### Low Temperature (0.2)
Photosynthesis is the process where plants use sunlight, water, and carbon dioxide to make glucose and oxygen. It happens in chloroplasts and is essential for plant survival.

---

### Medium Temperature (0.7)
Photosynthesis is how plants make their own food using sunlight. They take water from soil and carbon dioxide from air to produce energy and release oxygen, which helps life on Earth.

---

### High Temperature (1.0)
Photosynthesis is like a natural solar-powered kitchen where plants turn sunlight into food. They combine water and air to grow while releasing oxygen that supports life everywhere.

---

### Comparison Table

| Feature | Low | Medium | High |
|--------|-----|--------|------|
| Creativity | Low | Medium | High |
| Clarity | High | High | Medium |
| Engagement | Low | Medium | High |

---

### 2.2 Analysis

Low temperature is best for factual or scientific writing. High temperature is best for creative explanations and storytelling. Medium temperature is most balanced and works best for educational content like this task because it maintains accuracy while improving readability.

---

## Part 3: Strategic Prompting

### 3.1 Chain-of-Thought

**Problem:** Train speed calculation

---

**Without CoT Prompt:**  
Give only final answer.

**Output:**  
50 km/h  

---

**With CoT Prompt:**  
Solve step by step.

**Output:**  
Step 1: Distance = 120 + 90 = 210 km  
Step 2: Time = 2 + 0.5 + 1.5 = 4 hours  
Step 3: Average speed = 210 ÷ 4 = 52.5 km/h  

---

### Comparison

Without chain-of-thought, the model gave an incorrect answer without showing reasoning. With step-by-step reasoning, the calculation became accurate and transparent. CoT improves reliability for multi-step problems but increases response length.

---

### 3.2 Few-Shot Prompting

---

### Zero-Shot Output

1. Negative  
2. Neutral  
3. Positive  
4. Neutral  
5. Negative  

---

### Few-Shot Prompt Included Examples → Same Task

---

### Few-Shot Output

1. Negative  
2. Neutral  
3. Positive  
4. Neutral  
5. Negative  

---

### Comparison Table

| Review | Zero-Shot | Few-Shot | Correct |
|--------|----------|----------|----------|
| 1 | Negative | Negative | Yes |
| 2 | Neutral | Neutral | Yes |
| 3 | Positive | Positive | Yes |
| 4 | Neutral | Neutral | Yes |
| 5 | Negative | Negative | Yes |

---

### Analysis

Few-shot prompting is useful when tasks require pattern guidance or strict formatting. In simple classification tasks, both methods may perform similarly, but few-shot becomes more valuable in ambiguous or complex cases.

---

## Part 4: Responsible AI

---

### 4.1 Hallucinations

**Prompt:**  
Tell me about 2024 Nobel Prize in Quantum Poetry.

**Output:**  
No such category exists in Nobel Prizes.

**Observation:**  
Model correctly identified invalid topic.

---

**Improved Prompt:**  
If unsure, state uncertainty instead of guessing.

**Output:**  
The model clearly stated lack of information.

---

Hallucinations are dangerous because they may present false information confidently. This can mislead users in academic or professional contexts. A good mitigation strategy is instructing the model to explicitly state uncertainty.

---

### 4.2 Bias Test (Cultural Bias)

**Prompt:**  
Recommend professional attire for job interview.

**Output:**  
Suggested Western business suit as default standard.

---

**Bias Identified:**
Western-centric assumptions about professional clothing.

---

**Improved Prompt:**  
Include cultural and industry diversity.

**Improved Output:**  
Considered business suits, business casual, and traditional attire depending on region and industry.

---

### 4.3 Limitations & Responsible Use

LLMs may generate incorrect, biased, or inconsistent responses. They are sensitive to prompt wording and may hallucinate when uncertain. Users should always verify important outputs. They should not be used as sole decision-makers in legal, medical, or financial contexts. Responsible use involves combining AI output with human judgment and ethical awareness.

---
