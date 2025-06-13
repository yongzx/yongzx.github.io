---
layout: about
title: about
permalink: /
subtitle: <span style='color:grey'>Current&#58; Computer Science Ph.D. @ Brown University<br>Past&#58; Research Scientist Intern @ <a href='https://ai.meta.com/' style='color:#222222'>Meta AI</a>, Research Collaborator @ <a href='https://cohere.com/research' style='color:#222222'>Cohere Labs</a></span>

profile:
  align: right
  image: prof_pic.jpg
  image_circular: true # crops the image to make it circular
  more_info: 

news: true # includes a list of news items
selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page
misc: true # includes miscellaneous content
---

<style type="text/css">
 .tab { margin-left: 30px; }
 .research-grid {
   display: grid;
   grid-template-columns: 1fr 1fr;
   gap: 20px;
   margin: 20px 0;
 }
 .research-box {
   padding: 20px;
   border-radius: 8px;
   background-color: #ffffff;
   box-shadow: 0 2px 4px rgba(0,0,0,0.1);
 }
 .box-1 { border: 3px solid #a8c6e5; }  /* muted blue */
 .box-2 { border: 3px solid #e5a8a8; }  /* muted red */
 .box-3 { border: 3px solid #a8e5a8; }  /* muted green */
 .box-4 { border: 3px solid #e5e5a8; }  /* muted yellow */

 @media screen and (max-width: 768px) {
   .research-grid {
     grid-template-columns: 1fr;
   }
   .research-box {
     margin-bottom: 15px;
   }
 }
</style>


I am a fourth-year Ph.D. student in Computer Science at Brown University, advised by [Prof. Stephen Bach](https://scholar.google.com/citations?user=hs6pGXoAAAAJ&hl=en). I am fortunate to have worked with researchers at <u>Meta GenAI</u> (with [Jianfeng Chi](https://jfchi.github.io/)), <u>Meta AI FAIR</u> (with [Jean Maillard](https://maillard.it/) and [Michael Auli](https://michaelauli.github.io/)), and <u>Cohere Labs</u> (with [Julia Kreutzer](https://juliakreutzer.github.io/), [Beyza Ermis](https://scholar.google.com/citations?user=v2cMiCAAAAAJ&hl=en), [Marzieh Fadaee](https://marziehf.github.io/), and [Sara Hooker](https://www.sarahooker.me/)). 

I currently work on reasoning and alignment. My recent work/findings include:
- test-time scaling generalizes well to new languages but not new domains <a href="https://arxiv.org/abs/2505.05408">(preprint)</a>.
- more coming soon :)

My past research focus is on building safe and capable multilingual LLMs. Some of my notable work includes co-developing Aya model <a href="https://arxiv.org/abs/2402.07827">(&#11089;Best Paper Award, ACL 2024)</a> and discovering that low-resource languages can jailbreak GPT-4 <a href="https://arxiv.org/abs/2310.02446">(&#11089;Best Paper Award, NeurIPS 2023 Socially Responsible Language Modeling Workshop)</a>, which became the seminal work for multilingual red-teaming.

<!-- I work on generalization of post-training to make models more capable and safe, often using cross-language phenomena as scientific lens to reveal core principles of how LLMs generalize to out-of-distribution languages, domains, and tasks. I was a main contributor to [T0](https://arxiv.org/abs/2110.08207)/[mT0](https://arxiv.org/abs/2211.01786) and [Aya](https://arxiv.org/abs/2402.07827), and I discovered [crosslingual jailbreaks](https://arxiv.org/abs/2310.02446) and [crosslingual test-time thinking](https://arxiv.org/abs/2505.05408). 

My research interests and past work include:

<div class="research-grid">
  <div class="research-box box-1">
    <strong>Generalization of reasoning and test-time thinking.</strong> I investigated how test-time scaling of reasoning models generalizes to other languages and domains. My most recent work shows successful crosslingual generalization from English due to the "quote-and-think" pattern, but limited cross-domain transfer from math domains<a href="https://arxiv.org/abs/2505.05408">(preprint)</a>.
  </div>

  <div class="research-box box-2">
    <strong>Generalization of safety alignment</strong> I discovered low-resource languages can jailbreak GPT-4 <a href="https://arxiv.org/abs/2310.02446">(&#11089;Best Paper Award, NeurIPS 2023 Socially Responsible Language Modeling Workshop)</a>, revealing core limitations in how alignment training interacts with multilingual representations. This work became the seminal work for multilingual red-teaming and has shaped safety frameworks at major AI developers including <a href="https://cdn.openai.com/gpt-4o-system-card.pdf">OpenAI</a>, <a href="https://arxiv.org/abs/2407.21783">Meta</a>, and <a href="https://arxiv.org/abs/2407.13833">Microsoft</a>. The work was also highlighted in the <a href="https://www.gov.uk/government/publications/international-scientific-report-on-the-safety-of-advanced-ai">first International Scientific Report on the Safety of Advanced AI (2024)</a> and featured on <a href="https://www.newscientist.com/article/2398656-gpt-4-gave-advice-on-planning-terrorist-attacks-when-asked-in-zulu/">New Scientist</a>. <br>
    
    I also used <strong>mechanistic interpretability</strong> to explain crosslingual detoxification <a href="https://arxiv.org/abs/2406.16235">(EMNLP 2024 Findings)</a> and crosslingual finetuning attacks <a href="https://arxiv.org/abs/2410.18210">(NAACL 2025 Findings)</a>.
  </div>

  <div class="research-box box-3">
    <strong>Generalization of instruction-following.</strong> I was the co-first author of the open-source Aya model <a href="https://arxiv.org/abs/2402.07827">(&#11089;Best Paper Award, ACL 2024)</a> and a core contributor to foundational instruction-following models T0 (<a href="https://arxiv.org/abs/2110.08207">ICLR 2022 Spotlight</a>, <a href="https://arxiv.org/abs/2202.01279">ACL 2022 Demo</a>) and mT0 <a href="https://arxiv.org/abs/2110.08207">(ACL 2023)</a>. These work demonstrated that models can learn generalizable instruction-following patterns that transfer across linguistic boundaries.
  </div>

  <div class="research-box box-4">
    <strong>Efficient adaptation to unseen languages and speech accents</strong>: I investigated how pretrained models can efficiently generalize to unseen languages through language adaptation <a href="https://arxiv.org/abs/2212.09535">(ACL 2023)</a> and synthetic data <a href="https://arxiv.org/abs/2402.14086">(EMNLP 2024 Findings)</a>, contributing to mid-training methodologies. I also studied speech pattern distributions across accent groups to enable automatic speech recognition (ASR) models to generalize to unseen speech accents (<a href="https://arxiv.org/abs/2506.04364">INTERSPEECH 2025</a>).
  </div>
</div>

 -->
