# Reflection: Learning Activity (W7 A2)

Based on what you learned from class readings and your knowledge from other courses on human learning, you are going to create a 20-minute learning activity that you believe would spur logical and critical thinking. This is Task 1 in the module. The activity will include the following elements:

a statement of the theoretical framework you used as the basis for instruction,
a learning goal and at least two objectives,
a set of instructions for the learners,
recommended technologies for learners to use, and
a form of assessment.

Background:
I modeled the study based on a microlearning product that I am building: PrimsSkills.ai

PrismSkills is meant for businesses and corporate learners. Prism allows an organization to help their workforce learn AI using courses customized for their role, industry and use cases. Prism can provide on-demand learning in addition to the regular courses offered through its catalog. The entire content of the lessons, interactive exercises and assessments are contextually relevant for the learner. 

[![Watch the video](https://img.youtube.com/vi/RbcTBj4UUDw/0.jpg)](https://www.youtube.com/watch?v=RbcTBj4UUDw)

The course hierarchy is:
Course -> Modules -> Lessons -> Activities -> Assessment


Here's a snippet from the course structure: 

```
"course_title": "AI Safety and Security",
  "target_audience": "Working professionals across all business functions who use AI tools and handle company data.",
  "learning_level": "Beginner",
  "estimated_duration": "3 Hours",
  "overview": "This course shifts AI security from an IT-only problem to a daily professional habit. In the era of Generative AI, many of the most common vulnerabilities are not broken firewalls, but unsafe prompts, manipulated inputs, and over-trusted outputs. Professionals will learn how to safely handle sensitive data, recognize AI-enabled social engineering such as deepfakes and targeted phishing, and understand the risks of Shadow AI. The course provides practical, non-technical frameworks for interacting with AI tools securely while protecting corporate assets, personal information, and decision quality.",
  "prerequisites": [
    "None — designed for professionals with no prior technical, cybersecurity, or coding background"
  ],
  "learning_outcomes": [
    "Differentiate between Public and Enterprise AI tools to reduce the risk of unintentional data leaks and intellectual property exposure",
    "Identify and sanitize Sensitive, Protected, and Confidential information before interacting with any AI system",
    "Recognize AI-enhanced cyber threats, including hyper-targeted phishing, voice cloning, and deepfake impersonation",
    "Explain the basic mechanics of indirect prompt injection and why summarizing untrusted documents or webpages can be dangerous",
    "Apply a Zero-Trust verification checklist to AI-generated outputs, links, recommendations, and communications",
    "Establish a personal incident response protocol for reporting suspected AI security breaches, unsafe tool use, or data leaks"
  ],
  "tags": [
    "Cybersecurity",
    "AI Safety",
    "Data Privacy",
    "Risk Management",
    "Shadow AI",
    "Deepfakes",
    "Corporate Governance"
  ],
  ```

For the purpose of this assignment I came up with an assessment from a course "AI Safety and Security". 

As I mentioned in my paper, the goal of this activity is to help the learner assess their skills. By providing a contextuall relevant scenario at the right level of learning (beginner) we help reinforce the mental model and key concept that all AI output should be verified.

  **Learning Goal:**
  Use this activity as a simulation and enable learners to make safe, high-quality decisions when interacting with AI outputs in real workplace scenarios.
  
  **Objectives:**
  1.	Identify common, risky AI outputs such as inaccurate answers, hallucinations
  2.	Adopt verification mindset (zero-trust) for AI use cases
  
  **Activity Overview:**
  This activity is part of a microlearning course lesson. Learners have been provided the background material and now they are presented with instructions, a scenario and questions. For instance,  
  General Instructions: “You are reviewing AI outputs in a real work scenario. Your job is not to generate answers—but to decide whether to trust, verify, or reject them.”
  Instructions for exercise:
  1.	Read each scenario carefully. 
  2.	Make a decision and provide a short justification.
  3.	Compare your answer with the recommended approach.
  
  **Scenario Example**
  AI generates a summary of a document but hallucinates and mixes results with its own knowledge. 
  Task/Question:
  -	What’s the right action to take?
  -	Verify information
  -	Provide grounding instructions to the AI model
  Expected respond elements:
  -	Verify all AI-generated results
  -	Improve instructions to the AI model
  Recommended technologies:
  -	Lesson
  -	A document, AI model, prompts
  
  **Assessment:**
  1. Decision quality: Did the learner choose the correct action? (e.g., verify vs blindly trust) 
  2. Reasoning quality: Did they identify the correct risk (hallucination, phishing, prompt injection, etc.)? 
  3. Risk awareness / judgment
  *	Did they show appropriate caution? 
  *	Did they apply a zero-trust mindset?
  
