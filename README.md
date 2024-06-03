## Inspiration
Vertex AI agent has high potential to enable interactive digital experiences in schools. Imagine a school in India located in the mountains - using Vertext AI RAGs to learn from the syllabus designated more interactively. Solving maths problems from their textbook exercises using Vertex AI, learning about history with a summary in the regional languages. 

This opens up a new dimension in school-based learning mainly where the students get access to - books, practice exams, content, health and physical information—the single Vertex AI-based place to interact with.

## What it does
The Indian Mountain School let students:
- Explore their textbooks using Generative AI
- Solve Maths problems from textbooks with the help of Generative AI
- Complete homework with the help of Generative AI.
- Teachers generating questions for the practice of the students using Vertex AI. 
- Learn in the **regional languages** from textbooks
- Check the scorecard and areas of improvement by talking to **Scorecard Bot**.
- Book an admission to school using the **Admission Bot**.
- Health and physical teachers can take assistance from the **Health Both** to enhance their knowledge

## How we built it
We've built an interactive school experience with Vertex AI Agent Builder using
- Vertex AI Search Agent
- Vertex AI Agent
- Vertex AI DiaglogFlowCS

The search agent performs RAGs on the prebuilt datastores based on the designated syllabus. This search agent indexes and makes textbooks from various subjects and languages across grades.

Vertex AI Agent uses tools and agents to complete the accomplished goals using instructions, grounding and examples.  The scorecard bot is built by training the RAGs on 10000 student's scorecard data. Based on the datastore, the agent can interpret and communicate the scorecards of the students in a short and simple way

Vertex AI DiaglogFlowCS brings the benefit of making the generated content available even during a lack of internet connection using helpline number. Health and physical consultants at a school can leverage the agents to enhance their knowledge. 

## Challenges we ran into
We did not face many challenges as all the Google Cloud Vertex AI APIs are easy to integrate into the UI with prebuilt components. I got to learn some of the new concepts on the RAG and the grounding of Gemini.

## Accomplishments that we're proud of
Ability to seamlessly integrate Vertex AI into The Indian Mountain School site. 

## What we learned
- Vertex AI Agent Builder
- Tools, agents and the datastores
- Retrieval-Augmented Generation
- DiaglogFlow CX

## What's next for The Indian Mountain School - Digital Experience by Vertex AI
- Enhance the scope by adding several more regional textbooks designated by the respective authorities
- Adding recommended sports content into the Agent
- Building more video-based content for the students to learn effectively. 
