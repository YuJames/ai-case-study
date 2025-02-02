# AI case study on Nanonets

## Overview and Origin
Name of company
* Nanonets

When was the company incorporated?
* 2016
  
Who are the founders of the company?
* Nanonets was cofounded by Sarjoun Skaff and Shubham Bhardwaj.

How did the idea for the company (or project) come about?
* They recognized an opportunity to help companies more efficiently process their data with AI.

How is the company funded? How much funding have they received?
* In 2022 they raised $10 million in series A funding. In 2024 they raised another $29 million in series B funding, bringing the current total to ***$42 million***.

## Business Activities
What specific problem is the company or project trying to solve?
* The norm of relying on manual data entry is slow and error-prone.

Who is the company's intended customer? Is there any information about the market size of this set of customers?
* Any customer that has documents that are repetitively processed manually.
* From [forbes](https://www.forbes.com/sites/davidprosser/2024/03/12/why-enterprises-are-learning-to-love-nanonets-automation/):
> Largely, those customers have been mid-sized businesses, but Nanonets is increasingly attracting larger enterprises too.

What solution does this company offer that their competitors do not or cannot offer? (What is the unfair advantage they utilize?)
* They have a comprehensive platform that (1) gives easy access to both out-the-box and custom models and (2) makes it easy to build processing pipelines.

Which technologies are they currently using, and how are they implementing them? (This may take a little bit of sleuthing&mdash;you may want to search the company’s engineering blog or use sites like Stackshare to find this information.)
* In addition to their blog, I've communicated with Nanonets representatives via email and phone. They leverage a mixture of proprietary and open-source technology. Their backend is mostly python, and they leverage Tensorflow to great extent. Some of their more advanced offerings are powered by generative AI (LLMs) to implement zero-shot learning (ZLS).

## Landscape
What field is the company in?
* They operate in the AI space in general, but have out-the-box solutions for a variety of industries including finance, supply chain, healthcare, legal, and real estate.

What have been the major trends and innovations of this field over the last 5&ndash;10 years?
* Document parsing services have a long history, especially with regards to accounting. However, since the advent of generative AI and LLMs their underlying technology has improved, leading to more advanced capabilities.

What are the other major companies in this field?
* One competitor was Impera, before they were acquired by Figma. Adobe, also the parent company of Figma, has some OCR capabilities. A variety of smaller OCR microservice offerings can be found with a simple online search, one of which being [onlineocr.net](https://www.onlineocr.net/)

## Results
What has been the business impact of this company so far?

What are some of the core metrics that companies in this field use to measure success? How is your company performing based on these metrics?

How is your company performing relative to competitors in the same field?

## Recommendations
If you were to advise the company, what products or services would you suggest they offer? (This could be something that a competitor offers, or use your imagination!)
* They could shift more into the workflow and DAG (directed acyclic graph) direction, from simple (e.g. n8n) to complex (e.g. airflow)

Why do you think that offering this product or service would benefit the company?
* It could bring in a new audience, while still leveraging a significant amount of current technology.

What technologies would this additional product or service utilize?
* Additional integrations with data sources and destinations would be needed to gain market share, including ones with standalone databases. With this shift, considerations for increased bandwidth and throughput would be relevant too.

Why are these technologies appropriate for your solution?
* A significant portion of data pipelines can be represented by ETLs (extract, transform, load). Nanonets would have to build out significantly more on that front, rather than focus on their traditional no-code solution.

## References
* https://www.forbes.com/sites/davidprosser/2024/03/12/why-enterprises-are-learning-to-love-nanonets-automation/
* https://www.businessinsider.in/investment/news/nanonets-an-ai-powered-workflow-automation-startup-just-raised-29-million-with-this-23-slide-pitch-deck/slidelist/108443660.cms
* https://nanonets.com/blog/data-augmentation-how-to-use-deep-learning-when-you-have-limited-data-part-2/
* https://nanonets.com/blog/what-is-retrieval-augmented-generation-rag/
* https://nanonets.com/
* https://www.toolify.ai/ai-news/create-websites-in-minutes-with-ai-art-figma-and-chatgpt-2766654
* https://n8n.io/
* https://airflow.apache.org/
