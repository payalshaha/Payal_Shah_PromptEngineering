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

### Refined  V2 Prompt (Improved with Role + Simplicity)
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
Payal Shah

### Issues Identified
- Too short and abrupt  
- No appreciation for opportunity  
- No relationship-building tone  

---

### V2 Prompt
Write a professional email declining a job offer. Mention appreciation and explain that another opportunity was accepted.

### V2 Output
Dear Hiring Manager,  
Thank you for offering me the position. I appreciate the time and effort invested throughout the hiring process.

After careful consideration, I have accepted another opportunity that aligns with my current goals. I was impressed by your organization and hope our paths cross again in the future.

Best Regards,
Payal Shah

### Issues Identified
- Still lacks warmth  
- No mention of interview experience  
- No future relationship intent  

---

### V3 Prompt (Final)
You are a professional career advisor.

Write a warm and professional email declining a job offer because I accepted a research internship that aligns with my long-term goals.

Include:
- gratitude for the opportunity
- appreciation for the interview experience
- positive comments about the company culture
- interest in future opportunities

Tone: respectful, genuine, and professional.

### Final Output
Dear Hiring Manager,  

Thank you very much for offering me the opportunity to join your organization. I sincerely appreciate the time and effort invested in my interview process and enjoyed learning more about your team and work culture.

After careful consideration, I have decided to accept another opportunity that better aligns with my current academic and career goals. This was a difficult decision because I was genuinely impressed by your organization’s professionalism and welcoming environment.

I truly value the connection we have built during this process and hope to stay in touch for any future opportunities where we may collaborate.

Thank you again for your understanding.

Best regards,  
Payal Shah 

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
You are a marketing copywriter.

Create 5 catchy taglines for an eco-friendly water bottle brand aimed at environmentally conscious university students.

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
You are an award-winning branding consultant.

Generate 10 modern taglines for a sustainable water bottle brand called EcoSip.

Requirements:
- Target audience: Gen Z and university students
- Emphasize sustainability and healthy living
- Keep each tagline under 8 words
- Make them memorable and brandable

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

## 1.3 Role and Context Analysis
Role assignment significantly improved the quality of the responses. When I assigned the model the role of a creative teacher, it generated explanations that were more engaging and appropriate for children. Similarly, assigning the role of a professional career advisor resulted in a more polished and relationship-oriented email.

Context setting also improved the relevance of the outputs. By specifying the target audience, purpose, and tone, the model was able to tailor its responses more effectively. The final outputs felt more focused and aligned with the intended goals than the initial generic responses.

Overall, I observed that role and context prompting reduced ambiguity and helped the model generate content that better matched user expectations.
---

# Part 2: Temperature & Parameter Control (20 Points)

---

# 2.1 Temperature Experimentation (12 Points)

## Selected Task
Explaining the concept of **Photosynthesis**

---


# 🔵 Low Temperature (0.2) – Deterministic Output

### Prompt Used
Explain what photosynthesis is. Plants use sunlight, water, and carbon dioxide to make food.  
(Be precise and consistent)

### Output
Photosynthesis is the process by which green plants make their own food using sunlight, water, and carbon dioxide. This process takes place in the chloroplasts of plant cells. The plant converts these inputs into glucose, which provides energy for growth, and oxygen, which is released into the atmosphere.

### Observations
- Highly factual and structured  
- No creativity or analogies  
- Very precise scientific explanation  
- Best for textbook-style content  

---

# 🟡 Medium Temperature (0.7) – Balanced Output

### Prompt Used
Explain what photosynthesis is. Plants use sunlight, water, and carbon dioxide to make food.

### Output
Photosynthesis is the process by which plants make their own food using sunlight. Plants take in water from the soil and carbon dioxide from the air. With the help of sunlight, they convert these into glucose, which provides energy for growth. Oxygen is released as a by-product, which is essential for humans and animals to breathe.

Photosynthesis is important because it supports life on Earth by providing both food for plants and oxygen for living beings.

### Observations
- Balanced explanation style  
- Clear and easy to understand  
- Includes importance and context  
- Suitable for educational purposes  

---

# 🔴 High Temperature (1.2) – Creative Output

### Prompt Used
Explain what photosynthesis is. Plants use sunlight, water, and carbon dioxide to make food.  
Be creative and explore diverse ideas.

### Output
Photosynthesis is like nature’s invisible kitchen where plants cook their own food using sunlight as energy. Leaves act like tiny solar panels, capturing light and mixing water from the soil with carbon dioxide from the air. This magical process creates glucose, which feeds the plant and helps it grow strong and green.

At the same time, plants release oxygen, making Earth a living, breathing planet full of life. Without photosynthesis, life as we know it would not exist.

### Observations
- Highly creative and descriptive  
- Uses analogy (“nature’s kitchen”)  
- More engaging and story-like  
- Less formal but more memorable  

---

## 📊 Comparison Table

| Feature | Low Temp (0.2) | Medium Temp (0.7) | High Temp (1.2) |
|--------|----------------|-------------------|-----------------|
| Creativity | Very Low | Medium | High |
| Accuracy | Very High | High | High |
| Clarity | High | High | Medium |
| Engagement | Low | Medium | Very High |
| Style | Textbook | Educational | Storytelling |

---

# 2.2 Analysis & Recommendations (8 Points)

### When would you use low temperature?
Low temperature should be used when accuracy and consistency are critical. For example:
- Writing technical documentation or programming code  
- Generating factual answers in science or mathematics  

It ensures that responses are stable and do not include unnecessary creativity or variation.

---

### When would you use high temperature?
High temperature is useful when creativity and originality are important. For example:
- Writing stories, poems, or creative writing tasks  
- Creating marketing slogans or advertising content  

It helps generate diverse and imaginative outputs that feel more engaging.

---

### Which temperature worked best for this task and why?
For explaining photosynthesis, the **medium temperature (0.7)** worked best. It provided a good balance between accuracy and readability. The low temperature was too rigid and textbook-like, while the high temperature was creative but slightly less formal. The medium setting ensured clarity while still being engaging for learning purposes.

---

### Final Insight
Temperature control is important because it directly affects how creative or factual an LLM response will be. Choosing the right setting depends on the task type and desired output style.
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
