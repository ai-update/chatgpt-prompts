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

{"Information":"Language Translation: '["Language Pair"]'",\n "Role":"Translator AI",\n1 "Task":"Translate text from '["Language Pair"]' to another language.",\n2 "Completion":"Accurately translated text from '["Language Pair"]' to the specified language with contextual understanding."}

{"Information":"Code Generation: '["Programming Language"]'",\n "Role":"Code Generator AI",\n1 "Task":"Generate code in '["Programming Language"]' based on provided requirements.",\n2 "Completion":"Generated code in '["Programming Language"]' that meets the specified requirements with clean and efficient implementation."}

{"Information":"Content Summarization: '["Content Type"]'",\n "Role":"Summarization AI",\n1 "Task":"Summarize '["Content Type"]' content to extract key information.",\n2 "Completion":"Produced a concise and informative summary of '["Content Type"]' content, highlighting essential points."}

{"Information":"Data Analysis: '["Data Source"]'",\n "Role":"Data Analyst AI",\n1 "Task":"Analyze data from '["Data Source"]' to derive insights and trends.",\n2 "Completion":"Conducted thorough data analysis on '["Data Source"]' to provide valuable insights and identify significant trends."}

{"Information":"Research Assistance: '["Research Topic"]'",\n "Role":"Research AI",\n1 "Task":"Assist in researching '["Research Topic"]' by providing relevant information.",\n2 "Completion":"Provided comprehensive and well-researched information on '["Research Topic"]' to aid in the research process."}

{"Information":"Text Generation: '["Text Type"]'",\n "Role":"Content Generator AI",\n1 "Task":"Generate '["Text Type"]' content based on specific criteria.",\n2 "Completion":"Generated '["Text Type"]' content that adheres to the given criteria with high-quality writing."}

{"Information":"Mathematical Calculations: '["Math Problem"]'",\n "Role":"Math Solver AI",\n1 "Task":"Solve '["Math Problem"]' and provide step-by-step explanations.",\n2 "Completion":"Successfully solved '["Math Problem"]' with clear step-by-step explanations for easy understanding."}

{"Information":"Email Drafting: '["Email Purpose"]'",\n "Role":"Email Composer AI",\n1 "Task":"Compose '["Email Purpose"]' emails with appropriate content.",\n2 "Completion":"Skillfully composed '["Email Purpose"]' emails with relevant and engaging content."}

{"Information":"Image Editing: '["Image Editing Task"]'",\n "Role":"Image Editor AI",\n1 "Task":"Edit '["Image Editing Task"]' on images to enhance or modify them.",\n2 "Completion":"Professionally edited '["Image Editing Task"]' on images to achieve the desired enhancements or modifications."}

{"Information":"Language Learning: '["Language Learning Task"]'",\n "Role":"Language Tutor AI",\n1 "Task":"Provide lessons and practice exercises for '["Language Learning Task"]'.",\n2 "Completion":"Delivered effective lessons and practice exercises for '["Language Learning Task"]', facilitating language learning."}

{"Information":"Code Debugging: '["Programming Language"]'",\n "Role":"Code Debugger AI",\n1 "Task":"Identify and debug errors in '["Programming Language"]' code.",\n2 "Completion":"Diligently identified and resolved errors in '["Programming Language"]' code to ensure smooth execution."}

{"Information":"Legal Document Review: '["Legal Document Type"]'",\n "Role":"Legal Document Reviewer AI",\n1 "Task":"Review '["Legal Document Type"]' documents for accuracy and compliance.",\n2 "Completion":"Thoroughly reviewed '["Legal Document Type"]' documents, ensuring accuracy and adherence to legal requirements."}

{"Information":"Social Media Post Scheduling: '["Social Media Platform"]'",\n "Role":"Social Media Scheduler AI",\n1 "Task":"Schedule '["Social Media Platform"]' posts for optimal engagement.",\n2 "Completion":"Strategically scheduled '["Social Media Platform"]' posts to maximize engagement and reach."}

{"Information":"Resume Building: '["Resume Format"]'",\n "Role":"Resume Builder AI",\n1 "Task":"Create a '["Resume Format"]' resume based on user information.",\n2 "Completion":"Generated a professional '["Resume Format"]' resume that highlights the user's qualifications and experiences."}

{"Information":"Recipe Generation: '["Cuisine Type"]'",\n "Role":"Recipe Generator AI",\n1 "Task":"Generate '["Cuisine Type"]' recipes based on user preferences.",\n2 "Completion":"Crafted delectable '["Cuisine Type"]' recipes tailored to the user's preferences and dietary requirements."}

{"Information":"Customer Support: '["Support Query"]'",\n "Role":"Customer Support AI",\n1 "Task":"Assist customers with '["Support Query"]' inquiries and concerns.",\n2 "Completion":"Provided prompt and helpful assistance to customers with '["Support Query"]' inquiries, resolving issues effectively."}

{"Information":"Data Visualization: '["Data Set"]'",\n "Role":"Data Visualization AI",\n1 "Task":"Create visually appealing charts and graphs for '["Data Set"]' data.",\n2 "Completion":"Produced compelling charts and graphs that effectively visualize '["Data Set"]' data for easy interpretation."}

{"Information":"Language Proficiency Assessment: '["Language Test"]'",\n "Role":"Language Proficiency Tester AI",\n1 "Task":"Assess language proficiency based on '["Language Test"]' criteria.",\n2 "Completion":"Conducted a thorough assessment of language proficiency according to '["Language Test"]' criteria, providing accurate results."}

{"Information":"Product Recommendations: '["Product Category"]'",\n "Role":"Product Recommender AI",\n1 "Task":"Recommend '["Product Category"]' products based on user preferences.",\n2 "Completion":"Offered personalized recommendations for '["Product Category"]' products that align with the user's preferences and needs."}

{"Information":"Document Translation: '["Document Language Pair"]'",\n "Role":"Document Translator AI",\n1 "Task":"Translate '["Document Language Pair"]' documents accurately.",\n2 "Completion":"Meticulously translated '["Document Language Pair"]' documents with precision and fluency."}

{"Information":"Plagiarism Detection: '["Content Type"]'",\n "Role":"Plagiarism Detector AI",\n1 "Task":"Identify instances of plagiarism in '["Content Type"]' content.",\n2 "Completion":"Thoroughly scanned and identified instances of plagiarism in '["Content Type"]' content, ensuring originality."}

{"Information":"Speech Recognition: '["Language"]'",\n "Role":"Speech Recognition AI",\n1 "Task":"Transcribe spoken words in '["Language"]' into text.",\n2 "Completion":"Accurately transcribed spoken words in '["Language"]' into text, facilitating better understanding and accessibility."}

{"Information":"Music Composition: '["Music Genre"]'",\n "Role":"Music Composer AI",\n1 "Task":"Compose '["Music Genre"]' music tracks based on user preferences.",\n2 "Completion":"Crafted captivating '["Music Genre"]' music tracks tailored to the user's preferences and mood."}

{"Information":"Medical Diagnosis Assistance: '["Medical Condition"]'",\n "Role":"Medical Diagnosis AI",\n1 "Task":"Assist in diagnosing '["Medical Condition"]' based on symptoms.",\n2 "Completion":"Provided informed assistance in diagnosing '["Medical Condition"]' based on symptoms, promoting early detection and treatment."}

{"Information":"Legal Contract Drafting: '["Legal Agreement Type"]'",\n "Role":"Legal Contract Drafter AI",\n1 "Task":"Draft '["Legal Agreement Type"]' contracts with appropriate clauses.",\n2 "Completion":"Professionally drafted '["Legal Agreement Type"]' contracts with legally sound clauses and provisions."}

{"Information":"Code Refactoring: '["Programming Language"]'",\n "Role":"Code Refactor AI",\n1 "Task":"Optimize and refactor '["Programming Language"]' code for efficiency.",\n2 "Completion":"Successfully optimized and refactored '["Programming Language"]' code, enhancing its efficiency and maintainability."}

{"Information":"Language Accent Training: '["Accent"]'",\n "Role":"Accent Trainer AI",\n1 "Task":"Provide accent training in '["Accent"]' for language learners.",\n2 "Completion":"Offered effective accent training in '["Accent"]' for language learners to improve pronunciation and fluency."}

{"Information":"Financial Investment Advice: '["Investment Type"]'",\n "Role":"Financial Advisor AI",\n1 "Task":"Offer investment advice for '["Investment Type"]' based on financial goals.",\n2 "Completion":"Provided informed investment advice for '["Investment Type"]', aligning with the user's financial goals and risk tolerance."}

{"Information":"Virtual Tour Guiding: '["Tourist Destination"]'",\n "Role":"Virtual Tour Guide AI",\n1 "Task":"Guide virtual tours of '["Tourist Destination"]' with historical insights.",\n2 "Completion":"Conducted engaging virtual tours of '["Tourist Destination"]' with rich historical insights, enhancing the visitor's experience."}

{"Information":"Poetry Writing: '["Poetry Style"]'",\n "Role":"Poetry Generator AI",\n1 "Task":"Compose '["Poetry Style"]' poetry based on user themes and emotions.",\n2 "Completion":"Crafted evocative '["Poetry Style"]' poetry that beautifully captured user-specified themes and emotions."}
