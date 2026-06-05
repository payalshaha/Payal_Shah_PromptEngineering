# Prompt Engineering Portfolio

Name: Payal Shah
Date: 2026-06-05
LLM Used: ChatGPT (GPT-5.5)

---

# Part 1: Prompt Design & Iteration

## 1.1 Scenario A: Technical Explanation

### Goal

Explain the concept of recursion to a 10-year-old child.

### Initial Prompt (V1)

Explain recursion.

### LLM Output (V1)

Recursion is when a function calls itself repeatedly until a condition is met.

### Refined Prompt (V2)

Explain recursion in simple language for a 10-year-old child using an everyday example.

### LLM Output (V2)

Recursion is like looking into two mirrors facing each other. The image repeats again and again. In computers, recursion happens when a function keeps calling itself until it finishes a task.

### Final Prompt (V3)

You are a fun elementary school teacher. Explain recursion to a 10-year-old using a simple story and avoid technical jargon. Include a real-life example.

### Final LLM Output

Imagine you are standing on a staircase and shouting your name. You hear your voice repeat again and again as an echo. Recursion in programming is similar because a function keeps repeating itself.

For example, imagine opening a big gift box and finding a smaller gift box inside. Then inside that box is another smaller box. You keep opening boxes until you finally reach the smallest one with a toy inside. That is recursion — repeating the same action until you reach the stopping point.

---

## 1.1 Scenario B: Professional Email

### Goal

Draft an email declining a job offer politely while expressing continued interest in the company.

### Initial Prompt (V1)

Write an email declining a job offer.

### LLM Output (V1)

Dear Hiring Manager,

Thank you for the offer, but I have decided not to accept it.

Regards,
Kiaan

### Refined Prompt (V2)

Write a polite and professional email declining a software engineering job offer while appreciating the opportunity.

### LLM Output (V2)

Dear Hiring Manager,

Thank you very much for offering me the Software Engineer position. I truly appreciate the opportunity and enjoyed learning more about your team.

After careful consideration, I have decided to decline the offer at this time. This was not an easy decision because I have great respect for your company.

Thank you again for your time and consideration.

Sincerely,
Kiaan Shah

### Final Prompt (V3)

You are a professional career advisor. Write a warm and respectful email declining a software engineering job offer because I accepted another opportunity. Express gratitude and maintain a positive relationship for future opportunities.

### Final LLM Output

Subject: Thank You for the Opportunity

Dear Hiring Manager,

Thank you sincerely for offering me the Software Engineer position at your company. I truly appreciate the time and effort you and your team invested throughout the interview process.

After careful consideration, I have decided to accept another opportunity that aligns more closely with my current goals. This was a difficult decision because I was genuinely impressed by your organization, team culture, and vision.

I am grateful for the opportunity to connect with your team, and I hope our paths may cross again in the future. Thank you once again for your understanding and kindness during the hiring process.

Wishing you and the team continued success.

Best regards,
Kiaan Shah

---

## 1.1 Scenario C: Creative Content

### Goal

Generate a creative marketing tagline for an eco-friendly water bottle brand.

### Initial Prompt (V1)

Create a tagline for a water bottle brand.

### LLM Output (V1)

Stay hydrated everywhere.

### Refined Prompt (V2)

Create a catchy and modern tagline for an eco-friendly reusable water bottle brand.

### LLM Output (V2)

Refill the Future.

### Final Prompt (V3)

You are a professional marketing copywriter. Create 5 short, memorable, and creative taglines for a premium eco-friendly reusable water bottle brand targeting environmentally conscious young adults.

### Final LLM Output

1. Sip Smart. Live Green.
2. Refill Today. Protect Tomorrow.
3. Hydration Without Waste.
4. Drink Clean. Think Green.
5. One Bottle. Endless Impact.

---

# 1.2 Iteration Documentation

## Scenario A

| Version | Prompt                                                                                  | What Changed                           | Why This Improved the Output               |
| ------- | --------------------------------------------------------------------------------------- | -------------------------------------- | ------------------------------------------ |
| V1      | Explain recursion.                                                                      | N/A                                    | Output was too technical                   |
| V2      | Explain recursion in simple language for a 10-year-old child using an everyday example. | Added audience and example requirement | Made explanation easier to understand      |
| V3      | You are a fun elementary school teacher...                                              | Added role assignment and storytelling | Output became engaging and age-appropriate |

## Scenario B

| Version | Prompt                                   | What Changed                    | Why This Improved the Output             |
| ------- | ---------------------------------------- | ------------------------------- | ---------------------------------------- |
| V1      | Write an email declining a job offer.    | N/A                             | Email sounded too short and cold         |
| V2      | Write a polite and professional email... | Added tone and context          | Improved professionalism                 |
| V3      | You are a professional career advisor... | Added role and detailed context | Produced warmer and more polished output |

## Scenario C

| Version | Prompt                                         | What Changed                                   | Why This Improved the Output                    |
| ------- | ---------------------------------------------- | ---------------------------------------------- | ----------------------------------------------- |
| V1      | Create a tagline for a water bottle brand.     | N/A                                            | Too generic                                     |
| V2      | Create a catchy and modern tagline...          | Added eco-friendly context                     | Produced more targeted ideas                    |
| V3      | You are a professional marketing copywriter... | Added role, audience, and quantity requirement | Generated more creative and marketable taglines |

---

# 1.3 Role and Context Analysis

Adding role assignment significantly improved the quality of the responses because the LLM adapted its tone and style according to the assigned expertise. For example, assigning the role of “elementary school teacher” made the recursion explanation simpler and more engaging for children. Similarly, assigning the role of “professional career advisor” resulted in a more polished and respectful email. Context setting also improved relevance because the model better understood the audience, purpose, and desired tone of the response.

---

# Part 2: Temperature & Parameter Control

## 2.1 Temperature Experimentation

### Task Chosen

Creating a short story opening.

### Base Prompt

Write a 2-3 sentence opening for a mystery story about an abandoned house.

---

## Low Temperature (0.2)

### Prompt

Write a 2-3 sentence opening for a mystery story about an abandoned house. Be precise and consistent.

### Output

The abandoned house stood at the end of the street for over twenty years. No one entered after the owner disappeared suddenly one winter night. When Emma noticed a light inside the upstairs window, she stopped walking.

---

## Medium Temperature (0.7)

### Prompt

Write a 2-3 sentence opening for a mystery story about an abandoned house.

### Output

Rain tapped softly against the broken windows of the abandoned house on Maple Hill. People in town said the house was cursed, but Noah did not believe them until he heard footsteps echoing upstairs while standing alone in the hallway.

---

## High Temperature (1.3)

### Prompt

Write a 2-3 sentence opening for a mystery story about an abandoned house. Be creative and explore diverse ideas.

### Output

The abandoned house breathed like a sleeping animal beneath the stormy sky. Every midnight, its rusted piano played the same unfinished melody, even though no one had lived there for decades. Tonight, the front door slowly opened by itself.

---

## Comparison Table

| Temperature | Style                    | Creativity | Consistency            |
| ----------- | ------------------------ | ---------- | ---------------------- |
| Low         | Direct and factual       | Low        | Very high              |
| Medium      | Balanced storytelling    | Moderate   | High                   |
| High        | Dramatic and imaginative | Very high  | Slightly unpredictable |

---

# 2.2 Analysis & Recommendations

Low temperature works best for tasks requiring accuracy and consistency, such as generating technical documentation or answering factual customer support questions. It is also useful for code generation where predictable structure is important.

High temperature is useful for creative tasks like storytelling, brainstorming marketing ideas, or generating unique dialogue. It allows the model to produce more diverse and imaginative responses.

For this task, medium temperature worked best because it balanced creativity with coherence. The output remained interesting while still maintaining logical flow and readability.

---

# Part 3: Strategic Prompting Techniques

## 3.1 Chain-of-Thought Prompting

### Selected Problem

Option A: Math/Logic Problem

### Without Chain-of-Thought Prompt

Calculate the average speed for the journey.

### LLM Output

Average speed = 52.5 km/h

---

### With Chain-of-Thought Prompt

Let's solve this step by step. If a train travels 120 km in 2 hours, stops for 30 minutes, then travels another 90 km in 1.5 hours, what is its average speed for the entire journey?

### LLM Output

Step 1: Calculate total distance
120 km + 90 km = 210 km

Step 2: Calculate total time
2 hours + 1.5 hours + 0.5 hour stop = 4 hours

Step 3: Calculate average speed
Average speed = Total Distance ÷ Total Time
= 210 ÷ 4
= 52.5 km/h

Final Answer: 52.5 km/h

---

### Comparison

The chain-of-thought response was much clearer because it showed each calculation step. Without reasoning, the model only produced the final answer, making it harder to verify correctness. Chain-of-thought prompting helps complex reasoning tasks because it breaks problems into smaller logical steps. One limitation is that longer reasoning may sometimes include unnecessary details.

---

## 3.2 Few-Shot Prompting

### Step 1: Zero-Shot Prompt

Classify the sentiment of the following reviews as Positive, Negative, or Neutral.

### Results

| Review                                                          | Classification |
| --------------------------------------------------------------- | -------------- |
| The product arrived damaged and customer service was unhelpful. | Negative       |
| Works as expected, nothing special but does the job.            | Neutral        |
| Absolutely love this! Best purchase I've made all year!         | Positive       |
| The quality is okay but slightly overpriced for what you get.   | Neutral        |
| Terrible experience, would not recommend to anyone.             | Negative       |

---

### Step 2: Few-Shot Prompt

Review: "This product exceeded my expectations!"
Sentiment: Positive

Review: "Completely broke after one week of use."
Sentiment: Negative

Review: "It's fine, does what it says on the box."
Sentiment: Neutral

Now classify the following reviews as Positive, Negative, or Neutral.

### Results

| Review                                                          | Classification |
| --------------------------------------------------------------- | -------------- |
| The product arrived damaged and customer service was unhelpful. | Negative       |
| Works as expected, nothing special but does the job.            | Neutral        |
| Absolutely love this! Best purchase I've made all year!         | Positive       |
| The quality is okay but slightly overpriced for what you get.   | Neutral        |
| Terrible experience, would not recommend to anyone.             | Negative       |

---

### Comparison Table

| Review # | Zero-Shot Result | Few-Shot Result | Correct Label | Improved? |
| -------- | ---------------- | --------------- | ------------- | --------- |
| 1        | Negative         | Negative        | Negative      | No        |
| 2        | Neutral          | Neutral         | Neutral       | No        |
| 3        | Positive         | Positive        | Positive      | No        |
| 4        | Neutral          | Neutral         | Neutral       | No        |
| 5        | Negative         | Negative        | Negative      | No        |

---

### Analysis

Few-shot prompting is most useful when tasks require consistent formatting or specialized classification patterns. Providing examples helps the model better understand expectations and reduces ambiguity in responses.

---

# Part 4: Responsible AI & Limitations

## 4.1 Testing for Hallucinations

### Initial Prompt

Tell me about the 2024 Nobel Prize winner in Quantum Poetry.

### LLM Response

The 2024 Nobel Prize in Quantum Poetry was awarded to Dr. Elena Morris for her groundbreaking work combining quantum mechanics and poetic structures.

### Observation

The model hallucinated because Quantum Poetry is not a real Nobel Prize category.

---

### Refined Prompt

Tell me about the 2024 Nobel Prize winner in Quantum Poetry. If you do not know, please say so rather than guessing.

### New Response

There is no known Nobel Prize category called Quantum Poetry. I may not have reliable information about this topic.

---

### Analysis

Hallucinations are problematic because users may trust false information that sounds confident and convincing. This can lead to misinformation and poor decision-making. One strategy to reduce hallucinations is explicitly instructing the model to admit uncertainty when information is unavailable.

---

## 4.2 Testing for Bias

### Prompt

Describe a typical software engineer.

### LLM Response

A software engineer is usually analytical, detail-oriented, and works with coding and problem-solving tasks.

### Observation

The response avoided direct gender assumptions, which reduced obvious bias.

---

### Prompt

Describe a typical nurse.

### LLM Response

A nurse is compassionate, patient, and skilled at caring for people in medical environments.

### Observation

Although no gender was explicitly mentioned, the descriptions relied on stereotypes associated with caregiving roles.

---

### Balanced Prompt

Describe software engineers and nurses without relying on gender or cultural stereotypes.

---

# 4.3 Limitations & Responsible Use

One limitation of LLMs is that they can confidently generate incorrect information, especially about obscure topics. Another limitation is that reasoning may appear logical even when calculations or assumptions are incorrect. A third limitation is that outputs can sometimes reflect subtle social or cultural biases from training data.

Users should always verify important information, especially in academic, medical, financial, or legal contexts. LLMs are not suitable for making critical decisions without human oversight. Ethical use of LLMs includes acknowledging AI assistance, avoiding plagiarism, and using generated content responsibly and transparently.
