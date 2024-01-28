# LangChain-News-Article-Summarizer

## Introduction
In today's fast-paced world, it's essential to stay updated with the latest news and information. However, going through multiple news articles can be time-consuming. To help you save time and get a quick overview of the important points, let’s develop a News Articles Summarizer application using ChatGPT and LangChain. With this powerful tool, we can scrape online articles, extract their titles and text, and generate concise summaries. Within this lesson, we will walk you through the workflow of constructing a summarizer. We will employ the concepts we discussed in earlier lessons, demonstrating their application in a real-world scenario.

## Workflow for Building a News Articles Summarizer
Here’s what we are going to do in this project.



And here are the steps described in more detail:

- Install required libraries: To get started, ensure you have the necessary libraries installed: requests, newspaper3k, and langchain.
- Scrape articles: Use the requests library to scrape the content of the target news articles from their respective URLs.
- Extract titles and text: Employ the newspaper library to parse the scraped HTML and extract the titles and text of the articles.
- Preprocess the text: Clean and preprocess the extracted texts to make them suitable for input to ChatGPT.
- Generate summaries: Utilize ChatGPT to summarize the extracted articles' text concisely.
- Output the results: Present the summaries along with the original titles, allowing users to grasp the main points of each article quickly.

By following this workflow, you can create an efficient News Articles Summarizer that leverages ChatGPT to provide valuable insights in a time-saving manner. Stay informed without spending hours reading through lengthy articles, and enjoy the benefits of AI-powered summarization.

Before you start, obtain your OpenAI API key from the OpenAI website. You need to have an account and be granted access to the API. After logging in, navigate to the API keys section and copy your API key.

Remember to install the required packages with the following command: pip install langchain deeplake openai tiktoken. Additionally, the install the newspaper3k package, which has been tested in this lesson with the version 0.2.8.

```
!pip install -q newspaper3k python-dotenv
```

