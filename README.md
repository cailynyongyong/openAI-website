## Introduction

This is an openAI generated tool to integrate onto websites so that it can answer any questions about your site.
The code is referenced from OpenAI's tutorial on Website Q&A with Embeddings. [link](https://platform.openai.com/docs/tutorials/web-qa-embeddings).
When scraping the contents of a website, OpenAI's current tool doesn't work on sites that use dynamic Javascript content, so I used selenium to load the contents first and then retrieve the text using Beautiful Soup.

Ask questions by calling the function:

```javascript I'm A tab
answer_question(df, (question = "Who is talking about ETH Tokyo?"));
```
