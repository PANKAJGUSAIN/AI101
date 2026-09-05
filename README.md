# AI101
## How to Be Better with AI

---

## Table of Contents
1. [Fundamentals of AI](#1-fundamentals-of-ai)
   - [What is AI?](#what-is-ai)
   - [Motive of AI](#motive-of-ai)

2. [Levels of Enterprise AI](#2-levels-of-enterprise-ai)
   - [Automation](#automation--ai-does-it-for-you)
   - [Augmentation](#augmentation--ai-works-alongside-you)
   - [Agency](#agency--ai-acts-toward-goals)

3. [AI Models](#3-ai-models)
   - [Machine Learning Models](#machine-learning-models)
   - [Deep Learning Models](#deep-learning-models)
   - [Generative AI Models](#generative-ai-models)
   - [Relationship Between AI, ML, Deep Learning and GenAI](#relationship-between-ai-ml-deep-learning-and-genai)

4. [Generative AI](#4-generative-ai)
   - [What Can Generative AI Generate?](#what-can-generative-ai-generate)
   - [Examples of Generative AI](#examples-of-generative-ai)
   - [Large Language Models (LLMs)](#large-language-models-llms)
     - [What Are LLMs?](#what-are-llms)
     - [How Do LLMs Work?](#how-do-llms-work)
     - [GPT as a Leading Example](#gpt-as-a-leading-example)
     - [Examples of LLMs](#examples-of-llms)
     - [Practical Interview Example](#practical-interview-example)

5. [Prompt, Prompting, and Prompt Engineering](#5-prompt-prompting-and-prompt-engineering)
   - [Prompt](#prompt)
   - [Prompting](#prompting)
   - [Prompt Engineering](#prompt-engineering)
  
6. [Tokens](#6-tokens)
   - [Examples](#examples)
   - [Why Do Tokens Matter?](#why-do-tokens-matter)
     - [Context Limit](#context-limit)
     - [Accuracy and Quality](#accuracy-and-quality)
     - [Why AI Can "Forget"](#why-ai-can-forget)
     - [Efficiency](#efficiency)
    
7. [Context Window](#7-context-window)
   - [Why Does This Matter?](#why-does-this-matter)
   - [How Does This Information Help You Design Better Prompts?](#how-does-this-information-help-you-design-better-prompts)
     - [Front-load Critical Instructions](#front-load-critical-instructions)
     - [Keep Prompts Focused](#keep-prompts-focused)
     - [Reinforce Key Rules at Checkpoints](#reinforce-key-rules-at-checkpoints)
    
8. [Bias vs Hallucination in AI](#8-bias-vs-hallucination-in-ai)
   - [Bias](#bias)
     - [Examples](#examples)
     - [How to Reduce Bias](#how-to-reduce-bias)
   - [Hallucination](#hallucination)
     - [Examples](#examples-1)
     - [How to Reduce Hallucinations](#how-to-reduce-hallucinations)

9. [Human-in-the-Loop (HITL)](#9-human-in-the-loop-hitl)
   - [Practical Example](#practical-example)


---

# 1. Fundamentals of AI 

## What is AI?

Artificial Intelligence (AI) refers to advanced computer systems designed to perform tasks that require human intelligence and cognitive abilities.

In simple terms, AI involves teaching computers to:

- **Learn** from experiences to improve performance
- **Tackle** complex problems across different fields
- **Comprehend** language for effective user interaction
- **Make** informed decisions based on data analysis

## Motive of AI

The goal of AI is to assist humans with routine and complex tasks by making machines smarter and more capable.

AI does **not** understand truth, intent, or business context in the same way humans do. It primarily assists through pattern recognition and content generation.

---

# 2. Levels of Enterprise AI

Enterprise AI generally operates at three levels:

- **Automation** — Executing structured tasks
- **Augmentation** — Enhancing human judgment
- **Agency** — Acting toward defined outcomes

## Automation — AI Does It for You

AI executes predefined tasks within structured rules.

- Handles repetitive processes
- Improves speed and consistency

**Practical Example:**

An AI system automatically categorizes incoming customer support tickets based on their content and routes them to the appropriate team.

## Augmentation — AI Works Alongside You

AI enhances decision-making while humans remain accountable.

- Surfaces insights at scale
- Recommends next-best actions

**Practical Example:**

An AI system analyses customer complaints and suggests the most appropriate response to a support agent. The agent reviews the suggestion and decides whether to use it.

## Agency — AI Acts Toward Goals

AI can act toward defined goals within pre-approved workflows, with continuous monitoring and explicit human oversight.

**Practical Example:**

An AI agent receives a customer issue, checks the customer's account, identifies the problem, and performs an approved action such as issuing a refund within predefined limits. If the request falls outside its permissions, it escalates the case to a human.

---

# 3. AI Models

AI models are systems **trained on data to recognize patterns, make predictions, generate content, or support decision-making.**

## Key Types of AI Models

### Machine Learning Models

**Learn patterns from data to make predictions.**

These models learn patterns from past examples. Once trained, they can make predictions such as:

- Forecasting sales
- Predicting customer churn
- Recommending products

**Example:**

Amazon uses machine learning models to recommend products based on a user's previous activity and the behavior of similar users.

### Deep Learning Models

**Use multi-layer neural networks to learn complex patterns from large amounts of data.**

Deep learning models are particularly effective with complex data such as:

- Images
- Text
- Audio
- Video

They can identify patterns that are difficult to detect using traditional approaches.

**Example:**

Face recognition systems and voice assistants use deep learning models to understand and process complex inputs.

### Generative AI Models

**Generate new content based on patterns learned from training data.**

Unlike traditional models that primarily analyze or predict, generative models can create new content such as:

- Text
- Images
- Audio
- Video
- Code

**Example:**

- ChatGPT generating an email or writing code
- DALL·E generating an image from a text prompt

### Relationship Between AI, ML, Deep Learning and GenAI

AI is the broader field, while **Machine Learning is a subset of AI**, and **Deep Learning is a subset of Machine Learning**.

Generative AI is a capability/approach that is commonly built using deep learning models.

A simple way to visualize the relationship:

**AI → Machine Learning → Deep Learning → Modern Generative AI**

> Not every AI system uses machine learning, and not every deep learning model is generative.

---

# 4. Generative AI

Generative AI is a **class of AI models that goes beyond analysis to create new, contextually relevant content** by learning the underlying structures and patterns within large-scale datasets.

During training, these models learn how different elements relate to one another, whether in **language, images, audio, or other formats**.

When prompted, they use this learned knowledge to generate new outputs by **predicting what best fits the given context**, rather than simply retrieving pre-existing answers.

## What Can Generative AI Generate?

* **Natural language** — Emails, reports, documentation, code
* **Visual content** — Images, designs, illustrations
* **Audio and video** — Speech, music, videos
* **Structured outputs** — Summaries, insights, recommendations, JSON, etc.

## Examples of Generative AI

* ChatGPT
* Microsoft Copilot
* DALL·E
* Midjourney
* GitHub Copilot
* Notion AI

---

# Large Language Models (LLMs)

Among Generative AI models, **Large Language Models (LLMs)** have become one of the primary interfaces for interacting with AI through natural language.

## What Are LLMs?

Large Language Models (LLMs) are a specialized class of **Generative AI models trained on vast amounts of text data** to understand, interpret, and generate human language.

They can perform tasks such as:

* Answering questions
* Summarizing content
* Generating code
* Translating languages
* Writing and rewriting text
* Analyzing text

## How Do LLMs Work?

LLMs learn statistical relationships between **tokens, words, phrases, and contexts** during training.

When given a prompt, the model uses these learned patterns to **predict the most likely next token**, repeatedly generating a coherent response that aligns with the given context.

> LLMs don't retrieve a pre-written answer from a database. They generate a response based on patterns learned during training and the context provided in the prompt.

## GPT as a Leading Example

**GPT (Generative Pre-trained Transformer)** is a widely used family of LLMs that demonstrates these capabilities.

GPT models power applications such as:

* Conversational AI
* Coding copilots
* Enterprise knowledge assistants
* Content generation tools

## Examples of LLMs

Some leading LLM families that power language-based Generative AI applications include:

* **GPT** — OpenAI
* **Claude** — Anthropic
* **Gemini** — Google
* **LLaMA** — Meta

### Practical Interview Example

**Question:** *What's the difference between Generative AI and an LLM?*

**Answer:**

> Generative AI is the broader category of AI systems that can generate new content such as text, images, audio, or video. An LLM is a specialized type of Generative AI model focused primarily on understanding and generating language.

---

# 5. Prompt, Prompting, and Prompt Engineering

The way you communicate with AI significantly influences the quality of the output.

Although **prompt, prompting, and prompt engineering** sound similar, they refer to different concepts and represent different levels of interaction with AI.

## Prompt

A **prompt** is the specific input you provide to an AI system to get a desired response.

It can include:

* Text
* Images
* Files
* Instructions
* Questions

A prompt is essentially a **single unit of communication** with the AI.

**Goal:** **Clarity**

---

## Prompting

**Prompting** is the act of interacting with AI through prompts and iterating on the responses to achieve a useful result.

It involves a conversational **back-and-forth**, where you refine your instructions based on the AI's output.

**Goal:** **Refinement**

---

## Prompt Engineering

**Prompt engineering** is the intentional design and optimization of prompts to help AI understand the task and produce **reliable, consistent, and high-quality results**.

It involves using structured approaches, instructions, context, constraints, and prompting techniques to improve the output.



**Goal:** **Reliability and Scalability**

---

# 6. Tokens

A **token** is a small unit of text that an AI model uses to process and generate language.

AI models don't process text as complete sentences or words. Instead, the input is **broken down into smaller pieces called tokens**.

A token can be:

* A complete word — `"cat"`
* Part of a word — `"un"` + `"believable"`
* Punctuation — `"."`
* Other parts of text

The exact way text is split into tokens depends on the model and its tokenizer.

### Examples

For illustration, a tokenizer might split:

```text
"Apple" → 1 token

"Unbelievable" → 2 tokens
                ("un", "believable")

"I love AI." → 4 tokens
              ("I", "love", "AI", ".")
```

> **Note:** Token counts are model-dependent. The same text may be split differently by different AI models.

---

## Why Do Tokens Matter?

### Context Limit

Tokens determine **how much information an AI model can process at once**.

If the conversation becomes too large and exceeds the model's context limit, older content may no longer be available to the model.

### Accuracy and Quality

Well-structured and focused prompts can help the model understand the task more clearly.

However, **shorter prompts are not always better**. A concise prompt with the right context and instructions is generally more useful than simply minimizing the number of tokens.

### Why AI Can "Forget"

When the amount of input exceeds the model's available context window, earlier information may be dropped or become unavailable to the model.

This can make it appear as though the AI has **forgotten** something from earlier in the conversation.

### Efficiency

More tokens generally mean more computation.

Keeping prompts **focused and relevant** can reduce unnecessary token usage and make interactions more efficient.

# 7. Context Window

The **context window** is the maximum amount of information an AI model can process and consider at one time.

It includes things such as:

* Your current prompt
* Previous messages in the conversation
* Instructions provided to the model
* Other relevant content included in the interaction

Think of it like:

* **Short-term memory** for the AI
* A **backpack** that can only hold a certain number of tokens

The size of the context window is measured in **tokens**.

## Why Does This Matter?

When the amount of information exceeds the model's available context window, some earlier information may no longer be available to the model.

This can cause the AI to:

* Ignore or lose track of earlier instructions
* Repeat itself
* Contradict previous answers
* Lose structure or formatting
* Miss important context from earlier in the conversation

This isn't necessarily randomness—it can be a result of **context limitations**.

## How Does This Information Help You Design Better Prompts?

Understanding context windows helps you structure prompts and conversations more effectively.

### Front-load Critical Instructions

Put the most important rules, constraints, and requirements early in your prompt.

For example:

> **Important:** Answer using TypeScript, don't use external libraries, and explain the solution step by step.

This makes the critical requirements explicit and easy for the model to identify.

### Keep Prompts Focused

Avoid unnecessarily long or repetitive instructions.

Instead of putting a large amount of unrelated information into one prompt, **break complex tasks into smaller steps** when appropriate.

For example:

Instead of:

> "Build the entire application, explain every design decision, write all the code, create tests, optimize it, and document everything..."

Break it into stages:

1. Design the architecture
2. Implement the core functionality
3. Add tests
4. Review and optimize
5. Document the solution

### Reinforce Key Rules at Checkpoints

For long conversations or multi-step tasks, repeat critical requirements when necessary.

For example:

> **Reminder:** Continue using TypeScript and React. Don't introduce additional libraries.

This can help keep important constraints active throughout a long interaction.

> **Key idea:** The context window determines how much information the model can consider at once. Good prompt design helps ensure that the most important information remains clear and relevant.


# 8. Bias vs. Hallucination in AI

AI systems can fail in two important ways: they can be **unfair**, or they can be **wrong**.

**Bias** and **Hallucination** represent these two different risks.

## Bias

AI bias occurs when an AI system produces **unfair or skewed outcomes**, often because of biased, incomplete, or unrepresentative data.

### Examples

* Favouring certain groups
* Providing unequal recommendations
* Disadvantaging individuals or groups based on limited or unrepresentative data

### How to Reduce Bias

* **Testing for fairness**
* **Ensuring diverse and representative data**
* **Keeping human oversight**
* **Continuous monitoring and evaluation**

---

## Hallucination

AI hallucination occurs when an AI system **confidently generates information that is incorrect, fabricated, or not supported by reliable evidence**.

### Examples

* Fake statistics
* Incorrect facts
* Invented references or citations

### How to Reduce Hallucinations

* **Giving clear and specific prompts**
* **Providing relevant context**
* **Verifying important outputs**
* **Using AI as a co-pilot, not a replacement**

> **Key distinction:** Bias results in **unfair or skewed outcomes**, while hallucination results in **incorrect or fabricated information**.

---

# 9. Human-in-the-Loop (HITL)

**Human-in-the-Loop (HITL)** means a human remains involved at key points of an AI process — reviewing, correcting, approving, or overriding the AI's output.

It ensures that **AI doesn't operate completely on its own**, especially in situations where:

* Judgment is needed
* Context matters
* Risks are high
* People may be affected

### Practical Example

**AI-powered loan approval:**

An AI system analyses a customer's financial information and recommends whether a loan should be approved.

Instead of automatically approving or rejecting the application, a **human loan officer reviews the AI's recommendation** and makes the final decision.

The human can:

* **Approve** the recommendation
* **Reject** the recommendation
* **Override** the AI's decision
* **Request additional information**

This is an example of **Human-in-the-Loop**, because the AI assists with the decision while a human remains responsible for the final outcome.

> **Key idea:** AI makes the recommendation; **the human remains in control of the decision.**
