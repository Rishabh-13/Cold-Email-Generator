# 📧 Cold Mail Generator
Cold email generator for services company using groq, langchain and streamlit. It allows users to input the URL of a company's careers page. The tool then extracts job listings from that page and generates personalized cold emails. These emails include relevant portfolio links sourced from a vector database, based on the specific job descriptions. 

**Imagine a scenario:**

- Meta needs a Software Engineer in Machine Learning and is spending time and resources in the hiring process, on boarding, training etc
- Kapsun Overseas is Software Development company can provide a dedicated software development engineer to Meta. So, the business development executive (Rishabh Gupta) from Kapsun Overseas is going to reach out to Meta via a cold email.

![img.jpg](imgs/img.jpg)

## Architecture Diagram
![img.png](imgs/architecture.png)

## Set-up
1. To get started we first need to get an API_KEY from here: https://console.groq.com/keys. Inside `app/.env` update the value of `GROQ_API_KEY` with the API_KEY you created. 


2. To get started, first install the dependencies using:
    ```commandline
     pip install -r requirements.txt
    ```
   
3. Run the streamlit app:
   ```commandline
   streamlit run app/main.py
   ```
   
