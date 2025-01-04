---
title: Home
---

# Workshop Template!

{% include figure.html img="aaai-fidu-banner.jpg" alt="banner" caption="" width="75%" %}

Financial inclusion remains a critical global challenge, with complex financial documents often serving as a significant barrier to accessing and understanding financial services. While recent advances in Large Language Models (LLMs) have shown promising capabilities in document understanding, summarization, and financial education, implementing these solutions presents various challenges. These include handling diverse data formats, designing effective prompts, ensuring accuracy in simplified responses, and adapting explanations for different user backgrounds. Additionally, there’s a growing need for solutions that can democratize financial knowledge and empower individuals to make informed financial decisions, particularly among underserved populations.

This hands-on tutorial addresses these challenges by presenting a comprehensive framework for AI-driven financial document understanding. Participants will learn to develop solutions using Retrieval-Augmented Generation (RAG) and knowledge graphs, implemented via an open-source tech stack including Phidata, Weaviate, and Llama3.1. The tutorial is structured to provide both theoretical foundations and extensive practical implementation experience. Key topics include document summarization techniques, concept simplification strategies, and methods for creating personalized explanations tailored to users’ backgrounds. Through hands-on demonstrations, participants will build use cases for financial document comprehension, develop educational tools, and gain insights into creating human-interactable platforms for deploying these methods effectively. The session combines presentations with guided coding exercises and interactive building sessions, ensuring participants gain practical experience with implementing these solutions.

This tutorial is designed for a diverse audience, including financial institutions aiming to serve underserved populations, fintech professionals developing innovative products, policymakers focused on inclusion initiatives, and AI researchers working on document understanding. By bridging the gap between complex financial documents and user comprehension, participants will gain practical skills to enhance financial inclusion through AI-powered solutions. The tutorial emphasizes accessible, open-source solutions to ensure participants can continue developing and implementing these tools after the session. Participants should have basic Python programming knowledge and bring a laptop with internet connectivity; all necessary resources and code will be provided prior to the conference. Through this comprehensive training, attendees will be equipped to contribute to the broader goal of enhancing financial inclusion through innovative AI-powered solutions.

<div class="toc" markdown="1">
## Contents:

{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | relative_url }}){% endif %}
{% endfor %}
</div>

Hosted by [University of Idaho Library](http://www.lib.uidaho.edu/), {{ site.pub_year }}.
 
> built using [Jekyll](https://jekyllrb.com/) and [GitHub Pages](https://pages.github.com/)
>
> images and content: cc-by-sa <a href="https://github.com/{{ site.github_username }}">{{ site.author }}</a> {{ site.pub_year}} (get [source code]({{ site.repo }})).
> Last build date: {{ site.time | date: "%Y-%m-%d" }}.
>
> <a href="http://creativecommons.org/licenses/by-sa/4.0/" rel="license"><img style="border-width: 0;" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" alt="Creative Commons License" /></a>
