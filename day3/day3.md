# Day 3: Role-Based Prompting

Today's goal is to explore and understand the benefits of prompting AI using a "role" to fill rather than a general explanation with lacking context.

**Result:**

![alt text](<ChatGPT Image Jul 20, 2026, 05_50_38 PM.png>)

## Prompting Results:

**Q (No Role):** In two sentences, explain what the primary purpose and value is of developing a Retrieval Augmented Generation (RAG) pipeline.

**A:** A Retrieval-Augmented Generation (RAG) pipeline lets an AI retrieve relevant information from trusted external sources before generating an answer. Its value is that responses become more accurate, current, and grounded in specific data, reducing hallucinations without retraining the model.

**Q (Founder):** From the perspective of a startup founder for a financial assistance app, in two sentences, explain what the primary purpose and value is of developing a Retrieval Augmented Generation (RAG) pipeline.

**A:** A RAG pipeline allows our financial assistance app to retrieve verified, up-to-date information from trusted sources before answering users’ questions. Its value is delivering more accurate, personalized, and explainable guidance while reducing hallucinations and the compliance risks of relying only on a model’s built-in knowledge.

**Q (Developer):** From the perspective of a senior developer working for a financial assistance app startup, in two sentences, explain what the primary purpose and value is of developing a Retrieval Augmented Generation (RAG) pipeline to the new junior developer employee.

**A:** A RAG pipeline lets our app retrieve relevant, approved financial information before the language model generates a response, instead of relying only on what the model learned during training. That gives us more accurate, current, and traceable answers while reducing hallucinations, compliance risk, and the need to retrain the model whenever our data changes.

## Results Analysis

Overall, the role-interference seems to add a layer of detail, context, and examples that isn't present without it. The first answer defines what RAG is as a "dictionary" definition that doesn't aid in the user's understanding.

When I included context that set the LLM in the shoes of someone working at a real company (and especially when I gave it an audience) it provided details that relate to the role I assigned and explained it using more illuminating language. It explained it as more of a **concrete example** than an **ungraspable concept**.