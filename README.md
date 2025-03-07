# Smart India Hackathon Workshop
# Date:04/03/2025
## Register Number:212224040156
## Name:KEERTHANA R
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea
1.Virtual Board Room Experience:

A simulated panel interview environment with multi-expert involvement.
Customizable ice-breaking session followed by a structured techno-managerial question flow.
Real-time feedback for both interviewers and candidates on engagement and interaction quality.

2. AI-Powered Question Generation & Evaluation
Dynamic Question Generation:

AI suggests questions based on the candidate’s domain expertise, experience level, and role.
Real-time adaptability ensures progressive difficulty and structured assessment.

Question Relevancy Scoring:

Each question is quantified based on how well it aligns with the candidate's specialization.
Ensures fairness by minimizing bias and standardizing the evaluation process.

3. Candidate Response Evaluation & Scoring
Natural Language Processing (NLP) Based Analysis:

AI assesses candidate responses for accuracy, depth, and relevance.
Scores responses based on predefined criteria such as technical accuracy, managerial effectiveness, and articulation.

Expert Panel Review & AI-Assisted Scoring:

Experts can validate, adjust, or override AI-generated scores.
AI provides explanations for its scoring, ensuring transparency.

4. Comprehensive Suitability Score Calculation
A weighted scoring system combines:
Question Relevancy Score
Candidate Response Score
Expert Adjustments (if any)
Final suitability score helps in ranking candidates objectively.

5. Additional Features
Auto-Generated Interview Reports: Summary of interview performance, strengths, and improvement areas.
Interview Insights & Analytics: Patterns in candidate responses, frequently asked questions, and expert decision trends.
Bias Detection & Mitigation: AI ensures fairness by flagging inconsistencies in expert scoring.

## Proposed Solution / Architecture Diagram
![Screenshot (520)](https://github.com/user-attachments/assets/2b620391-aac4-48bc-acd5-76fa5d635748)


## Use Cases
![Screenshot (521)](https://github.com/user-attachments/assets/316e32a4-8681-4f22-b593-87f803a28bd9)


## Technology Stack
Front-End (User Interface)

🔹 Frameworks & Libraries:

React.js / Angular / Vue.js → Interactive UI for experts and candidates.
Bootstrap / Tailwind CSS → Modern and responsive UI design.
WebRTC → For real-time video-based interviews.

Back-End (Business Logic & Processing)

🔹 Frameworks & Languages:

Python (Django / FastAPI) or Node.js (Express.js) → Handles API requests & business logic.
Flask → For integrating AI/ML models efficiently.
GraphQL / REST API → For scalable data communication.

🔹 NLP & Machine Learning Models:

BERT / GPT models → For question understanding & response evaluation.
Spacy / NLTK → NLP processing for grading candidate responses.
T5 / OpenAI models → Auto-scoring responses based on similarity analysis.

## Dependencies

AI & NLP Libraries:

OpenAI API / Hugging Face Transformers
Google Cloud NLP
SpaCy / NLTK

🔹 Video Conferencing:

WebRTC / Zoom API / Jitsi Meet

🔹 Speech-to-Text (for interview recording analysis):

Google Speech-to-Text API
AWS Transcribe

🔹 Reporting & Analytics:

Power BI / Tableau
Matplotlib / Seaborn (for data visualization)
