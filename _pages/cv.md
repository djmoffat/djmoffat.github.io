---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Profile
======
AI and environmental data science research leader specialising in the development and application of artificial intelligence across Earth observation, marine science and environmental research. I lead national AI capability through NEODAAS and institutional AI and data science capability at Plymouth Marine Laboratory, combining scientific research, strategy, infrastructure, researcher development and interdisciplinary collaboration.

My research interests include machine learning for Earth observation, marine computer vision, environmental modelling, ocean biogeochemistry, foundation models, explainable AI and the development of trustworthy and reusable AI methods for environmental science.


Scientific Leadership and National Capability
======
I provide scientific and technical leadership in artificial intelligence for marine and environmental science, combining development of national research capability with leadership of interdisciplinary research, infrastructure, researcher training and organisational AI strategy.

### National AI and Earth Observation Capability
I lead artificial intelligence activities within the NERC Earth Observation Data Analysis and AI Service (NEODAAS), supporting the UK environmental research community in the effective application of AI and machine learning to Earth observation. This includes research co-design, specialist technical advice, training, access to scalable computing infrastructure, and the development of reusable and robust AI workflows.

### AI Strategy and Research Leadership
As AI and Data Science Lead at Plymouth Marine Laboratory, I lead the development of organisational AI capability and help set strategic direction for the application of AI across marine and environmental science. My research leadership spans Earth observation, marine computer vision, environmental modelling, ocean biogeochemistry, geospatial foundation models, explainable AI and responsible adoption of emerging AI technologies.

### Research Development and Funding
I lead and contribute to collaborative research development across NERC, ESA, EC and other national and international programmes. This includes scientific concept development, interdisciplinary team building, technical design, work-package development, project planning and budgets. I have contributed to more than 20 research proposals with a combined value of approximately £6.8M.

### People and Community Leadership
I provide line management, mentoring, postgraduate supervision and technical leadership for researchers working across AI and data science. I develop and deliver specialist AI and Earth-observation training for doctoral researchers, environmental scientists and the wider research community, and contribute to scientific strategy through invited talks, panels, peer review and national and international collaborations.

Employment
======

* AI and Data Science Lead
  * Plymouth Marine Laboratory, Sept. 2021 -- Present
  * Lead the development and application of artificial intelligence and data science across marine and environmental research. Provide scientific and technical leadership in Earth observation, computer vision, environmental modelling and emerging AI approaches, alongside organisational strategy, research development, national capability, researcher development and postgraduate supervision. Lead AI activities within NEODAAS and contribute to major NERC, ESA and international research programmes.

* Lecturer in Sound and Music Computing
  * University of Plymouth, Sept. 2020 --  Sept. 2021
  * Duties included: Engage with teaching and administrative duties on the Computing, Audio and Music Technology BSc. Programme. Teaching courses on topics including computer programming, audio engineering technology and research methods. As the programme leader for the course, I perform administrative tasks, attend open days, and engage in student recruitment events. Presenting research, including outreach and engagement work and grant writing.

* Postdoctoral Researcher in AI and Signal Processing
  * University of Plymouth, Nov. 2019 -- Sept. 2021
  * Duties included: Performing research on adaptive radio technology systems for people with dementia, as part of the RadioMe project. Applications of artificial intelligence and machine learning to audio mixing, source separation, speech synthesis, signal analysis and real-time audio processing. Developing engineering solutions and research around medial application of audio technology

* Postdoctoral Researcher
  * Queen Mary University of London, May 2018 -– Oct. 2019
  * Duties included: Published research on intelligent audio production, as part of FAST-IMPACt project. Applications of artificial intelligence and machine learning to audio mixing technologies, with a focus on semantic enhancements to studio production through audio analysis and expert knowledge.

* Freelance Audio DSP Consultant and Developer
  * Self Employed, Sept. 2013 –- Present
  * Working on projects as freelance audio technology consultant, working on numerous freelance projects including:
    * Venture Capitalist technology review and due diligence consultant
    * Technology business advice and consultancy for startup business.
    * MIR and audio analysis research and implementation, including embed technology in backend web
    * services for cloud solutions
    * Development and implementation of new set of audio effects for real time embedded Arm Cortex M4
    * hardware system.
    * Development of VST plugins using JUCE framework
    * Develop and implement real time processing system of Beagle Bone Black, using Bela realtime platform
    * Musical sound synthesis developer and machine learning consultant for musical interactive project

Education
======
* Associate Fellow Higher Education Academy (AFHEA), July 2021
* Ph.D in Computer Science, Queen Mary University of London, October 2019
* Diploma in Reseracher Revelopment, Queen Mary University of London, October 2019
* M.Sc. in Digital Music Processing, Queen Mary University of London, November 2014
* B.Sc. (Hons) in Artifical Intelligence and Computer Science, University of Edinburgh, June 2011

Skills
======

* **AI and machine learning:** Extensive experience developing, evaluating and applying machine-learning methods across environmental science, Earth observation, marine science, computer vision and signal processing. Expertise includes deep learning, neural networks, computer vision, explainable AI, model evaluation and transferability, and emerging geospatial and foundation-model approaches.

* **Environmental data science and Earth observation:** Experienced in applying AI and data-science methods to satellite Earth observation, ocean colour, marine ecosystems, environmental monitoring and biogeochemical modelling, with a strong focus on scientifically robust and interpretable approaches.

* **Scientific and technical leadership:** Experienced in setting strategic direction for AI capability, leading multidisciplinary research, developing national research capability, and translating scientific requirements into effective and reusable AI solutions.

* **Research strategy and development:** Experienced in scientific concept development, interdisciplinary collaboration, research proposals, work-package development, project planning and the development of new research directions across AI and environmental science.

* **Research software and scientific computing:** Strong scientific programming and research-software background, particularly Python, Linux and Git, alongside experience with C, C++, MATLAB, Bash and LaTeX. Experienced in reproducible scientific workflows, machine-learning frameworks, geospatial computing and high-performance computing.

* **Research methods:** Extensive experience in academic research, experimental design, statistics, model evaluation, scientific publishing, peer review, research software, reproducibility and the critical interpretation of AI-derived results.

* **People and capability development:** Experienced in line management, mentoring, technical leadership, postgraduate supervision, building teams from the ground up and the development of researchers working in AI and data science.

* **Teaching and knowledge exchange:** Associate Fellow of the Higher Education Academy (AFHEA), with experience in undergraduate and postgraduate teaching, doctoral training, professional researcher development, guest lecturing, course design and delivery, and specialist AI and Earth-observation training.

* **Scientific communication and engagement:** Experienced invited speaker, trainer and scientific communicator, with experience communicating complex AI and environmental-science concepts to specialist researchers, students, interdisciplinary collaborators and wider stakeholder audiences.

* **Audio, signal processing and real-time systems:** Research and engineering background in digital signal processing, machine listening, intelligent audio production, acoustics, source separation, sound synthesis and real-time audio systems.


Publications
======
<!--   <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->
  
### Journal Publications
<ul>{% for post in site.journal reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

### Book Chapters
<ul>{% for post in site.chapter reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

### Conference Publications
<ul>{% for post in site.conference reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>



Selected Talks
======
<ul>
{% assign selected_talks = site.talks
  | where: "selected_cv", true
  | sort: "date"
  | reverse %}
{% for post in selected_talks %}
  {% include archive-single-talk-cv.html %}
{% endfor %}
</ul>

{{ base_path }}/talks/

<!-- Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
   -->

Teaching and Research Supervision
======

I have extensive experience in university teaching, postgraduate research supervision, doctoral training and professional researcher development. I am an **Associate Fellow of the Higher Education Academy (AFHEA)** and have designed and delivered teaching from undergraduate level through to specialist training for doctoral researchers and established scientists.

### Professional and Researcher Training

I regularly develop and deliver specialist training in **artificial intelligence, machine learning and Earth observation**. This has included courses and workshops for NEODAAS and the Field Spectroscopy Facility (FSF), NCEO, EUMETSAT, the Trevor Platt Science Foundation, Machine Learning for Earth observation (ML4EO) conference and other national and international research communities.

My training combines the principles of machine learning with practical scientific applications, including preparing Earth observation data for AI, classification and regression, neural networks, computer vision, model evaluation and the development of robust machine-learning workflows.

{{ base_path }}/teaching/

### Doctoral Training

I have developed and delivered postgraduate training for doctoral researchers, including the **SENSE Centre for Doctoral Training** and the **University of Exeter Environmental Intelligence CDT**. Training has covered machine learning for Earth observation, environmental data science, AI workflows, research methods and practical scientific computing.

### University Teaching and Programme Leadership

I have taught undergraduate and postgraduate material across **computer science, artificial intelligence, programming, audio engineering, digital signal processing and research methods**.

At the **University of Plymouth**, I served as Programme Leader for the BSc Computing, Audio and Music Technology programme, with responsibilities spanning teaching, curriculum delivery, student support, programme administration and recruitment.

Previously, at **Queen Mary University of London**, I contributed to teaching in sound recording and production, digital audio, sound design and electronic engineering.

### Research Student Supervision

I supervise postgraduate research applying artificial intelligence, machine learning and computational methods across environmental science, Earth observation and interdisciplinary applications.

**Current PhD supervision**

* **Camila Toledo**, University of Exeter, Second Supervisor, 2024–present
* **Irene Monreal Campos**, University of East Anglia, Fourth Supervisor, 2024–present
* **Nuria Bachiller**, University of Exeter, Third Supervisor, 2024–present  
  *AI for river plume detection*

**Completed PhD supervision**

* **Satvik Venkatesh**, University of Plymouth, Second Supervisor, completed 2023

  
<!-- Service and leadership
======
* Currently signed in to 43 different slack teams -->
