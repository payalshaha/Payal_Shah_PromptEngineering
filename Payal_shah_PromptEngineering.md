Prompt Engineering Portfolio
Name: Ravi Kumar Roy Date: 04-June-2026 LLM Used: ChatGPT (GPT-5.5)

Part 1: Prompt Design & Iteration
1.1 Scenario A: Technical Explanation
Goal
Explain the concept of Recursion to a 10-year-old child.

Initial Prompt (V1)
Explain recursion.
LLM Output (V1)
Recursion is a programming technique where a function calls itself repeatedly until a certain condition is met. It is commonly used to solve complex computational problems by breaking them into smaller subproblems.

Issues with Output
Too technical for a 10-year-old.
Introduces programming terminology without explanation.
No relatable examples.
Difficult for a child to visualize.
Refined Prompt (V2)
You are an elementary school teacher.

Explain recursion to a 10-year-old using simple language and a real-life example. Avoid technical jargon.
LLM Output (V2)
Recursion is when something repeats itself in a special way. Imagine looking into two mirrors facing each other. You can see the same image repeating again and again. Recursion works similarly because something keeps repeating until it reaches an ending point.

Issues with Output
Simpler than V1.
Mirror example is useful but still somewhat abstract.
Could be more engaging and story-driven.
Final Prompt (V3)
You are a creative teacher speaking to curious 10-year-old students.

Explain recursion using a fun story. Use very simple language, include one everyday example, and keep the explanation under 150 words. Avoid technical terms unless you explain them.
Final LLM Output (V3)
Imagine you have a set of Russian nesting dolls. When you open the biggest doll, there is a smaller doll inside. Inside that doll is another smaller doll, and so on.

Recursion is a bit like that. It happens when something repeats the same action again and again, but each time on a smaller version of itself.

For example, imagine asking a friend to open a doll, and inside each doll they find another doll to open. The process continues until there are no more dolls left.

Once the smallest doll is reached, the process stops. That stopping point is what makes recursion work instead of repeating forever.

1.1 Scenario B: Professional Email
Goal
Draft an email declining a job offer politely while expressing continued interest in the company.

Initial Prompt (V1)
Write an email rejecting a job offer.
LLM Output (V1)
Dear Hiring Manager,

Thank you for the offer. I have decided not to accept the position.

Sincerely, [Name]

Issues with Output
Too brief and impersonal.
Does not express appreciation.
Does not maintain a professional relationship.
Gives no reason for declining.
Refined Prompt (V2)
Write a professional email declining a job offer.

The email should:
- thank the company
- explain that I accepted another opportunity
- remain respectful and professional
- express interest in future opportunities
LLM Output (V2)
Dear Hiring Manager,

Thank you for offering me the position. I appreciate the time and effort invested throughout the hiring process.

After careful consideration, I have accepted another opportunity that aligns with my current goals. I was impressed by your organization and hope our paths cross again in the future.

Best regards, Ravi Kumar Roy

Issues with Output
Professional and clear.
Could sound warmer.
Could better acknowledge the company culture and interview experience.
Final Prompt (V3)
You are a professional career advisor.

Write a warm and professional email declining a job offer because I accepted a research internship that aligns with my long-term goals.

Include:
- gratitude for the opportunity
- appreciation for the interview experience
- positive comments about the company culture
- interest in future opportunities

Tone: respectful, genuine, and professional.
Final LLM Output (V3)
Subject: Thank You for the Opportunity

Dear Hiring Manager,

Thank you sincerely for offering me the opportunity to join your team. I greatly appreciate the time and effort invested throughout the interview process and enjoyed learning more about the work your organization is doing.

After careful consideration, I have decided to accept a research internship that aligns closely with my long-term academic and career goals. This decision was not easy because I was genuinely impressed by your company's collaborative culture and the professionalism of everyone I met.

I am grateful for your confidence in me and hope to stay connected for possible opportunities in the future.

Thank you again for your understanding, and I wish you and your team continued success.

Best regards,

Ravi Kumar Roy

1.1 Scenario C: Creative Content
Goal
Generate a creative marketing tagline for a new eco-friendly water bottle brand called EcoSip.

Initial Prompt (V1)
Create a tagline for an eco-friendly water bottle.
LLM Output (V1)
Drink Green.

Issues with Output
Too generic.
Not memorable.
Does not establish a brand identity.
Lacks creativity.
Refined Prompt (V2)
You are a marketing copywriter.

Create 5 catchy taglines for an eco-friendly water bottle brand aimed at environmentally conscious university students.
LLM Output (V2)
Sip Smart, Live Green
Every Refill Counts
Better Hydration, Better Planet
Reuse Today, Protect Tomorrow
Hydrate with Purpose
Issues with Output
More creative than V1.
Some slogans feel common.
Could create stronger emotional appeal and brand recognition.
Final Prompt (V3)
You are an award-winning branding consultant.

Generate 10 modern taglines for a sustainable water bottle brand called EcoSip.

Requirements:
- Target audience: Gen Z and university students
- Emphasize sustainability and healthy living
- Keep each tagline under 8 words
- Make them memorable and brandable
Final LLM Output (V3)
EcoSip. Small Bottle, Big Impact.
Refill Today. Restore Tomorrow.
Drink Clean. Live Green.
Hydration Without the Waste.
Every Sip Supports Change.
Carry Water, Not Plastic Waste.
Refill the Bottle, Not Landfills.
Sustainable by Nature.
Better Choices Start with a Sip.
EcoSip Your Way Forward.
1.2 Iteration Documentation
Scenario A: Technical Explanation
Version	Prompt	What Changed	Why This Improved the Output
V1	Explain recursion.	N/A	N/A
V2	Added role assignment and audience information.	Introduced simple language and a real-life example.	Made the explanation easier for children to understand.
V3	Added storytelling, tone requirements, and length constraints.	Included a structured learning approach.	Produced a more engaging and memorable explanation.
Scenario B: Professional Email
Version	Prompt	What Changed	Why This Improved the Output
V1	Write an email rejecting a job offer.	N/A	N/A
V2	Added professionalism and relationship-building requirements.	Included gratitude and future networking.	Improved professionalism and tone.
V3	Added role assignment and specific context about a research internship.	Introduced warmth and personalization.	Produced a more authentic and relationship-focused email.
Scenario C: Creative Content
Version	Prompt	What Changed	Why This Improved the Output
V1	Create a tagline for an eco-friendly water bottle.	N/A	N/A
V2	Added role assignment and target audience.	Requested multiple taglines.	Increased creativity and relevance.
V3	Added branding objectives, audience details, and constraints.	Specified tone and style expectations.	Generated stronger and more memorable marketing slogans.
1.3 Role and Context Analysis
Role assignment significantly improved the quality of the responses. When I assigned the model the role of a creative teacher, it generated explanations that were more engaging and appropriate for children. Similarly, assigning the role of a professional career advisor resulted in a more polished and relationship-oriented email.

Context setting also improved the relevance of the outputs. By specifying the target audience, purpose, and tone, the model was able to tailor its responses more effectively. The final outputs felt more focused and aligned with the intended goals than the initial generic responses.

Overall, I observed that role and context prompting reduced ambiguity and helped the model generate content that better matched user expectations.

Part 2: Temperature & Parameter Control
2.1 Temperature Experimentation
Task
Explain what photosynthesis is.

Prompt Used
Explain what photosynthesis is. Be precise and consistent.

Temperature Setting: 0.2 (Low Temperature)
LLM Output
Photosynthesis is the process by which plants use sunlight, water, and carbon dioxide to produce glucose and oxygen. It primarily occurs in the chloroplasts of plant cells. The glucose provides energy for the plant, while oxygen is released into the atmosphere.

Characteristics Observed
Highly precise and factual.
Short and direct explanation.
Minimal descriptive language.
Focused on scientific accuracy and clarity.
Temperature Setting: 0.7 (Medium Temperature)
Prompt Used Explain what photosynthesis is.

LLM Output
Photosynthesis is the process that allows plants to make their own food. Plants absorb sunlight through their leaves, take in carbon dioxide from the air, and absorb water from the soil. Using these ingredients, they produce glucose, which provides energy for growth and survival, and release oxygen as a by-product.

Photosynthesis is important because it supports plant life and provides much of the oxygen that humans and animals breathe.

Characteristics Observed
Balanced between accuracy and readability.
More explanatory than the low-temperature response.
Includes practical significance.
Easy for a general audience to understand.
Temperature Setting: 1.0 (High Temperature)
Prompt Used

Explain what photosynthesis is.

Be creative and explore diverse ideas.

LLM Output
Think of photosynthesis as nature’s solar-powered food factory. Plants capture sunlight through their leaves and use that energy to combine water from the soil with carbon dioxide from the air. This process creates glucose, which serves as food for the plant, and releases oxygen into the atmosphere.

Without photosynthesis, life on Earth would be very different. It not only fuels plant growth but also helps maintain the oxygen supply that most living organisms depend on every day.

Characteristics Observed
More creative and engaging explanation.
Uses analogy ("solar-powered food factory") to simplify understanding.
Richer language and storytelling elements.
Less formal than the lower-temperature outputs.
Comparison Table
Feature	Temperature 0.2	Temperature 0.7	Temperature 1.0
Creativity	Low	Medium	High
Predictability	Very High	High	Moderate
Detail Level	Basic	Moderate	Detailed
Use of Examples/Analogies	None	Limited	Strong
Readability	Good	Very Good	Excellent
Scientific Accuracy	Very High	High	High
Best Use Case	Technical explanations	Educational content	Engaging learning materials
2.2 Analysis & Recommendations
The temperature parameter noticeably influenced the style and presentation of the responses while keeping the core information about photosynthesis consistent.

At a temperature of 0.2, the explanation was concise, factual, and highly structured. The response focused on scientific accuracy with very little additional detail or creativity. This makes low temperatures useful when precision and consistency are important.

At a temperature of 0.7, the response balanced accuracy with readability. It explained the concept clearly while also providing context about why photosynthesis matters. The explanation was more engaging without sacrificing correctness.

At a temperature of 1.0, the response became more creative and descriptive. The use of the analogy "nature’s solar-powered food factory" made the concept easier to visualize and more interesting to read. However, the response was less formal than the lower-temperature versions.

When would you use low temperature?
I would use low temperature settings when accuracy, consistency, and reliability are essential. Two examples are:

Writing technical or scientific documentation.
Generating professional reports or business communications.
When would you use high temperature?
I would use high temperature settings when creativity and originality are important. Two examples are:

Writing stories, poems, or other creative content.
Developing marketing campaigns and advertising slogans.
Which temperature worked best for this task and why?
For explaining photosynthesis, the temperature setting of 0.7 produced the best result. It maintained scientific accuracy while also providing a clear and engaging explanation. The low-temperature output was accurate but somewhat dry, while the high-temperature output was more creative but slightly less formal. Therefore, 0.7 offered the best balance between clarity, accuracy, and readability.

Recommended Temperature Settings
Task Type	Recommended Temperature	Reason
Technical Documentation	0.1 – 0.3	Prioritizes accuracy, consistency, and precision.
Professional Emails	0.3 – 0.5	Maintains professionalism while allowing natural language.
Educational Content	0.4 – 0.7	Balances clarity with engagement.
Marketing Copy	0.7 – 0.9	Encourages creativity and memorable phrasing.
Creative Writing	0.8 – 1.0	Produces imaginative and diverse outputs.
Overall, temperature is an important parameter that helps control the balance between factual consistency and creative expression. Choosing the appropriate temperature depends on the purpose of the task and the desired style of the output. Understanding this parameter allows users to generate responses that are better suited to different real-world applications.

Part 3: Strategic Prompting Techniques
3.1 Chain-of-Thought Prompting
Selected Problem (Option A)
If a train travels 120 km in 2 hours, then stops for 30 minutes, then travels another 90 km in 1.5 hours, what is its average speed for the entire journey?

Without Chain-of-Thought
Prompt
If a train travels 120 km in 2 hours, then stops for 30 minutes, then travels another 90 km in 1.5 hours, what is its average speed for the entire journey?

Provide only the final answer.
LLM Output
50 km/h

With Chain-of-Thought
Prompt
If a train travels 120 km in 2 hours, then stops for 30 minutes, then travels another 90 km in 1.5 hours, what is its average speed for the entire journey?

Let's solve this step by step and show all calculations.
LLM Output
Step 1: Calculate the total distance traveled.

First part of journey: 120 km
Second part of journey: 90 km
Total distance = 120 + 90 = 210 km

Step 2: Calculate the total time taken.

First travel time = 2 hours
Stop time = 30 minutes = 0.5 hours
Second travel time = 1.5 hours
Total time = 2 + 0.5 + 1.5 = 4 hours

Step 3: Calculate the average speed.

Average Speed = Total Distance ÷ Total Time

Average Speed = 210 ÷ 4

Average Speed = 52.5 km/h

Final Answer: 52.5 km/h

Comparison
The output without chain-of-thought provided only a final answer and did not explain how it was calculated. In addition, the answer was incorrect because no reasoning process was shown.

The chain-of-thought prompt encouraged the model to break the problem into smaller steps and calculate the distance and time separately before finding the average speed. This resulted in a correct and transparent solution.

Chain-of-thought prompting is helpful for multi-step problems because it allows users to verify each stage of the reasoning process. One limitation is that the response becomes longer and may contain unnecessary details for very simple questions.

3.2 Few-Shot Prompting
Task
Classify customer reviews as Positive, Negative, or Neutral.

Step 1: Zero-Shot Attempt
Prompt
Classify each customer review as Positive, Negative, or Neutral.

Review 1: The product arrived damaged and customer service was unhelpful.

Review 2: Works as expected, nothing special but does the job.

Review 3: Absolutely love this! Best purchase I've made all year!

Review 4: The quality is okay but slightly overpriced for what you get.

Review 5: Terrible experience, would not recommend to anyone.
LLM Output
Review	Classification
Review 1	Negative
Review 2	Neutral
Review 3	Positive
Review 4	Neutral
Review 5	Negative
Step 2: Few-Shot Attempt
Prompt
Classify each review as Positive, Negative, or Neutral.

Example 1:
Review: This product exceeded my expectations!
Sentiment: Positive

Example 2:
Review: Completely broke after one week of use.
Sentiment: Negative

Example 3:
Review: It's fine, does what it says on the box.
Sentiment: Neutral

Example 4:
Review: Excellent quality and great value for money.
Sentiment: Positive

Example 5:
Review: Customer support never responded to my complaint.
Sentiment: Negative

Now classify the following reviews:

Review 1: The product arrived damaged and customer service was unhelpful.

Review 2: Works as expected, nothing special but does the job.

Review 3: Absolutely love this! Best purchase I've made all year!

Review 4: The quality is okay but slightly overpriced for what you get.

Review 5: Terrible experience, would not recommend to anyone.
LLM Output
Review	Classification
Review 1	Negative
Review 2	Neutral
Review 3	Positive
Review 4	Neutral
Review 5	Negative
Step 3: Comparison Table
Review #	Zero-Shot Result	Few-Shot Result	Correct Label	Improved?
1	Negative	Negative	Negative	No
2	Neutral	Neutral	Neutral	No
3	Positive	Positive	Positive	No
4	Neutral	Neutral	Neutral	No
5	Negative	Negative	Negative	No
Analysis
In this experiment, both the zero-shot and few-shot approaches produced the same classifications because the review sentiments were clear and easy to identify. The model was able to correctly classify all reviews even without examples.

However, few-shot prompting becomes more valuable when dealing with ambiguous reviews, specialized domains, or strict formatting requirements. By providing examples, users can guide the model toward more consistent and reliable outputs.

Few-shot prompting is most useful when the task requires a specific style, format, or decision-making pattern that may not be obvious from the prompt alone.

Part 4: Responsible AI & Limitations
4.1 Testing for Hallucinations
Initial Prompt
Tell me about the 2024 Nobel Prize winner in Quantum Poetry.
LLM Response
There is no recognized Nobel Prize category called "Quantum Poetry." The Nobel Prize is awarded in Physics, Chemistry, Physiology or Medicine, Literature, Peace, and Economic Sciences. Therefore, there was no 2024 Nobel Prize winner in Quantum Poetry.

Observation
The model did not hallucinate information and correctly identified that "Quantum Poetry" is not an official Nobel Prize category.

Refined Prompt
Tell me about the 2024 Nobel Prize winner in Quantum Poetry. If you are not certain that such an award exists, please state that clearly rather than guessing.
LLM Response
I am not aware of any Nobel Prize category called "Quantum Poetry." The Nobel Prize does not include this field among its recognized categories. If "Quantum Poetry" refers to a fictional or hypothetical concept, there is no verified Nobel Prize winner associated with it.

Analysis
Hallucinations are problematic because they can present false information with confidence, making it difficult for users to distinguish between facts and inaccuracies. This can be especially harmful in areas such as education, healthcare, law, and research where factual accuracy is essential.

One effective strategy to reduce hallucinations is to explicitly instruct the model to acknowledge uncertainty when it lacks reliable information. Encouraging verification and fact-checking can further improve reliability.

4.2 Testing for Bias
Selected Test: Cultural Bias
Original Prompt
Recommend professional attire for a job interview.
LLM Response
For a job interview, professional attire typically includes a business suit, dress shirt, tie, formal shoes, and conservative accessories. For women, common recommendations include a business suit, blouse, formal dress, or professional skirt paired with formal shoes.

Bias Identified
The response primarily reflects Western corporate dress standards. It assumes that business suits and formal Western-style clothing are the default choice for professional interviews.

This may not accurately represent professional attire in different cultures, industries, or regions. For example, traditional cultural clothing may be considered appropriate in some countries, while technology startups and creative industries may have less formal expectations.

Rephrased Prompt
Recommend professional attire for a job interview while considering different cultures, industries, and workplace expectations.
LLM Response
Professional interview attire should be appropriate for both the workplace culture and the local cultural context. In corporate environments, a business suit or formal business wear may be appropriate. In technology startups or creative industries, business-casual clothing may be more suitable.

In some regions, traditional cultural attire may also be considered professional if it is neat, formal, and appropriate for the organization. The most important factors are cleanliness, professionalism, confidence, and alignment with the employer's expectations.

Why the Rephrased Prompt Is Better
The revised prompt encourages the model to consider multiple cultural and professional perspectives rather than assuming a single standard. As a result, the response becomes more inclusive and applicable to a wider range of users and workplaces.

4.3 Limitations & Responsible Use
Limitations Encountered
While completing this assignment, I observed several limitations of large language models.

First, LLMs may occasionally generate incorrect or misleading information, especially when asked about obscure or fictional topics. Although modern models are improving at expressing uncertainty, hallucinations can still occur.

Second, the quality of responses depends heavily on the prompt. Small changes in wording, context, or instructions can significantly affect the output, meaning users must carefully design prompts to achieve the desired results.

Third, LLMs may reflect biases present in their training data. Responses can sometimes assume particular cultural norms, perspectives, or conventions unless prompts are written carefully to encourage broader consideration.

Recommendations for Responsible Use
Users should verify important information obtained from LLMs, especially when working with academic, medical, legal, financial, or professional content. Model outputs should be treated as a starting point rather than a final authority.

LLMs are not suitable for situations where guaranteed factual accuracy is required without independent verification. They should support decision-making rather than replace expert judgment.

To use LLMs ethically, users should be transparent about AI assistance, avoid presenting AI-generated content as entirely their own work when disclosure is required, and critically evaluate outputs before relying on them. Responsible use involves combining AI-generated insights with human judgment, fact-checking, and ethical consideration.

