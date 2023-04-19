---
title: "Which is better: Bing, Bard or ChatGPT?"
date: 2023-04-19T13:13:22-07:00
draft: false

categories: [Real_Estate]
tags: [ChatGPT, Bing, Bard, Agent]
toc: false
featuredImage: "/images/Three_robots.png"
author: "Lloyd Tripp"
# Add og:image 
images: ["/images/Three_robots.png"]
---
# Hint: It is not what you expect!

Google recently released a preview version of its chatbot competitor to ChatGPT called **Bard**. Google has invested heavily in Artificial Intelligence and publishes significant research in this field of computer science, so the expectations for its chatbot were high.  
I performed a head-to-head competition between Microsoft's Bing chatbot, OpenAI's ChatGPT and Bard using a fairly complex prompt template to generate a cold call message that real estate agents frequently send out to potential customers. Let's see how well they performed.  

Here is the prompt template with the substitutions:  

>I am a real estate agent, {{firstname}} {{lastname}}. My phone number is {{phone_number}}. My email is {{email_address}}. My company name is {{company}}. Write a short cold-call note that I can mail to homeowners in {{target_area_name}} to persuade them call me or contact me using email. I have sold {{dollar_amt}} of homes in the area in the last 12 months. I know the area very well. I provide great customer service. The value of their home may have gone up enough to convince them to sell.  
>Use a {{tone_name}} tone. Target audience is {{target_type}}. Language is {{language_name}}.  
>The signature line should include my name, company name, phone number and email address.  
>{{firstname}}="Jane",  
>{{lastname}}="Doe",  
>{{phone_number}}="555-1212",  
>{{email_address}}="Jdoe@acme.com",  
>{{company}}="Acme Real Estate",  
>{{target_area_name}}="South Main Street",  
>{{dollar_amt}}="$5,000,000",  
>{{tone_name}}="professional",  
>{{target_type}}="retired couple",  
>{{language_name}}="English"

## Bing Chatbot in Creative mode

**Grade: B+**
Bing Chatbot does a perfect job in substituting the actual values for the placeholders. This is a highly significant level of language understanding that makes it possible to create detailed prompt templates with placeholder substitution right out of the box without the need of another application to perform the substitution. Being able to create your own prompt templates and modifying the substitutions greatly simplifies the process of taking advantage of the powerful features of Large Language Models (LLMs).  
The cold call message that it generates is already quite good, but if you want to make adjustments, you have a very good starting point.  
![Bing response](/images/Bing_Creative_cold_call_template.jpeg)

## ChatGPT

**Grade: B**
ChatGPT also flawlessly performed the substitution of the actual values for the placeholders. The Bing Chatbot is a newer version of ChatGPT so it is interesintg to see that this level of language understanding is even present in the earlier version.  
The cold call message that it responds with is also very good. I would try playing with the {{tone_name}} substitution to get some variations and pick the best one.  
![ChatGPT response](/images/ChatGPT_cold_call_template.jpeg)

## Google Bard

**Grade: F**
It is disappointing that Bard was not able to generate any response at all given the same prompt. I did try some simpler template prompts and it performed perfectly so that confirms that it understands the concept of placeholder substitution. Google is still referring to Bard as an "Experiment" so I expect it will get better at this type of prompt.  
![Google Bard response](/images/Google_Bard_cold_call_template.jpeg)