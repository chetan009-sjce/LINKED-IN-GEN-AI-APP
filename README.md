# LINKED-IN-GEN-AI-APP
It is an LLM powered application developed with Langchain.
This is a web application crawling Linkedin data about a person across web, customizes the info fetched with the help of LLM model and generates a summary, 2 of the interesting facts, 2 most relevant questions and his topics of interest based on the data available from his/her linked in profile.
To run this project, you will need to add the following environment variables to your .env file

`OPENAI_API_KEY`

`SCRAPIN_API_KEY` 

`TAVILY_API_KEY`

`LANGCHAIN_TRACING_V2`  

`LANGCHAIN_API_KEY` 

`LANGCHAIN_PROJECT` 


To run this project, you will need to add the following environment variables to your .env file:

> **Note**: This project uses paid API services:
> - [Scrapin.io](https://www.scrapin.io/?utm_campaign=influencer&utm_source=github&utm_medium=social&utm_content=edenmarco) for LinkedIn data scraping (20% discount available through this link, includes 20 free credits to start)


> **Important Note**: If you enable tracing by setting `LANGCHAIN_TRACING_V2=true`, you must have a valid LangSmith API key set in `LANGCHAIN_API_KEY`. Without a valid API key, the application will throw an error. If you don't need tracing, simply remove or comment out these environment variables.
## Run Locally

Clone the project

```bash
  git clone https://github.com/emarco177/ice_breaker.git
```

Go to the project directory

```bash
  cd ice_breaker
```

Install dependencies

```bash
  pipenv install
```

Start the flask server

```bash
  pipenv run app.py
```


