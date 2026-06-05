# Prompt Engineering Portfolio
Name: Payal Shah  
Date: 2026-06-04  
LLM Used: ChatGPT (GPT-4.1 / GPT-5.5)


---

# Part 1: Prompt Design & Iteration

## 1.1 Scenario A: Technical Explanation (Recursion)

### Goal
To explain the concept of recursion in a way that is understandable for a 10-year-old child using progressive prompt refinement.

---

### V1 Prompt (Initial Attempt)
Explain recursion.

### V1 Output
Recursion is a programming technique where a function calls itself repeatedly until a stopping condition is met. It is commonly used to solve problems by breaking them into smaller subproblems.

### Issues Identified
- Too technical for a child audience  
- Uses programming terminology like “function” and “subproblems”  
- No analogy or real-life explanation  
- Difficult to visualize concept  

---

### V2 Prompt (Improved with Role + Simplicity)
You are an elementary school teacher. Explain recursion to a 10-year-old child using simple language and real-life examples.

### V2 Output
Recursion is when something keeps repeating in a special way. Imagine two mirrors facing each other and showing endless reflections. That is similar to recursion.

### Issues Identified
- Still abstract for children  
- Lacks storytelling or engagement  
- Needs clearer stopping condition explanation  

---

### V3 Prompt (Final Optimized Version)
You are a creative and friendly teacher speaking to 10-year-old students. Explain recursion using a fun story, simple language, and an everyday example. Keep it under 150 words and include the idea of stopping condition.

### Final Output
Imagine you have Russian nesting dolls. When you open the biggest doll, you find a smaller one inside, and inside that another smaller one, and so on. This continues until you reach the smallest doll, which cannot be opened anymore.

Recursion is like this process. It means doing the same action again and again, but each time on a smaller version of the problem. For example, opening one doll leads to another smaller doll inside it.

The important part is the stopping point. If there was no smallest doll, you would keep opening forever. That stopping point is what makes recursion work correctly.

---

## 1.2 Iteration Documentation (Scenario A)

| Version | Prompt | What Changed | Why It Improved |
|--------|--------|--------------|-----------------|
| V1 | Basic instruction | No role or context | Output too technical |
| V2 | Added teacher role | Simplified explanation | More child-friendly |
| V3 | Added storytelling + constraints | Improved structure and clarity | Highly engaging and understandable |

---

## 1.3 Role and Context Usage

Role assignment significantly improved output quality by giving the model a defined persona (teacher), which controlled tone and complexity. Context such as “10-year-old child” ensured age-appropriate simplification. The addition of storytelling in V3 made the explanation more engaging and memorable. Overall, role and context reduced ambiguity and improved communication effectiveness.

---

## 1.1 Scenario B: Professional Email (Job Offer Rejection)

### Goal
To generate a professional and polite email declining a job offer while maintaining future professional relationships.

---

### V1 Prompt
Write an email rejecting a job offer.

### V1 Output
Dear Hiring Manager,  
Thank you for the offer. I have decided not to accept the position.  

Sincerely,  
[Name]

### Issues Identified
- Too short and abrupt  
- No appreciation for opportunity  
- No relationship-building tone  

---

### V2 Prompt
Write a professional email declining a job offer. Mention appreciation and explain that another opportunity was accepted.

### V2 Output
Dear Hiring Manager,  
Thank you for the opportunity. I have accepted another position. I appreciate your time.

### Issues Identified
- Still lacks warmth  
- No mention of interview experience  
- No future relationship intent  

---

### V3 Prompt (Final)
You are a professional career advisor. Write a warm, respectful email declining a job offer because I accepted another opportunity. Include gratitude, appreciation for the interview process, and interest in future collaboration.

### Final Output
Dear Hiring Manager,  

Thank you very much for offering me the opportunity to join your organization. I sincerely appreciate the time and effort invested in my interview process and enjoyed learning more about your team and work culture.

After careful consideration, I have decided to accept another opportunity that better aligns with my current academic and career goals. This was a difficult decision because I was genuinely impressed by your organization’s professionalism and welcoming environment.

I truly value the connection we have built during this process and hope to stay in touch for any future opportunities where we may collaborate.

Thank you again for your understanding.

Best regards,  
Ravi Kumar Roy  

---

## 1.2 Iteration Documentation (Scenario B)

| Version | Prompt | What Changed | Why It Improved |
|--------|--------|--------------|-----------------|
| V1 | Basic rejection email | No tone control | Too abrupt |
| V2 | Added explanation | Included job acceptance | More complete |
| V3 | Added role + tone | Added warmth and professionalism | Real-world HR standard |

---

## 1.1 Scenario C: Creative Content (EcoSip Taglines)

### Goal
Generate creative and brandable marketing taglines for an eco-friendly water bottle brand targeting Gen Z.

---

### V1 Prompt
Create a tagline for eco-friendly water bottle.

### V1 Output
Drink Green.

### Issues Identified
- Too generic  
- Not brand-specific  
- No emotional appeal  

---

### V2 Prompt
Create 5 marketing taglines for an eco-friendly water bottle brand targeting students.

### V2 Output
Sip Smart, Live Green  
Every Refill Counts  
Hydrate with Purpose  
Reuse Today, Save Tomorrow  
Drink Better, Live Better  

### Issues Identified
- Improved but still common phrases  
- Lacks strong brand identity  

---

### V3 Prompt (Final)
You are an award-winning branding strategist. Create 10 short, catchy, and memorable taglines for a sustainable water bottle brand called EcoSip. Target Gen Z students and emphasize sustainability and lifestyle impact.

### Final Output
EcoSip — Small Bottle, Big Impact  
Refill Today, Restore Tomorrow  
Drink Clean, Live Green  
Hydration Without Waste  
Every Sip Matters  
Carry Water, Not Plastic  
Refill the Future  
Sustainable Starts with a Sip  
Better Choices, Better Planet  
EcoSip Your Way Forward  

---

## 1.2 Iteration Documentation (Scenario C)

| Version | Prompt | What Changed | Why It Improved |
|--------|--------|--------------|-----------------|
| V1 | Simple request | No branding | Generic output |
| V2 | Added audience | Student focus | Better relevance |
| V3 | Added branding identity | Strong marketing tone | Professional-level output |

---

# Part 2: Temperature & Parameter Control

## Task: Explanation of Photosynthesis

---

### Low Temperature (0.2)
Photosynthesis is the process by which plants use sunlight, water, and carbon dioxide to produce glucose and oxygen. It occurs in chloroplasts and is essential for plant survival and energy production.

---

### Medium Temperature (0.7)
Photosynthesis is the process where plants make their own food using sunlight. They take carbon dioxide from air and water from soil to produce glucose, which gives them energy, and release oxygen into the atmosphere, which is essential for life.

---

### High Temperature (1.0)
Photosynthesis is like nature’s solar-powered kitchen where plants convert sunlight into food. They take water from the soil and carbon dioxide from the air, transforming them into energy-rich glucose while releasing oxygen that keeps life on Earth alive.

---

## Comparison Table

| Feature | Low | Medium | High |
|--------|-----|--------|------|
| Creativity | Low | Medium | High |
| Clarity | High | High | Medium |
| Engagement | Low | Medium | High |
| Accuracy | Very High | High | High |

---

## 2.2 Analysis & Recommendations

Low temperature is best suited for technical documentation, scientific writing, and tasks requiring precision and consistency. High temperature is more suitable for creative writing, storytelling, and marketing content where originality is important. Medium temperature is ideal for educational content because it balances clarity with engagement. In this task, medium temperature provided the best explanation as it maintained accuracy while improving readability and understanding.

---

# Part 3: Strategic Prompting Techniques

## 3.1 Chain-of-Thought Prompting

### Problem
Train travels 120 km in 2 hours, stops for 30 minutes, then travels 90 km in 1.5 hours. Find average speed.

---

### Without Chain-of-Thought

**Prompt:**  
Give only the final answer.

**Output:**  
52.5 km/h

---

### With Chain-of-Thought

**Prompt:**  
Solve step by step with full reasoning.

**Output:**  
Step 1: Total distance = 120 + 90 = 210 km  
Step 2: Total time = 2 + 0.5 + 1.5 = 4 hours  
Step 3: Average speed = 210 ÷ 4 = 52.5 km/h  

---

### Comparison

Without chain-of-thought, the model directly produces an answer without showing reasoning. With step-by-step reasoning, the model breaks the problem into smaller parts, improving transparency and accuracy. Chain-of-thought is especially useful for multi-step reasoning problems. However, it increases response length and computational cost.

---

## 3.2 Few-Shot Prompting

### Zero-Shot Prompt
Classify sentiment of reviews as Positive, Negative, or Neutral.

### Zero-Shot Output
1. Negative  
2. Neutral  
3. Positive  
4. Neutral  
5. Negative  

---

### Few-Shot Prompt (with examples)
Review: “I love this product” → Positive  
Review: “It broke quickly” → Negative  
Review: “It is okay” → Neutral  

Now classify:

### Few-Shot Output
1. Negative  
2. Neutral  
3. Positive  
4. Neutral  
5. Negative  

---

## Comparison Table

| Review | Zero-Shot | Few-Shot | Correct Label | Improved |
|--------|----------|----------|--------------|----------|
| 1 | Negative | Negative | Negative | No |
| 2 | Neutral | Neutral | Neutral | No |
| 3 | Positive | Positive | Positive | No |
| 4 | Neutral | Neutral | Neutral | No |
| 5 | Negative | Negative | Negative | No |

---

### Analysis
Few-shot prompting is helpful when tasks require structured behavior or pattern learning. In simple classification tasks, both zero-shot and few-shot perform similarly. However, few-shot becomes highly valuable in ambiguous or domain-specific tasks.

---

# Part 4: Responsible AI & Limitations

## 4.1 Hallucinations

### Prompt
Tell me about the 2024 Nobel Prize in Quantum Poetry.

### Output
No such Nobel Prize category exists. The Nobel Prize does not include Quantum Poetry.

---

### Observation
The model correctly identified that the topic was invalid and avoided hallucination.

---

### Improved Prompt
If unsure, clearly state uncertainty instead of guessing.

### Output
The model explicitly stated lack of verified information.

---

### Explanation
Hallucinations are problematic because they may present false information confidently. This can mislead users in academic or professional contexts. A key mitigation strategy is instructing models to express uncertainty and avoid fabrication.

---

## 4.2 Bias Testing (Cultural Bias)

### Prompt
Recommend professional attire for job interview.

### Output
Suggested Western business attire such as suits and formal clothing.

---

### Bias Identified
The response reflects Western corporate culture as the default standard and does not initially consider global or cultural diversity.

---

### Improved Prompt
Recommend professional attire considering different cultures, industries, and workplace norms.

### Improved Output
Professional attire varies by region and industry. Corporate roles may require formal business suits, while startups may prefer business casual. In some cultures, traditional attire is also acceptable when it is formal and appropriate.

---

### Explanation
The improved prompt leads to a more inclusive and globally relevant response, reducing cultural bias and increasing fairness.

---

## 4.3 Limitations & Responsible Use

Large language models have several limitations. They may generate incorrect or hallucinated information when unsure. They are highly sensitive to prompt wording, which can significantly change outputs. They may also reflect biases present in training data. Therefore, users must always verify important outputs. LLMs should not be used as sole decision-makers in critical domains such as healthcare, law, or finance. Ethical use involves transparency, fact-checking, and human oversight.

---
