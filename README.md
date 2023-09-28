# Prompts: ChatGPT-3.5

A collection of prompts for the free version of ChatGPT.

The primary purpose of this project is to offer a diverse range of prompt templates that can be used to interact with ChatGPT effectively. 

These templates are designed to streamline the process of generating high-quality responses from ChatGPT; making it easier for developers, researchers, and enthusiasts to harness the full potential of the A.I. model.

Made by Cas van Vliet: https://casvanvliet.com

# List of Prompts

**basic template**

{"Information":"your_info",\n "Role":"ideal_agent",\n1 "Task":"your_task",\n2 "Completion":"your_ideal_answer"}

> {"Information":"your_info",\n "Role":"ideal_agent",\n1 "Task":"your_task",\n2 "Completion":"your_ideal_answer"}

**1. Text Summarizer**

{["Text"]:"your_text_here" ### "Role":"Text Summarizer", "Task":"Summarize the provided '["Text"]' into a concise and coherent summary.", "Completion":"A well-structured summary of the '["Text"]' that captures its key points and main ideas accurately while maintaining readability and coherence."}

> {["Text"]:"your_text_here" ### "Role":"Content Summarizer", "Task":"Summarize the provided '["Text"]' into a concise and coherent summary.", "Completion":"A well-structured summary of the '["Text"]' that captures its key points and main ideas accurately while maintaining readability and coherence."}

**2. Research Assistant** 

{["Topic]":"you_topic_here" ### "Role":"Research Assistant", "Task":"Compile a comprehensive research report on the topic '["Topic"]', including relevant data, statistics, and insights.", "Completion":"A detailed research report on '["Topic"]' that covers the latest information, data, and analysis, providing valuable insights and references."}

> {["Topic]":"Prompt Engineering" ### "Role":"Research Assistant", "Task":"Compile a comprehensive research report on the topic '["Topic"]', including relevant data, statistics, and insights.", "Completion":"A detailed research report on '["Topic"]' that covers the latest information, data, and analysis, providing valuable insights and references."}

**3. Schedule Planner**

{"Information":"your_daily_activities",\n "Role":"Schedule Planner",\n1 "Task":"Create a schedule for my daily activities.",\n2 "Completion":"A concise, and detailed, and realistic schedule for my daily activities."}

> {"Information":"1. check and respond to my e-mails, 2. Workout in the gym, Bring the kids to school, Grocery shopping, Retrieve the kids from school, cook dinner, do my bookkeeping",\n "Role":"Schedule Planner",\n1 "Task":"Create a schedule for my daily activities.",\n2 "Completion":"A concise, and detailed, and realistic schedule for my daily activities."}
