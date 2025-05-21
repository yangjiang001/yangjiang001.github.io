---
title: "Research"
permalink: /research/
layout: single
classes: wide
author_profile: true
---

<style>
.research-entry {
  display: flex;
  align-items: flex-start;
  margin-bottom: 2rem;
  position: relative;
  display: inline-block;
}
.image-container {
  position: relative;
  display: inline-block;
}
.image-container img {
  # width: 400px;
  max-width: 35%;
  height: auto;
  margin-right: 1.5rem;
  object-fit: cover;  
  flex-shrink: 0;
}
.research-entry-text {
  flex: 1;
}
.page {
  padding-left: 0 !important;
  margin-left: 0 !important;
  max-width: 100% !important;
}


.venue-label {
  position: absolute;
  top: 8px; /* 10 px */
  left: 8px; /* 10 px */
  background-color: rgba(13, 40, 216, 0.7); /* semi-transparent black  rgba(0, 0, 0, 0.7); */
  color: #fff;;
  font-size: 0.75rem;/*12px*/
  padding: 2px 6px; /*2px 8px*/
  border-radius: 4px;
  font-weight: bold;
  z-index: 2;
  box-shadow: 0 1px 3px rgba(0,0,0,0.3);
}

</style>


My research is at the intersection of AI, education, psychology, and technology. Specifically, my research is centered around:

- Developing and applying educational data mining and learning analytics methods on process data to explore how learners interact with technology-based learning and assessment systems, and how these interactions relate to cognition and learning,
- Ensuring fairness in AI and data science methods used in education, and
- Assessing and supporting complex 21st-century skills (e.g., collaborative problem solving, self-regulated learning).

---

## Educational Data Mining and Learning Analytics on Process Data

I am passionate about developing and applying educational data mining and learning analytics methods on process data to explore how learners interact with technology-based assessments and learning systems, and how the interactions are related to cognition and learning. My work often involves analyzing the wealth of process data (e.g., log files, text chats, audio, video) obtained from various types of systems, including large-scale educational assessments, intelligent tutoring systems, simulations, educational games, and virtual environments. For example, in a series of studies using data from NAEP’s digitally based assessments, we investigate test-takers’ cognitive and metacognitive processes and problem-solving strategies by integrating process data, response data, and survey questionnaire data. To uncover patterns in learner behavior and cognition, I apply advanced methods including sequence mining, feature engineering, cluster analysis, social network analysis, hidden Markov models, and visualization techniques like Sankey diagrams to make visible what is often hidden in traditional assessments. Below are select projects related to this line of work.

<div class="research-entry">
  <div class="image-container">
    <img src="/assets/images/Jiang et al 2025 Journal of Computer Assisted Learning.png" alt="Automated Writing Feedback">
    <span class="venue-label">Computers & Education</span>
  </div>div>
  <div class="research-entry-text">
    <a href="https://doi.org/10.1111/jcal.70014"><strong>Unveiling Patterns of Interaction with Automated Feedback in Writing Mentor and Their Relationships with Use Goals and Writing Outcomes</strong><br></a>
    <strong>Yang Jiang</strong>, Beata Beigman Klebanov, Jiangang Hao, Paul Deane, Oren E. Livne
    <br><em>Journal of Computer Assisted Learning</em>, 2025.
  </div>
</div>

<div class="research-entry">
  <img src="/assets/images/Jiang et al 2023 Computers and Education.png" alt="NAEP Calculator Use">
  <div class="research-entry-text">
    <a href="https://doi.org/10.1016/j.compedu.2022.104680"><strong>Using Sequence Mining to Study Students’ Calculator Use, Problem Solving, and Mathematics Achievement in the National Assessment of Educational Progress (NAEP)</strong></a><br>
    <strong>Yang Jiang</strong>, Gabrielle A. Cayton-Hodges, Leslie Nabors Oláh, Ilona Minchuk 
    <br><em>Computers and Education</em>, 2023.
  </div>
</div>

<div class="research-entry">
  <img src="/assets/images/Jiang et al 2023 JRME.png" alt="Data Mining and Problem Solving">
  <div class="research-entry-text">
    <a href="https://doi.org/10.5951/jresematheduc-2020-0290"><strong>Investigating Problem Solving on Calculator Items in a Large-Scale Digitally-Based Assessment: A Data Mining Approach</strong><br></a>
    <strong>Yang Jiang</strong>, Gabrielle A. Cayton-Hodges
    <br><em>Journal for Research in Mathematics Education</em>, 2023.
  </div>
</div>

<div class="research-entry">
  <img src="/assets/images/Jiang et al 2021 LSAE.png" alt="Process Data">
  <div class="research-entry-text">
    <a href="https://doi.org/10.1186/s40536-021-00095-4"><strong>Using Process Data to Understand Problem-Solving Strategies and Processes for Drag-And-Drop Items in a Large-Scale Mathematics Assessment</strong></a><br>
    <strong>Yang Jiang</strong>, Tao Gong, Luis E. Saldivia, Gabrielle Cayton-Hodges, Chris Agard
    <br><em>Large-Scale Assessments in Education</em>, 2021.
  </div>
</div>

<div class="research-entry">
  <img src="/assets/images/Jiang et al 2018 AIED.png" alt="Deep Learning">
  <div class="research-entry-text">
    <a href="https://link.springer.com/chapter/10.1007/978-3-319-93843-1_15"><strong>Expert Feature-Engineering vs. Deep Neural Networks: Which is Better for Sensor-Free Affect Detection?</strong></a><br>
    <strong>Yang Jiang</strong>, Nigel Bosch, Ryan S. Baker, Luc Paquette, Jaclyn Ocumpaugh, Juliana Ma Alexandra L. Andres, Allison L. Moore, Gautam Biswas
    <br><em>Proceedings of the 19th International Conference on Artificial Intelligence in Education (AIED 2018)</em>
    <br><strong>🏆 [Best Student Paper Award] [Nominated for Best Paper Award]</strong>
  </div>
</div>



---

## Responsible and Ethical Use of AI in Education

The rapid rise of generative AI, such as ChatGPT, presents both tremendous opportunities and complex challenges. One significant challenge for educators is determining whether students’ submissions are their own work or AI-generated—a task crucial for ensuring academic integrity. To address this, we developed and evaluated various methods for detecting AI-generated essays by leveraging extensive data from large-scale assessments. We systematically investigated detectors’ performance across demographic groups, ensuring the detectors are fair with no systemic disadvantages for marginalized students. Our detectors achieved near-perfect accuracy and minimal bias against non-native English speakers. Expanding this work, we incorporated process data such as keystroke dynamics and writing behaviors to identify nonauthentic writing behaviors, opening new avenues for enhancing detection methods while prioritizing fairness. Our findings offer empirical evidence to inform educational policies, support the responsible use of AI tools, and promote fairness in academic environments. This work was recognized with the Harvard Graduate School of Education Alumni Council Award for Impact in Education.

<div class="research-entry">
  <img src="/assets/images/Jiang et al 2024 Computers and Education.png" alt="AI Detection">
  <div class="research-entry-text">
    <a href="https://doi.org/10.1016/j.compedu.2024.105070"><strong>Detecting ChatGPT-Generated Essays in a Large-Scale Writing Assessment: Is There a Bias Against Non-Native English Speakers?</strong><br></a>
    <strong>Yang Jiang</strong>, Jiangang Hao, Michael Fauss, Chen Li
    <br><em>Computers and Education</em>, 2024.
  </div>
</div>

<div class="research-entry">
  <img src="/assets/images/Jiang et al 2024 AIED Table.png" alt="Bias Study">
  <div class="research-entry-text">
    <a href="https://doi.org/10.1007/978-3-031-64312-5_38"><strong>Towards Fair Detection of AI-Generated Essays in Large-Scale Writing Assessments</strong></a><br>
    <strong>Yang Jiang</strong>, Jiangang Hao, Michael Fauss, Chen Li 
    <br><em>Proceedings of the 25th International Conference on Artificial Intelligence in Education (AIED 2024)</em>
  </div>
</div>
 
<div class="research-entry">
  <img src="/assets/images/Jiang et al 2024 JEM.png" alt="Keystroke Patterns">
  <div class="research-entry-text">
    <a href="https://doi.org/10.1111/jedm.12416"><strong>Using Keystroke Behavior Patterns to Detect Nonauthentic Texts in Writing Assessments: Evaluating the Fairness of Predictive Models</strong><br></a>
    <strong>Yang Jiang</strong>, Mo Zhang, Jiangang Hao, Paul Deane, Chen Li
    <br><em>Journal of Educational Measurement</em>, 2024.
  </div>
</div>



---

## Assessment of Complex 21st Century Skills in the Age of AI

I have led and contributed to numerous large-scale, multi-year research projects focused on assessing and supporting complex 21st century skills, including collaborative problem solving (CPS) and self-regulated learning (SRL). These projects span a wide range of domains, task types, participant populations, and experimental designs, enabling us to examine the generalizability of our methodologies and findings across diverse contexts. We apply theoretically grounded approaches that integrate educational data mining, psychometric modeling, and data analytics on multimodal data to better measure these complex constructs and understand their relationship to learning outcomes. This research provides deeper insights into the dynamics of human-human and human-AI interactions, supports more valid assessments of complex skills, and informs the design of interventions or scaffolding to support the development and transfer of these critical skills.

<div class="research-entry">
  <img src="/assets/images/Jiang et al 2025 AIED Table.png" alt="LLM Coding">
  <div class="research-entry-text">
    <a href="https://doi.org/10.1111/jcal.70014"><strong>Uncovering Transferable Collaboration Patterns Across Tasks Using Large Language Models</strong><br></a>
    <strong>Yang Jiang</strong>, Jiangang Hao, Wenju Cui, Emily Kerzabi, Patrick Kyllonen
    <br><em>Proceedings of the 26th International Conference on Artificial Intelligence in Education (AIED 2025)</em>
  </div>
</div>

<div class="research-entry">
  <img src="/assets/images/Jiang et al 2025 ISLS.png" alt="Epistemic Network Analysis">
  <div class="research-entry-text">
    <a href="https://doi.org/10.1016/j.compedu.2022.104680"><strong>Using Epistemic Network Analysis and Sequential Pattern Mining to Explore the Impacts of Human Facilitation on Collaborative Mathematical Problem Solving</strong></a><br>
    <strong>Yang Jiang</strong>, Edith Aurora Graf, Jessica Andrews-Todd 
    <br><em>Proceedings of the Annual Meeting of the International Society of the Learning Sciences (ISLS 2025)</em>
  </div>
</div>

<div class="research-entry">
  <img src="/assets/images/Jiang et al 2023 Computers in Human Behavior Figure.png" alt="Personality">
  <div class="research-entry-text">
    <a href="https://doi.org/10.1016/j.chb.2022.107608"><strong>Do You Know Your Partner's Personality Through Virtual Collaboration or Negotiation? Investigating perceptions of personality and their impacts on performance</strong><br></a>
    <strong>Yang Jiang</strong>, Michelle Martín-Raugh, Zhitong Yang, Jiangang Hao, Lei Liu, Patrick C. Kyllonen
    <br><em>Computers in Human Behavior</em>, 2023.
  </div>
</div>

<div class="research-entry">
  <img src="/assets/images/Andrews Todd et al 2023.jpg" alt="CPS Across Tasks">
  <div class="research-entry-text">
    <a href="https://doi.org/10.1016/j.compedu.2023.104928"><strong>Investigating Collaborative Problem Solving Skills and Outcomes Across Computer-Based Tasks</strong></a><br>
    Jessica Andrews-Todd, <strong>Yang Jiang</strong>, Jonathan Steinberg, Samuel L. Pugh, Sidney K. D’Mello
    <br><em>Computers and Education</em>, 2023.
  </div>
</div>

<div class="research-entry">
  <img src="/assets/images/Jiang et al 2018 Book Chapter.png" alt="SRL in VPA">
  <div class="research-entry-text">
    <a href="https://www.researchgate.net/publication/320347696_How_Immersive_Virtual_Environments_Foster_Self-Regulated_Learning"><strong>How Immersive Virtual Environments Foster Self-Regulated Learning</strong></a><br>
    <strong>Yang Jiang</strong>, Jody Clarke-Midura, Ryan S. Baker, Luc Paquette, Bryan Keller
    <br><em>Digital Technologies and Instructional Design for Personalized Learning</em>, 2018
  </div>
</div>

<div class="research-entry">
  <img src="/assets/images/Jiang et al 2018 Contemporary Educational Psychology.png" alt="Note-Taking in OELE">
  <div class="research-entry-text">
    <a href="http://doi.org/10.1016/j.cedpsych.2018.08.004"><strong>Note-Taking and Science Inquiry in an Open-Ended Learning Environment</strong></a><br>
    <strong>Yang Jiang</strong>, Jody Clarke-Midura, Bryan Keller, Ryan S. Baker, Luc Paquette, Jaclyn Ocumpaugh
    <br><em>Contemporary Educational Psychology</em>, 2018
  </div>
</div>

