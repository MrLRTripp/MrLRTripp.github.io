---
title: "ChatGPT Needs Prompt Engineering"
date: 2023-02-26T13:49:06-08:00
draft: false

categories: [Real_Estate]
tags: [ChatGPT, Agent]
toc: false
featuredImage: "/images/looking_robot.png"
author: "Lloyd Tripp"
# Add og:image 
images: ["/images/looking_robot.png"]
---
# A good response requires a good prompt  
The term "Prompt Engineer" is starting to pop up as a person that crafts prompts for ChatGPT and other AI assistants. "But wait a minute," you say, "wasn't the AI assistant supposed to make it easy for everyone to take advantage of its superior language capabilities?" "Now I'm supposed to engineer prompts?" Well, yes and no. There are two basic approaches that I have used to get the AI assistant to generate the desired response: 1. Iterative refinement using simple prompts, and 2. start with detailed prompt.  

# Iterative refinement using simple prompts
The AI assistant responds to the prompts that are provided. If the prompt is lacking in detail, it will do its best to come up with the best response based on the information provided and the vast amount of textual sources used to train it. This may be perfectly fine if you are exploring the range of responses that it can generate. However, if you are aiming for a particular **level of detail, format, tone or length**, then you will likely have to provide additional prompts to refine the response. One of the many fantastic features of Large Language Model (LLM) AI assistants is that they can remember the context of the previous prompts and responses. This makes iterative refinement using simple prompts possible.   

Note: The preview version of Microsoft Bing currently limits the number of turns in one session to 6. They discovered that is starts generating strange responses as the number of turns exceed 6. They are working to increase the number of turns / session.  

Let's see an example using Bing to iteratively create a thank-you note to a customer. I used 5 prompts to create the final note:  
1. Write a thank-you note to my customer.
2. My customer's name is "Mr. Tripp"
3. He just bought a new house.
4. My name is Ms. Doe and my business address is "A1 Realtor, 123 Main, Anywhere, CA"
5. Mr. Tripp has a family with a wife, Jane, 2 kids and a German Shepherd dog.  

Notice how the responses transition from generic to highly personal.


![iterative prompts](/images/iterative.gif)


# Start with detailed prompt
The iterative approach gets the job done, but it wastes time to take such small steps if you have a good idea about the result you are trying to achieve. It is much better to start with a prompt that has as much detail as you want to add to the final response. You can always make minor adjustments with additional prompts or make them manually.  

Let's take the above example and perform it in one prompt:  
I'm a real estate agent, Ms. Doe, and my business address is "A1 Realtor, 123 Main, Anywhere, CA." Write a thank-you note to my customer, "Mr. Tripp." He just bought a new house from me on 2/27/2023. Mr. Tripp has a family with a wife, Jane, 2 kids and a German Shepherd dog. Include my business name and address below the signature.

Notice the level of detail in the response.

![detailed prompt and response](/images/detailed_prompt_and_response.jpeg)

# Wait. I could have done that myself.
Sure, this was a simple example to illustrate the high-quality output that can be generated as long as details are provided in the prompt(s). But could you have written the note in Spanish or any of the **100 languages Bing understands**?  

We'll explore the topic of **translation in an upcoming post**.

