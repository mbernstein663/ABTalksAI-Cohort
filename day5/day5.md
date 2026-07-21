# Context engineering

Today's learning is dedicated to understanding the value of and gathering effective strategies of context engineering. It's effectively a fancy term for a soft skill that involves properly contextualizing an ask from AI.

# Prompt A Example

**Prompt**: Create a 30-day learning roadmap. Include: - Weekly milestones - Daily tasks - Resources - Projects - Final outcome Make it practical and beginner-friendly.

**Response**: # 30-Day Practical AI Learning Roadmap

## Objective

In 30 days, develop enough practical AI skill to:

* Write reliable, structured prompts
* Understand basic machine-learning and large-language-model concepts
* Use AI for research, analysis, writing, and problem-solving
* Call an AI model from Python
* Build and present a small AI-powered application

## Daily Study Structure

Commit **60–90 focused minutes per day**:

* **15–25 minutes:** Learn
* **30–45 minutes:** Practice
* **15–20 minutes:** Document what you learned
* **5 minutes:** Save your best prompt, code, or result

Do not spend the month passively watching tutorials. Every learning session must produce something.

---

# Week 1: AI and Prompting Fundamentals

## Weekly Milestone

By the end of Week 1, you will understand how generative AI works at a basic level and have a reusable library of at least 10 prompts.

### Day 1 — Understand Generative AI

**Learn**

* What artificial intelligence, machine learning, and generative AI mean
* How chat-based AI differs from a search engine
* Common AI strengths and weaknesses

**Task**

Ask an AI tool to explain the same topic:

1. To a five-year-old
2. To a college student
3. To a technical professional

Compare the outputs.

**Deliverable:** One page of notes explaining generative AI in your own words.

### Day 2 — Learn Basic Prompt Structure

Study this structure:

**Role + Task + Context + Constraints + Output Format**

**Task**

Rewrite five vague prompts using this structure.

Example:

Weak prompt:

> Explain exercise.

Improved prompt:

> Act as a certified personal trainer. Explain progressive overload to a beginner using fewer than 200 words, one analogy, and one practical example.

**Deliverable:** Five before-and-after prompts.

### Day 3 — Practice Role-Based Prompting

**Learn**

Assigning the model a role helps define the perspective, vocabulary, priorities, and expected level of expertise.

**Task**

Ask the same question from four roles:

* Teacher
* Data scientist
* Business owner
* Skeptical reviewer

**Deliverable:** A short comparison of how the role changed each answer.

### Day 4 — Add Context and Constraints

**Learn**

Practice supplying:

* Audience
* Goal
* Background information
* Length
* Tone
* Required sections
* Excluded content

**Task**

Create one detailed prompt for:

* Writing
* Research
* Planning
* Learning
* Data analysis

**Deliverable:** Five structured prompts.

### Day 5 — Control Output Formats

Ask the model to return information as:

* A checklist
* A table
* JSON
* A step-by-step explanation
* An executive summary

**Task**

Use one topic and request all five formats.

**Deliverable:** A format comparison showing which format works best for which situation.

### Day 6 — Improve Weak Responses

Use this revision loop:

1. Generate an answer
2. Identify what is missing
3. Add clearer requirements
4. Generate again
5. Compare the versions

**Task**

Complete this loop three times.

**Deliverable:** Three examples showing the original prompt, revised prompt, and improvement.

### Day 7 — Weekly Project: Prompt Library

Build a document containing at least 10 reusable prompts:

* Learning prompt
* Research prompt
* Summarization prompt
* Writing prompt
* Brainstorming prompt
* Planning prompt
* Data-analysis prompt
* Critique prompt
* Interview-preparation prompt
* Project-planning prompt

For every prompt, include:

* Purpose
* Prompt template
* Example input
* Expected output

**Week 1 Project:** Personal Prompt Library

---

# Week 2: Reliable AI Workflows

## Weekly Milestone

By the end of Week 2, you will be able to create multi-step AI workflows and evaluate whether an output is accurate, useful, and complete.

### Day 8 — Understand Hallucinations

**Learn**

AI can generate confident answers that are incomplete, unsupported, or incorrect.

**Task**

Ask the model five factual questions. Verify each answer using trustworthy sources.

**Deliverable:** A verification log with correct, incorrect, and uncertain claims.

### Day 9 — Ask for Evidence

Practice prompts that require:

* Sources
* Assumptions
* Confidence levels
* Missing information
* Alternative explanations

**Task**

Create a reusable fact-checking prompt.

**Deliverable:** One verification template.

### Day 10 — Break Complex Tasks into Steps

Take one large task and divide it into:

1. Planning
2. Information gathering
3. Drafting
4. Criticism
5. Revision
6. Final formatting

**Task**

Use the process to create a short report on a topic you understand.

**Deliverable:** A complete multi-step workflow.

### Day 11 — Use AI as a Tutor

Create a tutoring prompt that tells the model to:

* Assess your current understanding
* Explain one concept at a time
* Give examples
* Ask questions
* Correct mistakes
* Increase difficulty gradually

**Task**

Complete a 30-minute tutoring session.

**Deliverable:** Notes containing three concepts learned and three mistakes corrected.

### Day 12 — Use AI as a Critic

Create separate critique roles:

* Technical reviewer
* Hiring manager
* Customer
* Editor
* Skeptic

**Task**

Submit the same piece of work to all five reviewers.

**Deliverable:** A prioritized revision list.

### Day 13 — Create a Repeatable Workflow

Choose one recurring task, such as:

* Studying
* Preparing job applications
* Analyzing articles
* Planning workouts
* Writing social posts
* Summarizing meeting notes

Design a repeatable workflow with clear inputs and outputs.

**Deliverable:** A one-page standard operating procedure.

### Day 14 — Weekly Project: AI Research Brief

Research a topic and produce a two-page brief containing:

* Main question
* Key findings
* Supporting evidence
* Conflicting viewpoints
* Limitations
* Recommended next steps

Use AI to help organize and critique the work, but manually verify important claims.

**Week 2 Project:** Evidence-Based Research Brief

---

# Week 3: Python and AI Application Basics

## Weekly Milestone

By the end of Week 3, you will have a working Python program that sends user input to an AI model and processes the response.

### Day 15 — Refresh Python Fundamentals

Review:

* Variables
* Strings
* Lists
* Dictionaries
* Loops
* Functions
* Reading files
* Error handling

**Task**

Write a Python script that reads a text file and reports:

* Word count
* Character count
* Most common words

**Deliverable:** Working Python script.

### Day 16 — Work with JSON

**Learn**

AI applications frequently exchange structured data using JSON.

**Task**

Create a Python dictionary containing:

* User question
* Category
* Difficulty
* Response
* Timestamp

Save it to a `.json` file and load it again.

**Deliverable:** JSON practice script.

### Day 17 — Understand APIs

Learn these concepts:

* Request
* Response
* Endpoint
* API key
* Headers
* JSON payload
* Status code
* Rate limit

**Task**

Draw a simple flow:

**User → Python application → AI API → Response → User**

**Deliverable:** API flow diagram and vocabulary notes.

### Day 18 — Make Your First AI API Request

Follow an official API quickstart and make one basic request from Python.

**Task**

Create a program that:

1. Accepts a topic
2. Sends a structured prompt
3. Prints a beginner-friendly explanation
4. Handles a failed request without crashing

**Deliverable:** First AI-powered Python script.

### Day 19 — Build Reusable Prompt Functions

Create functions such as:

```python
def explain_topic(topic):
    ...

def generate_quiz(topic):
    ...

def review_answer(question, answer):
    ...
```

**Task**

Test each function with at least three inputs.

**Deliverable:** A small prompt utility module.

### Day 20 — Add Structured Output

Ask the model to return predictable fields such as:

```json
{
  "summary": "",
  "key_terms": [],
  "quiz_questions": [],
  "next_step": ""
}
```

Parse the response in Python.

**Deliverable:** Script that converts an AI response into usable structured data.

### Day 21 — Weekly Project: Command-Line AI Tutor

Build a command-line program that:

* Asks the user for a topic
* Explains the topic
* Generates three questions
* Accepts the user’s answers
* Provides feedback
* Recommends what to study next

**Week 3 Project:** Python AI Tutor

---

# Week 4: Build and Present an AI Product

## Weekly Milestone

By the end of Week 4, you will have a functioning AI application with documentation, testing examples, and a public demonstration.

### Day 22 — Select the Capstone Problem

Build an **AI Career Assistant** that can:

* Accept a job description
* Accept resume or experience text
* Extract required skills
* Identify likely skill gaps
* Generate interview questions
* Recommend a learning plan

Define:

* Target user
* User problem
* Inputs
* Outputs
* Features that are essential
* Features that are unnecessary

**Deliverable:** One-page project specification.

### Day 23 — Design the Prompt Pipeline

Separate the application into steps:

1. Analyze job description
2. Extract skills and responsibilities
3. Analyze candidate experience
4. Compare candidate with role
5. Produce recommendations
6. Generate interview questions

**Deliverable:** Prompt pipeline with one prompt for each step.

### Day 24 — Build the Core Python Logic

Create the functions needed to:

* Receive text
* Build prompts
* Call the model
* Parse results
* Display errors clearly

**Deliverable:** Working backend script.

### Day 25 — Build a Streamlit Interface

Create fields for:

* Job description
* Resume or experience
* Target role
* Analysis button

Display:

* Match summary
* Strongest qualifications
* Missing skills
* Interview questions
* Recommended next steps

**Deliverable:** Application running locally.

### Day 26 — Improve the User Experience

Add:

* Clear instructions
* Loading feedback
* Input validation
* Helpful error messages
* Organized output sections
* Downloadable or copyable results

**Deliverable:** Usable second version.

### Day 27 — Test the Application

Create at least five test cases:

* Strong candidate match
* Weak candidate match
* Empty input
* Extremely short job description
* Unrelated experience

Record:

* Input
* Expected behavior
* Actual behavior
* Problem found
* Fix applied

**Deliverable:** Testing document.

### Day 28 — Improve Reliability

Evaluate the application for:

* Accuracy
* Specificity
* Consistency
* Unsupported assumptions
* Formatting problems
* Usefulness of recommendations

Revise prompts based on the results.

**Week 4 Project:** Tested AI Career Assistant

---

# Final Two Days

### Day 29 — Document and Publish

Create a clear README containing:

* Project overview
* Problem being solved
* Main features
* Technology used
* Setup instructions
* Example input and output
* Limitations
* Future improvements

Add screenshots and clean unnecessary files from the repository.

**Deliverable:** Portfolio-ready repository.

### Day 30 — Demonstrate and Reflect

Record a two-to-three-minute demonstration covering:

1. The problem
2. How the application works
3. The AI workflow
4. A live example
5. Limitations
6. What you learned

Write a final reflection:

* What can I now build?
* What do I still not understand?
* Which part of the project is weakest?
* What should I study during the next 30 days?
* What evidence proves that I improved?

**Deliverable:** Demo video, finished repository, and next-month plan.

---

# Core Resources

## Prompt Engineering

* **OpenAI Academy: Prompting** — an introductory resource on designing and refining prompts for stronger outputs.
* **OpenAI Academy: Introduction to Prompt Engineering** — a beginner-oriented introduction to prompt construction and experimentation.
* **Anthropic Documentation** — includes an introduction to Claude, developer tools, prompting resources, and example notebooks.

## AI and Machine Learning Fundamentals

* **Google Machine Learning Crash Course** — modular lessons that can be completed independently, allowing beginners to focus on the most relevant concepts first.
* **Google ML Exercises** — practice activities covering multiple machine-learning topics.

## Python

* **Official Python Tutorial** — an introductory guide to Python’s core language concepts and features.

## Application Development

* **OpenAI Developer Quickstart** — official Python examples for making an initial API request and building with the Responses API.
* **Streamlit Get Started Guide** — installation instructions, core concepts, widgets, application structure, and introductory tutorials.

---

# Final Outcome

After completing the roadmap, you should have:

1. A reusable prompt library
2. An evidence-based research brief
3. A command-line AI tutor
4. A functional Streamlit AI application
5. A documented GitHub repository
6. A short project demonstration
7. A testing and evaluation process
8. A clear plan for the next 30 days

The real outcome is not “understanding AI.” It is having visible proof that you can design, build, test, and explain an AI-powered workflow.

---

Prompt A provided a highly overengineered, long-winded, but strong roadmap. Its answer will likely be similar to the second one because CGPT has already build a profile on me.

---

# Prompt B

**Prompt**: PROMPT B (WITH CONTEXT)

Create a 30-day learning roadmap.

Context:
- Current Situation: Fresher professional seeking data science and DS-adjacent roles
- Current Skills: python, R, SQL (need refreshing), ML
- Goal: Data science entry level role
- Available Time: 1 hour per day
- Experience Level: Beginner to intermediate
- Preferred Learning Style: I like to learn by building without skipping fundamentals, and by watching videos

Include:
- Weekly milestones
- Daily tasks
- Resources
- Projects
- Final outcome

Make it short, practical and beginner-friendly.

**Response**:

# 30-Day Data Science Roadmap

## Daily Structure — 1 Hour

* **15 minutes:** Watch or read
* **35 minutes:** Code without copying blindly
* **10 minutes:** Record key concepts, mistakes, and commands

## Main Project

Build a **Customer Churn Prediction and Retention Dashboard** containing:

* SQL-based data exploration
* Python data cleaning and visualization
* A reproducible ML pipeline
* Model evaluation and interpretation
* A simple Streamlit application
* A professional GitHub README

---

# Week 1: Refresh the Core Tools

## Milestone

Clean, query, explore, and visualize a dataset using Python and SQL.

### Day 1 — Python Refresher

Review variables, lists, dictionaries, loops, functions, comprehensions, and error handling.

**Task:** Complete 8–10 small Python exercises.

### Day 2 — pandas Refresher

Review filtering, grouping, sorting, merging, missing values, and data types.

**Task:** Load the project dataset and create a basic data-quality report.

### Day 3 — Data Visualization

Review histograms, box plots, bar charts, scatter plots, and correlation matrices.

**Task:** Create five useful visualizations and explain what each reveals.

### Day 4 — SQL Fundamentals

Review `SELECT`, `WHERE`, `ORDER BY`, `GROUP BY`, `HAVING`, and aggregate functions.

**Task:** Complete SQLBolt lessons and exercises on these topics. SQLBolt provides interactive browser-based SQL practice.

### Day 5 — SQL Joins and Window Functions

Review joins, subqueries, CTEs, `ROW_NUMBER`, `RANK`, and grouped calculations.

**Task:** Write five queries that answer business questions about the dataset.

### Day 6 — Statistics Refresher

Review:

* Mean, median, variance, and distributions
* Correlation versus causation
* Confidence intervals
* Hypothesis testing
* Statistical versus practical significance

**Task:** Perform one hypothesis test and explain the result in plain English.

### Day 7 — Mini Project: Exploratory Analysis

Create a short notebook containing:

* Data-quality checks
* Five business questions
* SQL or pandas answers
* Visualizations
* Three actionable findings

---

# Week 2: Rebuild Machine-Learning Fundamentals

## Milestone

Train and correctly evaluate baseline classification models.

### Day 8 — ML Workflow

Review features, targets, training data, validation data, testing data, and data leakage.

**Task:** Create a train-test split and identify three possible leakage risks.

### Day 9 — Preprocessing

Review missing-value imputation, scaling, and categorical encoding.

**Task:** Build a scikit-learn preprocessing pipeline.

### Day 10 — Logistic Regression

Watch a StatQuest explanation and review how logistic regression produces class probabilities. StatQuest’s ML playlist breaks major methods into focused video explanations.

**Task:** Train logistic regression and interpret five coefficients.

### Day 11 — Decision Trees and Random Forests

Review splitting, tree depth, overfitting, bagging, and feature importance.

**Task:** Compare a decision tree with a random forest.

### Day 12 — Evaluation Metrics

Review:

* Accuracy
* Precision
* Recall
* F1
* ROC-AUC
* Confusion matrix

**Task:** Explain which metric matters most for churn and why.

### Day 13 — Cross-Validation

Review cross-validation and why one train-test split can be misleading.

**Task:** Compare models using five-fold cross-validation.

### Day 14 — Weekly Project: Baseline Model Report

Produce a report containing:

* Baseline prediction
* Two or three models
* Cross-validation results
* Confusion matrices
* Selected model
* Business interpretation

Google’s Machine Learning Crash Course provides videos, visualizations, and exercises for reviewing these fundamentals.

---

# Week 3: Build an End-to-End Data Science Project

## Milestone

Turn the notebook into a reproducible modeling pipeline.

### Day 15 — Feature Engineering

Create meaningful features based on customer behavior, usage, tenure, or spending.

**Task:** Add three justified features—not random transformations.

### Day 16 — Class Imbalance

Inspect class distribution and compare:

* Class weights
* Threshold adjustment
* Precision-recall trade-offs

**Task:** Document whether imbalance treatment is actually necessary.

### Day 17 — Hyperparameter Tuning

Use `RandomizedSearchCV` or a small `GridSearchCV`.

**Task:** Tune one model and compare it with the untuned baseline.

### Day 18 — Model Interpretation

Review permutation importance and model coefficients.

**Task:** Identify the strongest churn drivers and explain them without technical jargon.

### Day 19 — Error Analysis

Examine false positives and false negatives.

**Task:** Find patterns among incorrect predictions and propose improvements.

### Day 20 — Refactor the Code

Separate the project into:

* Data loading
* Preprocessing
* Training
* Evaluation
* Prediction

**Task:** Move reusable code from the notebook into Python scripts.

### Day 21 — Weekly Project: Final Model Pipeline

Save:

* Preprocessing pipeline
* Trained model
* Evaluation results
* Feature definitions
* Example predictions

The free scikit-learn MOOC covers predictive pipelines, model evaluation, and other practical ML topics.

---

# Week 4: Deployment, Portfolio, and Interviews

## Milestone

Publish and confidently explain one complete project.

### Day 22 — Build a Streamlit Interface

Create inputs for customer information and display:

* Churn probability
* Predicted class
* Main risk indicators

Streamlit’s official guide covers installation and creation of a first application.

### Day 23 — Add a Business Dashboard

Display:

* Customer-risk distribution
* Most important features
* High-risk customer segments
* Suggested retention actions

### Day 24 — Test the Application

Test:

* Missing values
* Invalid inputs
* Extreme values
* Normal customers
* High-risk customers

**Task:** Record and fix every failure.

### Day 25 — Clean the Repository

Use a clear structure:

```text
project/
├── app.py
├── notebooks/
├── src/
├── data/
├── models/
├── requirements.txt
└── README.md
```

### Day 26 — Write the README

Include:

* Business problem
* Dataset
* Methods
* Results
* Application screenshots
* Setup instructions
* Limitations
* Future improvements

### Day 27 — SQL Interview Practice

Practice 8–10 questions covering:

* Aggregations
* Joins
* CTEs
* Window functions
* Ranking
* Date calculations

### Day 28 — ML Interview Practice

Explain aloud:

* Bias versus variance
* Overfitting
* Cross-validation
* Logistic regression
* Random forest
* Precision versus recall
* Data leakage
* Feature importance

Do not memorize definitions. Explain each concept using your project.

### Day 29 — Project Presentation

Prepare a three-minute explanation:

1. What problem did you solve?
2. How did you prepare the data?
3. Why did you choose the model?
4. How well did it perform?
5. How could a business use it?
6. What are its limitations?

Record yourself and remove vague or overly technical language.

### Day 30 — Publish and Apply

* Publish the GitHub repository
* Add the project to your resume
* Add it to LinkedIn or your portfolio
* Apply to three well-matched roles
* Record weaknesses for the next 30-day cycle

---

# Final Outcome

After 30 days, you should have:

* Refreshed Python and SQL fundamentals
* Rebuilt your understanding of core ML concepts
* One complete end-to-end data science project
* A deployed Streamlit application
* A professional GitHub repository
* Practiced SQL and ML interview explanations
* A concrete project story for resumes and interviews

Your target is not to “finish learning data science.” Your target is to produce credible evidence that you can take a business problem from raw data to a usable result.

---

## Results

Overall, the second prompt improved results drastically and made more sense chronologically. This is because I was highly specific about what I needed, and that kept the AI on task when generating a result. Overall, it seems that assigning a role, listing out requirements, listing out context, and targetting specifics when prompting will save time and produce higher quality.
