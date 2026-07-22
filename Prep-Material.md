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

<Answer:>
    Amazon Bedrock Knowledge Bases - It ensures connectivity with private information. ✅
    Amazon Bedrock Agents - Enables creation of new Agents, not necessarily related to this question. ❌
    Amazon Bedrock Guardrails - Ensures no use of prohibited words(profanity, sexual, etc.), also disables the machine's ability to hallucinate. ❌
    Amazon Bedrock Model Evaluation - Evaluates model based on a metric of its own. ❌
</Answer:>

**Question 2**

A hospital system has an existing computer vision model trained on standard chest X-rays. They need to adapt it to detect a rare pediatric bone condition in wrist radiographs without starting model training from scratch due to limited data availability.

Which ML approach is MOST appropriate?

* Unsupervised Learning,
* Transfer Learning,
* Reinforcement learning from human feedback,
* Synthetic Data Generation

<Answer:>
    Transfer Learning - This is the best and most efficient way to adapt a model to a new one, as the name suggests it just transfers everything it knows to the new model. ✅
    Unsupervised Learning - Is basically leaving unlabeled data to the machine and allowing for it to do whatever it wants with it(train, label) all on its own. ❌
    Reinforcement Learning from Human Feedback - Is a great way to train the model but it consumes time and work force(requesting a human to always give prompts to the machine so that it can learn). ❌
    Synthetic Data Generation - this is not what the question asked, this is basically creating new data that has no correlation to X-rays(may or may not have), also it requires computational workforce since you need to implant algorithms and simulations to it.
</Answer:>

**Question 3**

A financial services company must retain complete records of every API call made to foundation models for regulatory compliance. They need to capture both the input prompts and model responses, along with timestamps and model identifiers.

Which Amazon Bedrock feature should be enabled?