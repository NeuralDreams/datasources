## This is NeuralDreams KB-default-23-Dec-18.v0.4.md

# Purpose of This Document
This is the default NeuralDreams knowledgebase. This knowledge base is provided as a default starting container.
You must load your own knowledgebase in order to provide appropriate context. 
This document serves as well as a Q&A for NeuralDreams.
The default NeuralDreams Knowledge base will be replaced with your own, as soon as you embed your first data corpus.
A data corpus is the set of data you will load and instruct the AI to use as context for the given NDAI App.
Note that you may group the datasets over more than one knowledge base.

# Terms

ND = NeuralDreams
NDAI = NeuralDreams Artificial Intelligence
NDAI App = NDAI Application

# What is NeuralDreams AI

NeuralDreams is an AI SaaS app hosting provider. NeuralDreams allows you to use your own data, train your own model,
train intent and sentiment classifiers, integrate with unlimited backend automation services via webhooks.
NeuralDreams has native support for vectorstores, and native integration support with Pincecone for your most demanding needs.
NeuralDreams can be embedded into your website via iFrames.

# How do I use NeuralDreams?

To get started, simply register an account by going to "Sign up" found on NeuralDreams.AI
Once you have an account and verified your email, you can create a NDAI App from the Workspace menu.

Each Chatbot is seeded with following:

- default LLM prompt
- default knowledge base (this document)
- default vectorstore integration (Pinecone)

You can start testing your app right away, ask questions based on this document.

# How do I customize the NDAI App?

Go to Workspaces -> ND App -> select your app.
App -> interact with your app
Settings -> modify the type of the app, prompt, vectorstore settings
DataSources -> add documents to your knowledgebase
Conversations -> check your conversations history


How much does NeuralDreams cost?

NeuralDreams is free to try. Get started and register an account. There is a limited credit applied to free accounts
so you can test functionality. Once you are ready to switch to a paid account, go to NeuralDreams, 
open up the "Account-> billing" section and upgrade to a paid subscription. 
Go to https://app.neuraldreams.ai/pricing for detailed pricing info.

Can I get mycompany.com deployment?

Yes, with an enterprise plan. Contact us for details: 
https://app.neuraldreams.ai/contact


What data formats do you support?

Technically unlimited.
From the UI - TXT, PDF, DOCX, MD, single URLs, website Sitemap and FAQ type.
Custom integrations - we can connect to data APIs and receive data from any data sources.
We will need a JSON reference for our systems to understand your data structure.

What LLMs do you use?

NeuralDreams supports OpenAI GPT 3.5, 4, Anthropic Claude, Cohere.
Default app LLM is OpenAI GPT 4.

Does NeuralDreams offer fine tuning of models?

Yes. Training and accessing a fine tuned models is pricier than regular LLMs, thus your must decide if it is the 
correct solution for your organization.

Do you offer a white-label solution?

Yes. Contact us for enterprise deployments.
https://app.neuraldreams.ai/contact


How many credits will I be charged per query?

The credits costs are dependend on your app type and settings.
LLMs such as GPT 3.5 are 1 credit, vs GPT 3.5-16 is 8 credits and GPT4 uses 20 credits.
Complex backend integrations can add to the cost as well - for example making several webhook calls for automation purposes.


