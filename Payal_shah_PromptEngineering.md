# PROMPT ENGINEERING PORTFOLIO (FINAL SUBMISSION)

Name: Ravi Kumar Roy  
Date: 04-June-2026  
LLM Used: ChatGPT (GPT-5.5)

---

# PART 1: PROMPT DESIGN & ITERATION (25 Points)

## 1.1 Scenario A: Technical Explanation (Recursion)

### Goal
Explain recursion to a 10-year-old child in a simple and engaging way.

### V1 Prompt
Explain recursion.

### V1 Output
Recursion is a programming concept where a function calls itself until a stopping condition is met.

### V2 Prompt
You are a teacher. Explain recursion to a 10-year-old using simple language.

### V2 Output
Recursion is when something repeats again and again, like mirrors reflecting each other.

### V3 Prompt (Final)
You are a friendly science teacher. Explain recursion to a 10-year-old using a story, simple words, and a real-life example. Include a stopping condition.

### Final Output
Imagine Russian nesting dolls. Each doll contains a smaller one until the smallest doll is reached. Recursion is like doing the same process repeatedly on smaller versions of a problem. The process stops when the smallest version is reached.

---

## 1.2 Iteration Table
| Version | Prompt | Change | Why Improved |
|--------|--------|--------|--------------|
| V1 | Basic | No context | Too technical |
| V2 | Teacher role | Simplified | Better clarity |
| V3 | Story + constraint | Engaging | Best output |

---

## 1.3 Role & Context Usage
Role improved tone and clarity. Context like "10-year-old" ensured simplicity. Storytelling improved understanding.

---

## Scenario B: Email
### V1 Prompt
Write an email rejecting a job offer.

### V3 Prompt
You are a career advisor. Write a polite email declining a job offer.

### Final Output
Dear Hiring Manager,  
Thank you for the opportunity. I have accepted another offer aligned with my goals.

---

## Scenario C: Taglines
EcoSip taglines generated:
- EcoSip — Small Bottle, Big Impact
- Refill Today, Restore Tomorrow
- Drink Clean. Live Green.

---

# PART 2: TEMPERATURE CONTROL (20 Points)

## Prompt
Explain photosynthesis in plants.

### Low (0.2)
Photosynthesis is how plants make food using sunlight, water, and CO2.

### Medium (0.7)
Plants make food using sunlight and release oxygen.

### High (1.2)
Photosynthesis is nature’s kitchen where plants cook food using sunlight.

## Comparison
Low = factual, Medium = balanced, High = creative.

## Analysis
Medium works best for learning.

---

# PART 3: STRATEGIC PROMPTING (30 Points)

## Chain-of-Thought
Distance = 210 km, Time = 4 hours, Speed = 52.5 km/h

CoT improves clarity but increases length.

## Few-shot
Zero-shot less consistent. Few-shot improves classification accuracy.

---

# PART 4: RESPONSIBLE AI (25 Points)

## Hallucination
Model correctly identified unknown fake study.

## Bias
Western attire bias detected and corrected.

## Limitations
LLMs may hallucinate, show bias, and lack real reasoning. Always verify outputs.
