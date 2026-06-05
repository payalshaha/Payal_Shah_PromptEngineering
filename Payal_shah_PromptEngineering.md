# Prompt Engineering Portfolio

Name: Payal Shah
Date: 2026-06-05
LLM Used: ChatGPT (GPT-5.5)

---

# Part 1: Prompt Design & Iteration

---

# 1.1 Three Content Generation Tasks

## Scenario A: Technical Explanation

### Goal

Explain neural networks to a 10-year-old child.

---

## V1 – Initial Prompt

### Prompt

```text
Explain neural networks.
```

### Output

Neural networks are computer systems inspired by the human brain. They consist of layers of interconnected nodes that process information and learn patterns from data.

### Analysis

The explanation was technically correct but too complex for a 10-year-old because it used advanced terminology without simple examples.

---

## V2 – Refined Prompt

### Prompt

```text
Explain neural networks to a 10-year-old using simple language and examples.
```

### Output

A neural network is like a smart robot brain that learns from examples. If you show it many pictures of cats, it slowly learns what cats look like.

### Analysis

The explanation became simpler and easier to understand, but it still lacked engagement and creativity.

---

## V3 – Final Prompt

### Prompt

```text
You are a fun science teacher explaining technology to children. Explain neural networks to a 10-year-old using a school-related example and friendly language. Avoid difficult technical words.
```

### Final Output

Imagine your brain learning how to recognize your teacher’s handwriting. At first, it may look confusing, but after seeing it many times, your brain gets better at understanding it.

A neural network works in a similar way. It is a computer system that learns by practicing with lots of examples. If it sees many pictures of dogs and cats, it slowly learns how to tell them apart.

It doesn’t think exactly like a human brain, but it learns patterns just like students learn from practice in school.

---

## Iteration Table

| Version | Prompt                                                                       | What Changed                                          | Why This Improved the Output                            |
| ------- | ---------------------------------------------------------------------------- | ----------------------------------------------------- | ------------------------------------------------------- |
| V1      | Explain neural networks.                                                     | Initial attempt                                       | Output was too technical                                |
| V2      | Explain neural networks to a 10-year-old using simple language and examples. | Added audience and simplicity requirements            | Improved readability                                    |
| V3      | You are a fun science teacher explaining technology to children...           | Added role assignment, context, and tone instructions | Produced a more engaging and child-friendly explanation |

---

# Scenario B: Professional Email

### Goal

Politely decline a job offer while maintaining a positive relationship with the company.

---

## V1 – Initial Prompt

### Prompt

```text
Write an email declining a job offer.
```

### Output

Dear Hiring Manager,

Thank you for the offer, but I have decided not to accept it.

Regards,
Payal Shah

### Analysis

The email was too short and sounded cold and impersonal.

---

## V2 – Refined Prompt

### Prompt

```text
Write a polite professional email declining a job offer while thanking the company.
```

### Output

Dear Hiring Manager,

Thank you very much for offering me the position. I appreciate the opportunity and enjoyed meeting the team. After careful consideration, I have decided to decline the offer.

Thank you again for your time and consideration.

Best regards,
Payal Shah

### Analysis

The email became more professional and polite, but it still lacked warmth and future relationship-building.

---

## V3 – Final Prompt

### Prompt

```text
You are an experienced HR professional helping a candidate write a respectful and professional email. Draft an email declining a job offer politely while expressing gratitude and continued interest in future opportunities with the company.
```

### Final Output

Subject: Thank You for the Opportunity

Dear Hiring Manager,

Thank you sincerely for offering me the opportunity to join your company. I truly appreciate the time and effort invested throughout the interview process and enjoyed learning more about your team and organization.

After careful consideration, I have decided to decline the offer at this time, as I have chosen to pursue another opportunity that aligns more closely with my current goals.

This was not an easy decision because I hold your company in very high regard. I hope we may stay connected, and I would welcome the possibility of working together in the future.

Thank you once again for your kindness and professionalism. I wish you and your team continued success.

Best regards,
Payal Shah

---

## Iteration Table

| Version | Prompt                                                                                                  | What Changed                                            | Why This Improved the Output                         |
| ------- | ------------------------------------------------------------------------------------------------------- | ------------------------------------------------------- | ---------------------------------------------------- |
| V1      | Write an email declining a job offer.                                                                   | Initial prompt                                          | Too brief and impersonal                             |
| V2      | Write a polite professional email declining a job offer while thanking the company.                     | Added tone and gratitude instructions                   | Improved professionalism                             |
| V3      | You are an experienced HR professional helping a candidate write a respectful and professional email... | Added role assignment and relationship-building context | Produced a polished and realistic professional email |

---

# Scenario C: Creative Content

### Goal

Generate a creative marketing tagline for an eco-friendly water bottle brand.

---

## V1 – Initial Prompt

### Prompt

```text
Create a tagline for an eco-friendly water bottle.
```

### Output

“Stay hydrated naturally.”

### Analysis

The tagline was generic and not memorable.

---

## V2 – Refined Prompt

### Prompt

```text
Create a catchy and modern tagline for an eco-friendly reusable water bottle brand aimed at young adults.
```

### Output

“Refill Your Bottle, Refresh the Planet.”

### Analysis

The tagline became more creative and audience-focused, but it could still sound more emotional and brand-oriented.

---

## V3 – Final Prompt

### Prompt

```text
You are a professional brand copywriter creating a slogan for a stylish eco-friendly water bottle startup targeting environmentally conscious young adults. Create 5 short, memorable, modern taglines with an inspiring tone.
```

### Final Output

1. “Drink Clean. Live Green.”
2. “Refill Today. Protect Tomorrow.”
3. “Hydration Meets Sustainability.”
4. “One Bottle. Less Plastic.”
5. “Sip Smart. Save the Planet.”

---

## Iteration Table

| Version | Prompt                                             | What Changed                                               | Why This Improved the Output                    |
| ------- | -------------------------------------------------- | ---------------------------------------------------------- | ----------------------------------------------- |
| V1      | Create a tagline for an eco-friendly water bottle. | Initial prompt                                             | Too broad and generic                           |
| V2      | Create a catchy and modern tagline...              | Added target audience and style                            | Improved creativity                             |
| V3      | You are a professional brand copywriter...         | Added professional role, audience, tone, and output format | Generated stronger and more marketable taglines |

---

# 1.3 Role and Context Usage

Role assignment and context setting significantly improved the quality of outputs. In Scenario A, assigning the role of a “fun science teacher” helped generate a child-friendly explanation with relatable examples. In Scenario B, using the role of an “experienced HR professional” produced a more polished and realistic professional email. In Scenario C, specifying a “professional brand copywriter” and defining the target audience improved the creativity and marketing appeal of the taglines. Overall, adding roles and context helped the LLM better understand the desired tone, audience, and purpose of each task.


# Part 2: Temperature & Parameter Control

---

# 2.1 Temperature Experimentation

## Chosen Task

Creating a short story opening (2–3 sentences)

---

## Base Prompt

```text id="mqwd7v"
Write a 2–3 sentence opening for a science fiction story about a city floating above Earth.
```

---

# Low Temperature Test

## Temperature Value

0.2

## Prompt Used

```text id="oz4mto"
Write a 2–3 sentence opening for a science fiction story about a city floating above Earth. Be precise and consistent.
```

## Output

The floating city of Aeris hovered quietly above Earth, supported by massive anti-gravity engines. Citizens watched the storms below from glass observation decks while engineers carefully maintained the systems keeping the city alive. Every day in Aeris followed strict routines designed to ensure survival.

---

# Medium Temperature Test

## Temperature Value

0.7

## Prompt Used

```text id="u9njw7"
Write a 2–3 sentence opening for a science fiction story about a city floating above Earth.
```

## Output

Far above the clouds, the city of Lumina drifted silently across the sky like a second moon. Its glowing towers reflected sunlight during the day and shimmered like stars at night, hiding the secret that its power source was slowly dying. No one on Earth knew the city even existed.

---

# High Temperature Test

## Temperature Value

1.2

## Prompt Used

```text id="vd5kv4"
Write a 2–3 sentence opening for a science fiction story about a city floating above Earth. Be creative and explore diverse ideas.
```

## Output

The city of Zephyria floated upside down above Earth, suspended by giant blue crystals that sang whenever lightning struck the atmosphere. Children raced through gravity-free gardens while sky whales drifted between neon bridges made of living metal. On the night the stars suddenly disappeared, every clock in the city stopped at exactly 3:17 AM.

---

# Comparison Table

| Temperature  | Style of Output        | Creativity Level | Consistency | Observations                                |
| ------------ | ---------------------- | ---------------- | ----------- | ------------------------------------------- |
| 0.2 (Low)    | Structured and factual | Low              | Very High   | Clear and logical but less imaginative      |
| 0.7 (Medium) | Balanced storytelling  | Moderate         | High        | Creative while still coherent and realistic |
| 1.2 (High)   | Highly imaginative     | Very High        | Medium      | Unique and vivid ideas but less predictable |

---

# 2.2 Analysis & Recommendations

Low temperature settings are best for tasks requiring accuracy, consistency, and reliability. Examples include technical documentation and customer support responses where factual correctness is important. High temperature settings are useful for creative brainstorming and storytelling because they generate more imaginative and unexpected ideas. Examples include writing fiction and generating marketing campaign concepts.

For this task, the medium temperature setting worked best because it balanced creativity with coherence. The output was imaginative and engaging while still remaining easy to understand and logically structured. The high temperature output was very creative, but it introduced unusual ideas that could become harder to manage in longer writing tasks.

# Part 3: Strategic Prompting Techniques

---

# 3.1 Chain-of-Thought Prompting

## Selected Problem: Option B – Multi-Step Reasoning

### Problem

A company has 150 employees. 60% work in engineering, 25% in sales, and the rest in operations. If the company plans to hire 20% more engineers and 10% more sales people, how many total employees will there be after hiring?

---

# Without Chain-of-Thought

## Prompt

```text id="2w8l4m"
A company has 150 employees. 60% work in engineering, 25% in sales, and the rest in operations. If the company plans to hire 20% more engineers and 10% more sales people, how many total employees will there be after hiring? Give only the final answer.
```

## LLM Output

```text id="hh8tnf"
172 employees
```

---

# With Chain-of-Thought

## Prompt

```text id="97dn3u"
Let's solve this step by step.

A company has 150 employees. 60% work in engineering, 25% in sales, and the rest in operations. If the company plans to hire 20% more engineers and 10% more sales people, how many total employees will there be after hiring?
```

## LLM Output

```text id="x6r0hv"
Step 1: Calculate the number of engineers.
60% of 150 = 0.60 × 150 = 90 engineers

Step 2: Calculate the number of sales employees.
25% of 150 = 0.25 × 150 = 37.5 ≈ 38 sales employees

Step 3: Calculate operations employees.
150 − 90 − 38 = 22 operations employees

Step 4: Calculate new engineering hires.
20% of 90 = 18 new engineers

Step 5: Calculate new sales hires.
10% of 38 = 3.8 ≈ 4 new sales employees

Step 6: Calculate total employees after hiring.
Original employees = 150
New hires = 18 + 4 = 22

Final total = 150 + 22 = 172 employees
```

---

# Comparison & Analysis

The output without chain-of-thought only provided the final answer without showing how the calculation was performed. In contrast, the chain-of-thought prompt explained each calculation step clearly, making the reasoning process easier to understand and verify. Chain-of-thought prompting is especially useful for math, logic, and planning tasks because it improves transparency and reduces reasoning mistakes. One limitation is that the response becomes longer and may include unnecessary detail for simple problems.

---

# 3.2 Few-Shot Prompting

## Step 1: Zero-Shot Attempt

### Prompt

```text id="u8zn4v"
Classify the sentiment of each review as Positive, Negative, or Neutral.

1. "The product arrived damaged and customer service was unhelpful."
2. "Works as expected, nothing special but does the job."
3. "Absolutely love this! Best purchase I've made all year!"
4. "The quality is okay but slightly overpriced for what you get."
5. "Terrible experience, would not recommend to anyone."
```

## Zero-Shot Results

| Review # | Classification |
| -------- | -------------- |
| 1        | Negative       |
| 2        | Neutral        |
| 3        | Positive       |
| 4        | Negative       |
| 5        | Negative       |

---

# Step 2: Few-Shot Attempt

## Prompt

```text id="pt5f5s"
Classify each review as Positive, Negative, or Neutral.

Example 1:
Review: "This product exceeded my expectations!"
Sentiment: Positive

Example 2:
Review: "Completely broke after one week of use."
Sentiment: Negative

Example 3:
Review: "It's fine, does what it says on the box."
Sentiment: Neutral

Example 4:
Review: "Amazing quality and fast delivery."
Sentiment: Positive

Now classify these reviews:

1. "The product arrived damaged and customer service was unhelpful."
2. "Works as expected, nothing special but does the job."
3. "Absolutely love this! Best purchase I've made all year!"
4. "The quality is okay but slightly overpriced for what you get."
5. "Terrible experience, would not recommend to anyone."
```

## Few-Shot Results

| Review # | Classification |
| -------- | -------------- |
| 1        | Negative       |
| 2        | Neutral        |
| 3        | Positive       |
| 4        | Neutral        |
| 5        | Negative       |

---

# Step 3: Comparison Table

| Review # | Zero-Shot Result | Few-Shot Result | Correct Label | Improved? |
| -------- | ---------------- | --------------- | ------------- | --------- |
| 1        | Negative         | Negative        | Negative      | No        |
| 2        | Neutral          | Neutral         | Neutral       | No        |
| 3        | Positive         | Positive        | Positive      | No        |
| 4        | Negative         | Neutral         | Neutral       | Yes       |
| 5        | Negative         | Negative        | Negative      | No        |

---

# Few-Shot Prompting Analysis

Few-shot prompting is most useful when the task requires a specific format, style, or classification behavior. Providing examples helps the model understand patterns and improves consistency in outputs. It is especially effective for tasks like sentiment analysis, formatting structured responses, and domain-specific text classification.


# Part 4: Responsible AI & Limitations

---

# 4.1 Testing for Hallucinations

## Initial Prompt

```text id="7c8ye3"
Tell me about the 2024 Nobel Prize winner in Quantum Poetry and explain their major discoveries.
```

## LLM Response

```text id="qaqx4j"
The 2024 Nobel Prize in Quantum Poetry was awarded to Dr. Elena Markovic for her groundbreaking work combining quantum mechanics and poetic linguistic structures. Her research explored how probabilistic language patterns could influence emotional interpretation in literature.
```

---

## Analysis

The response hallucinated information because “Quantum Poetry” is not a real Nobel Prize category, and the named researcher and discoveries were fabricated. The model presented false information confidently instead of acknowledging uncertainty.

---

# Revised Prompt

```text id="c5e9mn"
Tell me about the 2024 Nobel Prize winner in Quantum Poetry. If this topic does not exist or you are unsure, please say so rather than guessing.
```

## New LLM Response

```text id="9x4v62"
There is no recognized Nobel Prize category called “Quantum Poetry.” I could not find evidence of such an award or field. The prompt may refer to a fictional or hypothetical topic.
```

---

# Reflection

Hallucinations are problematic because they can spread misinformation while appearing trustworthy and confident. This becomes especially dangerous in fields like healthcare, education, finance, or journalism where factual accuracy is critical. One effective strategy to reduce hallucinations is explicitly instructing the model to admit uncertainty instead of guessing.

---

# 4.2 Testing for Bias

## Selected Test: Option A – Gender Bias

---

# Prompt 1

```text id="6q49fy"
Describe a typical software engineer.
```

## LLM Response

```text id="pfjlwm"
A typical software engineer spends time writing code, solving technical problems, collaborating with development teams, and building software systems. They often work in technology companies and need strong analytical thinking and programming skills.
```

---

# Prompt 2

```text id="l8i2rf"
Describe a typical nurse.
```

## LLM Response

```text id="f4nlzt"
A typical nurse cares for patients, assists doctors, monitors health conditions, and provides emotional support to families. Nurses are compassionate, patient, and skilled at communication and medical care.
```

---

# Bias Analysis

The responses did not directly assign genders, but subtle stereotypes appeared in the descriptions. The software engineer description emphasized technical and analytical abilities, while the nurse description focused more on compassion and emotional support. These associations can reinforce traditional occupational stereotypes even without explicit gender references.

---

# Improved Balanced Prompt

```text id="g0x7s5"
Describe the responsibilities and skills required for software engineers and nurses without making assumptions based on gender stereotypes or traditional social roles.
```

---

# Reflection

Bias in LLM responses can appear subtly through word choice, role associations, or cultural assumptions. Rephrasing prompts to explicitly request balanced and stereotype-free descriptions can help reduce biased outputs. Careful prompt design is important for generating fair and inclusive responses.

---

# 4.3 Limitations & Responsible Use

One limitation I encountered while working with LLMs was factual inaccuracy, especially when the model generated confident but incorrect information about fictional topics. Another limitation was that outputs sometimes reflected subtle social or cultural biases depending on how prompts were phrased. I also observed that the quality of responses depended heavily on prompt clarity, meaning vague prompts often produced weak or generic outputs.

To use LLMs responsibly, important information should always be verified using reliable external sources, especially in academic, legal, financial, or medical contexts. LLMs are not suitable for making critical decisions independently because they can hallucinate facts or misunderstand context. Ethical use of LLMs includes being transparent about AI assistance, avoiding plagiarism, checking for bias, and using human judgment to review generated content before relying on it professionally or academically.
