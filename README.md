# Case Study: GitHub Copilot

## Overview and Origin

* **Name of company:** GitHub (in conjunction with OpenAI)
* **When was the company incorporated?:** GitHub was incorporated in 2008<sup>[1](#wikipedia-github)</sup>, OpenAI 2015<sup>[2](#wikipedia-openai)</sup>
* **Who are the founders of the company?:**
    * **Github** - Tom Preston-Werner, Chris Wanstrath, P. J. Hyett, and Scott Chacon<sup>[1](#wikipedia-github)</sup>
    * **OpenAI** - Sam Altman, Elon Musk, Ilya Sutskever, Greg Brockman, Trevor Blackwell, Vicki Cheung, Andrej Karpathy, Durk Kingma, John Schulman, Pamela Vagata, and Wojciech Zaremba<sup>[2](#wikipedia-openai)</sup>
*	**How did the idea for the company (or project) come about?:** The idea for GitHub Copilot originated from the need to enhance developer productivity and reduce the cognitive load of writing code.<sup>[3](#github-copilot-research)</sup>  GitHub and OpenAI collaborated to create a tool using the power of OpenAI's artificial intelligence models.
* **How is the company funded? How much funding have they received?:**
    * **Github** - GitHub was acquired by Microsoft in 2018 for $7.5 billion.  It makes money from it's paid Team and Enterprise accounts[4](#github-pricing).  It was a startup that received venture capital through Andreessen Horowitz, Sequoia Capital,Thrive Capital, IVP (Institutional Venture Partners) and other venture capital funds[1](#wikipedia-github).
    * **OpenAI** - OpenAI, has received significant funding, including $1 billion from Microsoft<sup>[2](#wikipedia-openai)</sup>.

      >"The majority of the company’s revenue comes from licensing fees for its AI models and products. It prices access to its language models and ChatGPT based on the use of tokens, which provide access to a specific number of generated words."<sup>[5](#techo-openai-pricing)</sup>
    


## Business Activities

* **What specific problem is the company or project trying to solve?:** 
GitHub Copilot aims to solve the problem of time-consuming and error-prone code writing by providing AI-driven code suggestions while improving developer efficiency and code quality <sup>[3](#github-copilot-research)</sup>.
* **Who is the company’s intended customer? Is there any information about the market size of this set of customers?:** The intended customers are software developers and engineers. The global software development market is vast, with millions of developers worldwide and a market size expected to reach $781.47 billion by 2026 <sup>[6](#statistica-software-ww)</sup>.
* **What solution does this company offer that their competitors do not or cannot offer? (What is the unfair advantage they utilize?):** GitHub Copilot offers real-time, context-aware code suggestions, which is trained on a vast corpus of code and natural language data<sup>[8](#github-better-model)</sup>. This integration within popular code editors like Visual Studio Code gives it a competitive edge over other code completion tools.
* **Which technologies are they currently using, and how are they implementing them?:** GitHub Copilot utilizes OpenAI’s Codex, a descendant of the GPT-3 model<sup>[9](#openai-codex)</sup>.  The enterpise price level supports GPT-4o<sup>[12](#updated-components-enterprise)</sup>. They've also added enhanced context filtering<sup>[7](#github-goes-beyond-codex)</sup>. It integrates seamlessly with Visual Studio Code, JetBrains, and other IDEs.  It leverages machine learning to provide contextually relevant code suggestions based on the code being written by the developer.

## Landscape

* **What field is the company in?:** GitHub Copilot is in the field of software development tools, specifically focusing on AI-driven code assistance.
* **What have been the major trends and innovations of this field over the last 5–10 years?:** Major trends include the rise of AI and machine learning in software development, the increasing popularity of integrated development environments (IDEs), and the shift towards automation and intelligent code completion tools.
* **What are the other major companies in this field?:** Other major companies include Microsoft (Visual Studio IntelliCode), JetBrains (ReSharper), and TabNine.  It is also competing with other AI assistants like Claude that might not provide direct IDE integration.

## Results

* **What has been the business impact of this company so far?:** GitHub Copilot has significantly improved developer productivity.
  > "Users report that GitHub Copilot has contributed to faster coding, with time savings of up to 30% and an average weekly time gain of 1 to 5 hours. These efficiency improvements signal Copilot's potential for scaling up productivity across teams over time."<sup>[10](#copilot-soaring-or-stalling)</sup>

  It has also enhanced code quality and increased developer satisfaction.
* **What are some of the core metrics that companies in this field use to measure success? How is your company performing based on these metrics?:** Core metrics include developer productivity, code quality, adoption rate, and user satisfaction. GitHub Copilot has performed well in these areas, showing substantial improvements in productivity and code quality, and high levels of developer satisfaction<sup>[3](#github-copilot-research)</sup>. 
* **How is your company performing relative to competitors in the same field?:** GitHub Copilot is considered a leading tool in its field due to its advanced AI capabilities, strong integration with popular IDEs, and the extensive training data backing its suggestions.

## Recommendations

* **If you were to advise the company, what products or services would you suggest they offer?:** I would suggest offering advanced customization options for Copilot, allowing developers to tailor the AI’s suggestions based on their coding style and project requirements. Additionally, expanding Copilot’s capabilities to better support more programming languages and frameworks would be beneficial. Currently Copilot works best with Python, JavaScript, TypeScript, Ruby, Go, C# and C++ <sup>[11](#code-suggestions-in-ide)</sup>. 
* **Why do you think that offering this product or service would benefit the company?:** Providing advanced customization options would enhance user satisfaction and make Copilot more versatile across different coding environments and styles. Expanding language support would broaden its user base, attracting more developers to the platform.
* **What technologies would this additional product or service utilize?:** These enhancements would utilize machine learning algorithms for customization, natural language processing for understanding different programming languages, and possibly reinforcement learning to adapt to user preferences over time.
* **Why are these technologies appropriate for your solution?:** Machine learning and natural language processing are central to providing intelligent code suggestions, while reinforcement learning would help in creating a more personalized and adaptive AI assistant, thereby improving user experience and satisfaction.

# References
<a name="wikipedia-github">1</a>: GitHub. (2024, July 9). In *Wikipedia*<br /> [https://en.wikipedia.org/w/index.php?title=GitHub&oldid=1233573446](https://en.wikipedia.org/w/index.php?title=GitHub&oldid=1233573446)

<a name="wikipedia-openai">2</a>: OpenAI. (2024, July 13). In *Wikipedia*<br />
[https://en.wikipedia.org/w/index.php?title=OpenAI&oldid=1234208676](https://en.wikipedia.org/w/index.php?title=OpenAI&oldid=1234208676)

<a name="github-copilot-research">3</a>: Kalliamvakou, E. (2022, September 7). *Research: quantifying GitHub Copilot’s impact on developer productivity and happiness*<br />
[https://github.blog/2022-09-07-research-quantifying-github-copilots-impact-on-developer-productivity-and-happiness/](https://github.blog/2022-09-07-research-quantifying-github-copilots-impact-on-developer-productivity-and-happiness/)

<a name="github-pricing">4</a>: Github. (2024, 7 16). *Pricing - Plans for Every Developer*<br />
[https://github.com/pricing](https://github.com/pricing)

<a name="techo-openai-pricing">5</a>: Willing, N. (2024, July 16). *Techopedia: How Does OpenAI Make Money? Revenue Model Explained*<br />
[https://www.techopedia.com/how-does-openai-make-money](https://www.techopedia.com/how-does-openai-make-money)

<a name="statistica-software-ww">6</a>: Statistica. (2024, July 16). *Software - Worldwide Statistics Forecast*<br />
[https://www.statista.com/outlook/tmo/software/worldwide](https://www.statista.com/outlook/tmo/software/worldwide)

<a name="github-goes-beyond-codex">7</a>: Zhao, S. (2023, July 28). *Smarter, more efficient coding: GitHub Copilot goes beyond Codex with improved AI model*<br />
[https://github.blog/2023-07-28-smarter-more-efficient-coding-github-copilot-goes-beyond-codex-with-improved-ai-model/](https://github.blog/2023-07-28-smarter-more-efficient-coding-github-copilot-goes-beyond-codex-with-improved-ai-model/)

<a name="github-better-model">8</a>: Zhao, S. (2023, February 13). *GitHub Copilot now has a better AI model and new capabilities*<br />
[https://github.blog/2023-07-28-smarter-more-efficient-coding-github-copilot-goes-beyond-codex-with-improved-ai-model/](https://github.blog/2023-07-28-smarter-more-efficient-coding-github-copilot-goes-beyond-codex-with-improved-ai-model/)

<a name="openai-codex">9</a>: OpenAI. (2024, July 16). *OpenAI Codex*<br />
[https://openai.com/index/openai-codex/](https://openai.com/index/openai-codex/)

<a name="copilot-soaring-or-stalling">10</a>: Rakers, R. (2024, June 20). *GitHub Copilot: Soaring or Stalling in Software Development?*<br />
[https://www.linkedin.com/pulse/github-copilot-soaring-stalling-software-development-remco-rakers-dub9e/](https://www.linkedin.com/pulse/github-copilot-soaring-stalling-software-development-remco-rakers-dub9e/)

<a name="code-suggestions-in-ide">11</a>: Github. (2024, July 17). *Getting code suggestions in your IDE with GitHub Copilot*<br />
[https://docs.github.com/en/copilot/using-github-copilot/getting-code-suggestions-in-your-ide-with-github-copilot](https://docs.github.com/en/copilot/using-github-copilot/getting-code-suggestions-in-your-ide-with-github-copilot)

<a name="updated-components-enterprise">12</a>: Github. (2024, July 3). *Updated Components to Enterprise Licensing*<br />
[https://github.blog/changelog/2024-07-05-github-copilot-enterprise-on-gpt-4o/](https://github.blog/changelog/2024-07-05-github-copilot-enterprise-on-gpt-4o/)