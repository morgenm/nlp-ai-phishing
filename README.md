# Detecting Phishing Emails with NLP and AI
This repository corresponds to a [blog post](https://morgenm.github.io/blog/2023/phishing-detection-ai/) I wrote. The post gives explanation behind the choices I made while writing this code. This code trains models to detect phishing emails based on the body text of the emails. I do not plan on maintaining this code; I uploaded it so that others could see and understand my process, and reproduce it if they wish. However, if anyone needs any further explanations, or notices any egregious errors or mistakes, you can open an issue or PR and I will try to address it. I apologize for the messy code. I was writing it for functionality, not maintainability.

This code requires various datasets to run. The datasets I used were placed in `../datasets/`. The list of datasets I used is listed on my blog post. 

## Spam wordlist
The spam wordlist was created based on two sites: [here](https://www.activecampaign.com/blog/spam-words) and [here](https://blog.hubspot.com/blog/tabid/6307/bid/30684/The-Ultimate-List-of-Email-SPAM-Trigger-Words.aspx)