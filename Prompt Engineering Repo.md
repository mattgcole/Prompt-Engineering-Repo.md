**Self-reflection prompt:**

You are writing a self-reflection on your performance for the past period. Here are your monthly notes:
"""
<paste monthly notes>
"""
 
Based on your monthly notes, answers these questions:
 
1. What progress have you made in this review period? Describe the impact on the success of your team, project, practice/department and/or Credera.
2. Reflecting on the period, please provide examples of how you have actively addressed growth areas identified in your projectbased feedback, year end CPM, or any other feedback you have received. How have you applied the feedback to improve your performance and contribute to the success of your team? For context, here is previous feedback you have received:
 
"""
<paste previous feedback>
"""
 
Let the data and notes speak for themselves. Do not embellish.
 
If you do not have enough information to answer a question of part of it, respond with "I do not have enough information to answer this part of the question".
 
**Snapshot prompt:**

You are a manager, writing a performance review. Take the Self-Reflection on Performance and answer these questions:
 
1. List the role(s) (i.e., project, internal, etc.) that this team member played during this review period.
2. During this review period, what are 1-2 of this person's most impactful accomplishments?
 
Let the data and notes speak for themselves. Do not embellish.
 
If you do not have enough information to answer a question of part of it, respond with "I do not have enough information to answer this part of the question".
 
Here is the self-reflection:
"""
<paste self-reflection>
"""
**Additional feedback prompt:**

Here is additional feedback. You should only respond with "Feedback has been added to context". I will later prompt you to provide an updated summary with all the additional feedback.
 
Here is the feedback:
"""
<paste additional feedback>
"""
 
_Note: If you add multiple additional feedback, you'll get a response "Feedback has been added to context" each time. After you are done adding additional feedback, ask the questions again to get an updated summary._

**Step-Back Prompting**

Here is a question or task: {{Question}}
Let's think step-by-step to answer this:

Step 1) Abstract the key concepts and principles relevant to this question:

Step 2) Use the abstractions to reason through the question:
Final Answer:

**Chain of Verification Prompting**

Here is the question: {{Question}}.

First, generate a response.

Then, create and answer verification questions based on this response to check for accuracy. Think it through and make sure you are extremely accurate based on the question asked.

After answering each verification question, consider these answers and revise the initial response to formulate a final, verified answer. Ensure the final response reflects the accuracy and findings from the verification process.

**Debugging code**

I want you to be a {Coding Language Type} programmer, here is a piece of {Coding Language} code containing {problem} — {insert code snippet} — I am getting the following error {insert error}. What is the reason for the bug?

**Code explanation**

I want you to act as a code explainer in {Coding Language}. I don't understand this function. Can you please explain what it does, and provide an example? {Insert function}

**Code optimization**

I want you to act as a code optimizer in {Coding Language}. {Describe problem with current code, if possible}. Can you make the code {more Pythonic/cleaner/more efficient/run faster/more readable}? {Insert Code}

**Code translation**

I want you to act as a programmer in {Coding Language}.  Please translate this code to {Coding Language}. {Insert code}

**Compare function speeds**

I want you to act as a Python programmer.  Can you write code that compares the speed of two functions {functionname} and {functionname}? {Insert functions}

**Generate Markdown**

I want you to act as a data generator. Can you generate a Markdown file that contains {data requirement}. Save the file to {filename}

**Feature engineering ideation**

I want you to act as a data scientist. Given a dataset of {dataset name} that contains the {columns}, you are to predict {predicted variable}. Suggest data that will be helpful for this problem and perform feature engineering for this problem.

**Model training workflow**

I want you to act as a data scientist programming in Python. Given a dataset of {dataframe name} that contains the {column name}, write code to predict {output variable}.

**Hyperparameter tuning workflow**

I want you to act as a data scientist programming in Python. Given a {type of model} model, write code to tune the hyperparameter.

**Model explainability workflow**

I want you to act as a data scientist programming in Python. Given a {type of model} that predicts the {predictor variable}, write code that explains an output using Shap values.

**Text dataset generation**

I want you to act as a dataset generator. Please generate {number of text} texts on {required text and the context}. {Insert additional requirements}.

**Explain data concepts for business executives**

I want you to act as a data scientist of a corporate company. {Describe content in detail, if required} Please explain to a business executive what {concept} means.

**Summarize article/paper**

I want you to act as a data scientist in a research start-up. Please explain the paper {paper} to a {level of difficulty, e.g. software developer, five-year-old, business executive, professor}.

**Write tutorials to understand data topics**

I want you to act as a data scientist writer. Please write the {number-of-words}-word introduction to a tutorial on {title}. {Insert relevant key points}.

**Analyze Market Trends**

Act as a seasoned market researcher. Your task is to analyze the feasibility of a [product]. This includes conducting comprehensive market research to determine the product's potential success in the current market. Evaluate the demand for the product, potential customer base, and market trends. Determine the product's potential profitability, considering factors like production costs, pricing strategy, and competitive landscape. Conduct a SWOT analysis to identify strengths, weaknesses, opportunities, and threats. Compile your findings into a detailed report with clear conclusions and actionable recommendations.

**Analyze Potential Audience**

As a seasoned audience researcher, your task is to analyze the potential audience for a [product]. You will conduct thorough market research to identify key demographics, their behaviors, needs, and interests. This will include both quantitative and qualitative analysis, leveraging data from various sources. Identify potential market segments, their size, and their potential value. Create an in-depth report outlining your findings, including an overview of the potential audience, their key characteristics, and recommendations for targeting them effectively. The report should be comprehensive and easy to understand, providing actionable insights that can drive marketing and sales strategies.
