---
layout: about
title: about
permalink: /
subtitle: Founding NLP engineer @ <a href='https://dashworks.ai'>Dashworks.ai</a> | Summer Scholar, Research Collaborator and Course Facilitator @ <a href='https://www.stanford.edu/'>Stanford University</a>.

profile:
  align: right
  image: profile_avatar.png
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>Stanford University (Current).</p>
    <p>Chennai, India.</p>

news: true # includes a list of news items
selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page
---

<br>
<br>

<img align="left" width="30" height="30" src="assets/img/about_me_icon.png" alt="About Me">
##  [About Me](#about-me)

I'm a founding NLP engineer at <a href='https://dashworks.ai'>Dashworks.ai</a> and an upcoming summer research scholar at Stanford University. Additionally, I'm the course facilitator for Stanford's <a href='https://online.stanford.edu/courses/xcs224u-natural-language-understanding'>XCS224U: Natural Language Understanding</a> class.

Academically, I did my bachelors in Computer Science Engineering from <a href='https://www.annauniv.edu/'> Anna University</a> and I did my AI graduate program at <a href='https://www.stanford.edu/'>Stanford University</a> as an NDO.

On the research front, I've collaborated with (past) Stanford Ph.D students, <a href='https://ashwinparanjape.github.io/'>Ashwin Paranjape</a> on Retriever pre-training and with <a href='https://omarkhattab.com/'>Omar Khattab</a> on optimizing Language Model Programs, <a href='https://github.com/stanfordnlp/dspy'>the DSPy framework</a>. I'm extremely grateful for both of them, and my faculty mentors, Professor Christopher Potts & Professor Matei Zaharia.

<br>
<br>

<img align="left" width="30" height="30" src="assets/img/research_icon.png" title="research icons">
## [Research Directions](#research-directions)

I'm broadly interested in improving ML search & recommendation systems.

  > Why? Long lost are the days when the purpose of search was just to retrieve content. We are in an age where search is being used implicitly to sculpt and mold intelligence in systems.
  
###### As an example, imagine the below cases:

###### `Example 1 (simple)`
- Searching in photos no longer refers to filtering on metadata but identifying the pictures or videos using natural language queries. For instance, using OpenAI's CLIP model, users can search for specific frames in a YouTube video by describing the content in natural language, such as "a fire truck" or "people crossing the street".

###### `Example 2 (medium)`
- Robots are increasingly being equipped with a wide array of tools and operations, necessitating sophisticated search algorithms to identify the correct tool for a given task. This capability is crucial for enabling robots to perform complex and varied tasks autonomously.

###### `Example 3 (hard)`
- AI assistants (or co-pilots) are tasked with solving real-life problems that are new and challenging. These systems often gather, process, and structure information from massive unstructured data to form enough intelligence to solve the task.

I believe there is a significant potential for improvement in the current Search systems that are built in industries. My short-term research direction are more specifically in the following lines:

##### `(More) reliable foundational models`
- The stakes have never been higher. Foundational Models such as OpenAI's GPT and Meta's LLama (to name a couple) are widely being deployed on production grade systems to solve real-world problems. One of the very common use-cases of these industries involve building Retrieval Augmented Generation Systems. We have leap-frogged a decade's worth of time when we moved from BERT to newer foundational models but there are significant challenges in operating these systems reliably at production level. In 2017, a false-negative in model prediction would have wasted a day's worth of humans resource (fictional approximation) but a similer false-negative in the current age has serious consequences. eg: AI job screening, AI agent for Stock market, self-driving cars, and AI assisted parole hearings. Factual accuracy, and consistency are the two key areas I would want to expore in achieving more reliable foundational models for these cases. Popular problems that fall under these areas are Hallucinations, and lost-in-the-middle problem. Commonly, there are two ways in handling this: i) engineer models inputs to reduce such factors, and ii) build models from ground-up that are less prone to these factors. I would want to focus on the latter.

##### `Better Retrievers & Rankers`
- Surprisingly, unlike foundational models we haven't yet achieved the decade's worth leapfrog with Retrievers & Rankers. Until we research the utopia of no-loss infinite context length foundational models, we have to depend on retrievers and rankers to improve the quality of information that is fed to foundational models for generation. There are too many optimizations that can be explored in this area such as long-context RRs (Retrievers & Rankers), Metadata aware RRs, and Instruction following RRs. I would love to solve these problems in the near future.

##### `Better Adaptability of foundational models`
- Foundational models hold abundant of knowledge within them and the best way to make use of them is to guide them appropriately. The common guides are i) prompting (such as instructions & few-shot examples), and ii) Fine-tuning. Although (i) is more commonly employed than (ii), the latter is less brittle and more effective compared to the prompting. Eventhough Fine-tuning is much easier to accomplish (obviously, with money and resource) now, there are unsurprisingly many challenges that are yet to be tackeled. A couple of them are (i) fine-tuned models are more prone to hallucinations, and (ii) efficient way to update knowledge. This is a very interesting direction since it is mostly open-ended. I would love to keep-up with this area.

##### `Multi-modal search`
- Why not? This is the future..