# Evaluating Political Bias in Popular Generative LLMs
Itzhak Estrella and Alexander Parks

## About
As the popularity of publicly available generative models increases, people have begun to use them as a primary source of information. Generative models are increasingly providing people with primary information regarding their finances, careers, hobbies, politics, and more. However, the majority of people are unaware that these generative models can provide misinformation through hallucinated or purely incorrect responses, as demonstrated in Wang et al.'s recent survey on the factuality of large language model responses (2024). In light of this trend and the recent U.S. presidential election, our project aims to determine if certain, popular, open-source generative models demonstrate preference or bias toward certain U.S. political parties. By examining the difference in sentiment of text generated on identical prompts for each party, we can determine which models, if any, are biased towards certain parties, ideologies, etc. Research concerning political bias in generative models is important as people rely more on these models as primary sources of information; even if the models are biased, it is important for users to be aware of this bias as they interact with the models’ outputs. Our research aims to answer two central questions:
- Compared to a baseline difference in sentiment between “conservative” and “liberal” prefixes, do any of the selected models display a difference in sentiment between “conservative” and “liberal” generated suffixes?
- How has the average disparity in sentiment by major U.S. political party changed in the selected models over time?

## Files
- `requirements.txt`: Text file that contains the necessary package requirements to run the code in the Jupyter notebooks
- `news_article_links.txt`: Text file that contains the news article links that were scraped to get raw sentences
- `dataset_construction.ipynb`: A Jupyter notebook for constructing our dataset
- `model_comparison_huggingface`: A Jupyter notebook for performing the analysis on models via Hugging Face
- `model_comparison_openai`: A Jupyter notebook for performing the analysis on models via OpenAI API
- `base_data.tsv`: Tab-separated dataset for moving data between `dataset_construction.ipynb` and the model comparison notebooks
- `openai-gpt_results.tsv`: Tab-separated dataset for the results from GPT
- `gpt2_results.tsv`: Tab-separated dataset for the results from GPT-2
- `gpt3.5_results.tsv`: Tab-separated dataset for the results from GPT-3.5
- `gpt4o_results.tsv`: Tab-separated dataset for the results from GPT-4o

## Presentation
A link to the presentation for this project: https://docs.google.com/presentation/d/1IeHI58Z_AwG6YorfSa4CC8fkCO3MPJvb/edit?usp=sharing&ouid=103907116625322886779&rtpof=true&sd=true

## Report
A link to the report for this project: https://docs.google.com/document/d/1QN8RP46c3gB025_IfEbmTBdOO33oGJp1HCWsl7wLO3Y/edit?usp=sharing 
