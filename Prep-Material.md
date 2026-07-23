# AWS AI Practicioner Exam #

## To the people reading this .md file consists of only practice problems gathered from various practice tests(of course I won't name where I got each question from) ##

### My thoughts: AWS AI practicioner exam is a relatively easy exam, it consists of 65 questions, 15 of them are unmarked,(for some stupid reason they still do this), in my first attempt i got 671/1000, bear in mind I had no familiarity with AWS Services and am a 1st year transitioning to 2nd year in  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTqsAeYWr1bCzeKeufWy6c2SKsU2zJfj6xLS-x4RkpGsQ&s=10" height="20" style="vertical-align: middle; margin: 0 3px;">, so of course I couldn't really pass it on my first try! ###

---
**Question 1**

An e-commerce company wants to build an AI assistant that answers product-related questions using its internal product catalog and policy documents stored in Amazon S3. They want the assistant's answers to be grounded in actual company content, not just general knowledge.

Which Amazon Bedrock feature is BEST suited for this use case?

* Amazon Bedrock Agents,
* Amazon Bedrock Guardrails,
* Amazon Bedrock Knowledge Bases,
* Amazon Bedrock Model Evaluation

<Details>
    Amazon Bedrock Knowledge Bases - It ensures connectivity with private information. ✅<br>
    Amazon Bedrock Agents - Enables creation of new Agents, not necessarily related to this question. ❌<br>
    Amazon Bedrock Guardrails - Ensures no use of prohibited words(profanity, sexual, etc.), also disables the machine's ability to hallucinate. ❌<br>
    Amazon Bedrock Model Evaluation - Evaluates model based on a metric of its own. ❌
</Details>

**Question 2**

A hospital system has an existing computer vision model trained on standard chest X-rays. They need to adapt it to detect a rare pediatric bone condition in wrist radiographs without starting model training from scratch due to limited data availability.

Which ML approach is MOST appropriate?

* Unsupervised Learning,
* Transfer Learning,
* Reinforcement learning from human feedback,
* Synthetic Data Generation

<Details>
    Transfer Learning - This is the best and most efficient way to adapt a model to a new one, as the name suggests it just transfers everything it knows to the new model. ✅<br>
    Unsupervised Learning - Is basically leaving unlabeled data to the machine and allowing for it to do whatever it wants with it(train, label) all on its own. ❌<br>
    Reinforcement Learning from Human Feedback - Is a great way to train the model but it consumes time and work force(requesting a human to always give prompts to the machine so that it can learn). ❌<br>
    Synthetic Data Generation - this is not what the question asked, this is basically creating new data that has no correlation to X-rays(may or may not have), also it requires computational workforce since you need to implant algorithms and simulations to it.
</Details>

**Question 3**

A financial services company must retain complete records of every API call made to foundation models for regulatory compliance. They need to capture both the input prompts and model responses, along with timestamps and model identifiers.

Which Amazon Bedrock feature should be enabled?

* Amazon Bedrock Guardrails,
* Model Invocation Logging,
* Amazon Bedrock Agents,
* AWS Cloud Trail

<Details>
    Model Invocation Logging - This is the correct answer, as the word Logging suggests it uses a history view of all API calls made. ✅ <br>
    Amazon Bedrock Guardrails - As mentioned previously this is only used to enable strict rules for the model to follow, such as no use of profanity and disable hallucination. ❌ <br>
    Amazon Bedrock Agents - Create new Agents. ❌ <br>
    AWS Cloud Trail - This is very similiar to Model Invocation Logging but this does not capture the prompts/timestamps and stuff. ❌ 
</Details>


**Question 4**

A government agency is creating an AI governance policy for its newly deployed automated benefits determination system. The agency's legal team requires a clear chain of responsibility if the system makes an erroneous decision that harms a citizen.

Which governance practice BEST supports accountability for AI system decisions?

* Deploy only open-source foundation models to ensure code transparency.
* Maintain audit trails of model decisions, document model development processes, and assign named owners to each AI system.
* Restrict deployment to air-gapped, on-premises infrastructure.
* Exclude any personally identifiable information from model training datasets.

<Details>
    Maintain audit trails of model decisions, document model development processes, and assign named owners to each AI system - This is the correct answer because AI accountability requires three pillars: 1.Documentation(model cards, data lineage, design decisions), 2.Audit Trails(Logged records of when models were deployed, modified, and what decisions they produced), and clear ownership(Naming responsible individuals or teams for each systems). ✅ <br>
    Deploy only open-source foundation models to ensure code transparency - This only establishes what code is written, not who is responsible for what, when it was made and such. ❌ <br>
    Restrict deployment to air-gapped, on-premises infrastructure - Incorrect, this is unrelated to the question. ❌ <br>
    Exclude any personally identifiable information from model Training datasets - This is PII, not related to the question, whatsoever. ❌
</Details>

**Question 5**

A startup is experimenting with Amazon Bedrock for a proof-of-concept. Their prototype application calls the model approximately 15 times per day with varying request volumes. They want to minimize costs during this early phase.

Which approach BEST minimizes costs?

* Purchase Provisioned Throughput with a 1-month commitment for guaranteed capacity.
* Fine-tune a foundation model to improve relevance and reduce retries.
* Use On-Demand pricing and optimize prompts to minimize token count.
* Migrate to a dedicated Amazon SageMaker endpoint for cost predictability.

<Details>
    Use On-Demand pricing and optimize prompts to minimize token count - This is the best and most efficient way to minimize cost, On-Demand enables the user to only pay for when they use the AI(opposite of Provisioned throughput), combining that with prompt optimization enables both input and output token, which in turn reduces the amount needed for spend. ✅ <br>
    Purchase Provisioned Throughput with a 1-month commitment for guaranteed capacity - This is not the way to go, provisioned Throughput is like a Gym membership, you pay for it for a specific time, but it doesnt care if you went there or not. ❌ <br>
    Fine-tune a foundation model to improve relevance and reduce retries - This takes a lot of workforce and doesnt guarante success. ❌ <br>
    Migrate to a dedicated Amazon SageMaker Endpoint for cost predictability - This does not minimize cost it just predicts it. ❌
</Details>

**Question 6**

A retail company wants to build a shopping assistant that can accept a photo of a product and generate a written description of that item, including suggested complementary products. The system must process both image and text inputs and produce text outputs.

Which model type supports this requirement?

* Text-only large language model,
* Multimodal foundation model,
* Image segmentation model,
* Optical character recognition model.

<Details>
    Multimodal foundation model - The thing with Multimodal foundation models is that they are multi-functional, enabling the user to accept multiple input modalities(Images, texts, and audios), and generate text as output. ✅ <br>
    Text-only large Language Model - This only accepts text as input. ❌ <br>
    Image Segmentation model - They don't generate text outputs. ❌ <br>
    Optical Character Recognition model - They extract printed text from images but don't understand visual semantics. ❌
</Details>

**Question 7**

A legal technology company is building a document similarity system. They need to convert thousands of legal briefs into a numerical format that captures their semantic meaning so that attorneys can find precedents by searching with natural language queries.

Which model type should be used for this conversion step?
